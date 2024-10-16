# bash_cards

Practice project inspired by a Vue.js tutorial I found on [Youtube by Susan B.](https://codewithsusan.com/notes/vuejs-simplified-1) for a simple flashcard app.

I will use it for creating flashcards to practice BASH/Linux utility commands in a similar way as I did to pass my CompTIA Linux+ certification.
I hope to also implement a simple database so that additional cards may be added or removed via a restful API moving forwards.

My plan is to poach the idea, and the basic outline of the project form Susan B's code, but implement a more complex version following Test Driven Development (TDD) principles for the fist time and also attempting to use TypeScript (TS) and PHP for the first time, both as a novice, in a full stack project.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run Unit Tests with Coverage resulsts with [Vitest](https://vitest.dev/)

```sh
npm run test:coverage
```

### Run End-to-End Tests with [Playwright](https://playwright.dev)

```sh
# Install browsers for the first run
npx playwright install

# When testing on CI, must build the project first
npm run build

# Runs the end-to-end tests
npm run test:e2e
# Runs the tests only on Chromium
npm run test:e2e -- --project=chromium
# Runs the tests of a specific file
npm run test:e2e -- tests/example.spec.ts
# Runs the tests in debug mode
npm run test:e2e -- --debug
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
