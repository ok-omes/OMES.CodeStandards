# Javascript Style Guide

## Formatting
[Prettier](https://prettier.io/) and [ESLint](https://eslint.org/) are the defacto goto's but they do not always work in conjunction.

The recommended use is of ESLint and then Prettier through a ESLint plugin. 

## Usage
In the sample `package.json` is a list of dev dependiecies to use to get the recommended use wired up to a project.

There is also a `.eslintrc.js` file that you will need to put in the root of your project.

## Extend
These settings are comprised of various ESLint plugins, you can visis a plugin documantation to look for something not implemented.
* [eslint-config-airbnb](https://www.npmjs.com/package/eslint-config-airbnb)
* [eslint-config-prettier](https://www.npmjs.com/package/eslint-config-prettier)
* [eslint-plugin-html](https://www.npmjs.com/package/eslint-plugin-html)
* [eslint-plugin-import](https://www.npmjs.com/package/eslint-plugin-import)
* [eslint-plugin-jsx-a11y](https://www.npmjs.com/package/eslint-plugin-jsx-a11y)
* [eslint-plugin-prettier](https://www.npmjs.com/package/eslint-plugin-prettier)
* [eslint-plugin-react](https://www.npmjs.com/package/eslint-plugin-react)
* [eslint-plugin-react-hooks](https://www.npmjs.com/package/eslint-plugin-react-hooks)
* [prettier](https://www.npmjs.com/package/prettier)

## With VS Code
1. Install the [ESLint package](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
2. Now we need to setup some VS Code settings via `Code/File `→ `Preferences` → `Settings`. It's easier to enter these settings while editing the `settings.json` file, so click the Open (Open Settings) icon in the top right corner.
3. Add the [following](./.vscode/settings.json) to the `settings.json`.


## Considerations
This was built with [React](https://reactjs.org/) in mind, if you are needing to use with a [Node](https://nodejs.org/en/), [Angular](https://angular.io/) or [Vue](https://vuejs.org/) project please think about submitting a PR with the correct changes.