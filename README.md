# ⚛ Electron - React - NextUI Template With Router

A simple template for you to use Electron + React + NextUI together.

# Features

-   Use React for creating interfaces
-   Use `react-router-dom` for routing
-   Use NextUI for componets which based on TailwindCSS and Framer Motion.
-   Use TailwindCSS for styling

# Insatllation

## Prerequisite

### Install concurrently & wain-on
```shell
yarn add concurrently wait-on --dev
```

Concurently allows us to run mutliple commands within one script and wait-on will wait for port 3000 which is the default CRA port, to launch the app.

### Install electron-forge
```shell
yarn add --dev @electron-forge/cli
npx electron-forge import
```
Electron Forge is an all-in-one tool that handles the packaging and distribution of Electron apps.

### Use this repo
-   Clone repo
-   Run `yarn` to install dependencies.
-   Run `yarn dev` to start development server
-   Run `yarn make` to create executable

# Contributing

Feel free to use GitHub's features.