<p align="center">
    <img src="./public/logo.png" width="400px" alt="CrescentCMS Logo">
</p>

<h1 align="center">CrescentCMS</h1>

<p align="center">
    <a>English</a> |
    <a href="./README-id.md">Indonesia</a>
</p>


An easy to use, customizable, and self-deployable CMS (Content Management System) designed specifically for mosques.

...

# Getting Started

## 🚀 Deploying Your Own CrescentCMS

...

## 🔃 Updating The Template

...

# Contributing to Development

To contribute to the development of CrescentCMS, you will need to have a basic understanding of Astro, React, and TailwindCSS (with daisyui). You can learn more about Astro [here](https://docs.astro.build/).

To get started simply clone the repository and install all the necesary packages. You will need `Node 16+` and `yarn` as the package manager.

## 📂 Project Structure

Inside of the project, you'll see the following folders and files:

```
/
├── public/
│   └── * (static assets)
├── src/
│   ├── components/
│   │   └── *
│   ├── layouts/
│   │   └── * 
│   ├── pages/
│   │   └── * 
│   ├── env.d.ts  
│   └── global.css
│
├── astro.config.mjs
├── tailwind.config.js
├── tsconfig.json
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

We use `yarn` as our package manager so all commands will be using `yarn` (Please do not use `npm` or other package managers).

All commands are run from the root of the project, from a terminal:

| Command             | Action                                           |
| :------------------ | :----------------------------------------------- |
| `yarn install`      | Installs dependencies                            |
| `yarn dev`          | Starts local dev server at `localhost:3000`      |
| `yarn build`        | Build your production site to `./dist/`          |
| `yarn preview`      | Preview your build locally, before deploying     |
| `yarn astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `yarn astro --help` | Get help using the Astro CLI                     |

## Setting up

# 📚 Learn More

Check the Wiki (to be added later)