# Teknisk dokumentation for Tema 10 gruppe eksamensprojekt (Et website til 1257°)

Vi har skrevet denne readme for at sikre, en så strømlignet samarbejdsproces som muligt.

## Projektstruktur:

- Organisering af billeder, fonte og andre ressourcer:

  Billeder er placeret i en mappe kaldet 'img'
  Fonte (adobe) linkes til i <head> i mainLayout, samt defineres i css variabler (style.css)
  Andre ressourcer ligger i en mappe kaldet 'assets' (logo, video...)

- Alle pages er placeret i en pages mappe i scr.

- Vi arbejder med komponenter, som alle ligger i en components mappe i scr.

## Navngivning:

- Filnavne skrives med små bogstaver og uden mellemrum fx: index.astro, about.astro, style.css...

## Link til scripts:

- Vi refererer til scripts i vores fences i mainLayout.astro.

## Git branches:

- Vi navngiver branches således, så det er klart for alle hvad de forskellige commits gør: add/remove-feature-navn -> add-menu-luna

## Arbejdsflow:

- Vi sørger for at have opdelt vores prototype i komponenter, så det er let at arbejde flere på samme tid - Uden at man sidder i den samme fil.

## Kode:

- Hvordan skriver i funktioner i JavaScript?(fx med function keyword eller som arrow functions)

- For at sikre at koden er let for alle at finde rundt i, opdeler vi stylesheets med kommentarer så man kan se hvad den givne styling gør fx: /** styling af menu **/

# Funktionalitet

- Vi har arbejdet med dynamisk indhold fra superbase til vores eventkalender.
- Vi har en sign-up til venteliste knap, der skal føre videre til et googleforms opskrivningsscheet.

# API endpoints

Link til superbase?

# Dokumentation af Funktion

Dette afsnit skal beskrive en funktion I selv har udviklet. Det kunne eksempelvis være en funktion der generere en listen over fx. produkter:

- Beskrivelse: Hvad gør funktionen? Hvordan spiller den sammen med resten af koden?

# Astro Starter Kit: Minimal

```sh
npm create astro@latest -- --template minimal
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/minimal)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/minimal)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/minimal/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

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
