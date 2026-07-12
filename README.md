# React Stellar SDK

A Create React App scaffold set up for building a Stellar network demo client, showing a standard CRA + Bootstrap project structure with the Stellar SDK wired in as a dependency.

## What's inside

- Create React App project structure (`react-scripts` build/dev/test tooling)
- Bootstrap and Reactstrap for UI components, Sass for custom styling, Font Awesome for icons
- `stellar-sdk` included as a dependency for interacting with the Stellar network
- A minimal `App` / `Demo` component pair as the starting point for the demo UI

## Tech stack

- React
- Create React App (react-scripts)
- Bootstrap / Reactstrap
- Sass
- Font Awesome
- Stellar SDK

## Quickstart

```bash
yarn install
yarn start
```

Opens the app in development mode at [http://localhost:3000](http://localhost:3000).

Other available scripts:

```bash
yarn test   # run the test runner in watch mode
yarn build  # build a production bundle to the build/ folder
```

## Project structure

```
src/
  App.js     # top-level app shell
  Demo.js    # demo view (starting point for Stellar SDK integration)
  assets/scss/  # custom Sass styles
public/        # static assets and HTML template
```
