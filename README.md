# Projektstruktur:

Vi organiserer billeder i vores img-mappe inden under vores assets-mappe. Derudover har vi lavet en general.css mappe, hvor vi derfinerer hyppigt brugte variabler.

Alle vores pages er organiseret inde i pages-mappen, hvor index.astro også er palceret.

# Navngivning:

Vi navngiver vores filnavne med udelukkene små bogstaver når det gælder enten css eller javascript filer. Derudover, er alle vores astro-filer skrevet med et stort forbogstav for hvert ord. Dette gælder også for vores koponenter, som fx er navngivet: CardEspergaerde.astro. Vi har selvfælgelig kun brugt engelsk tastetur til navngivning.

# Link til scripts:

Vi har palceret script referencer i HTML'en i sidst i <body> med defer attribute.

# Git branches:

Vi navngiver vores gitbranches efter hvilken funktion der bliver arbejdet videre på i den branch, men har ikke inkluderet hvem der arbejder hvor i navnet.

# Arbejdsflow:

Vi sikrer at ingen arbejder i de samme filer ved at uddelegere arbejdet imellem os og kommunikere grundigt, så vi undgår merge-conflicts. Derudover, skriver vi beskrivende commit-beskeder på engelsk, så vi ikke er i tvivl om hvad hinanden har lavet.

# Kode:

## Beslut hvilken CSS selector i benyttes til referener i henholdsvis CSS og JavaScript(fx. id'er til JavaScript og Classes til CSS)

Vi bruger classes til CSS for styling, og ID'er til Javascript for at give dem JS funktioner

## Skal filer have korte forklaringer som kommentarer?

Vi har valgt at det generelt er en meget god ide med en del kommentarer undervejs, så alle i gruppen kan forstå hvad der sker hvor, og hvad det gør ved fx. styling eller funktioner ect.

# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
