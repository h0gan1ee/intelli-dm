# IntelliDM

## Development Guide

### Setup

Run `yarn` to setup.

### Scripts

- `yarn dev`: Build and run development server with HMR support.
- `yarn format`: Format code with ESLint.
- `yarn build`: Run `yarn format`, then if successful, build production artifacts to `/dist`.
- `yarn preview`: Deploy `/dist` to a simple local server.
- `yarn prod`: A shorthand for `yarn build && yarn preview`.

### Major Dependencies

- Vue 3: https://v3.vuejs.org
- Vite: https://vitejs.dev
- Tone.js: https://tonejs.github.io
- ESLint: https://eslint.org
- eslint-plugin-vue: https://eslint.vuejs.org
- Yarn: https://yarnpkg.com

### Programming and Markup Languages (as so far)

- HTML
- Javascript
- CSS
- Vue 3 (SFC)

### Merge Request

#### Enforced rules

1. Before you open a merge request, make sure you've run `yarn prod` successfully, and carefully test as many things as
   possible locally.
2. Always keep your working branch the same; otherwise, you should delete the branch after merging.
3. Combine all commits into one when merging to `master` branch.

#### Best practice

1. Make your commit message simple and informative.
2. Describe all changes in merge request if possible.
3. Review others' requests carefully.
