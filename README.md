# React Rich Starter

React starter project with pre-configured development and production-ready build scripts.

## Usage

| Command      | Action                                                                                                   |
| ------------ | -------------------------------------------------------------------------------------------------------- |
| `yarn start` | Run `yarn dev`.                                                                                          |
| `yarn build` | Build application in _production_ mode with specified `CLIENT_ENV` (`production` – by default) variable. |
| `yarn clean` | Remove `dist` folder.                                                                                    |
| `yarn dev`   | Run project in _development_ mode.                                                                       |

## Features

- Great experience with latest versions of [React](https://reactjs.org/) and [TypeScript](https://www.typescriptlang.org/).
- Support for `.env` files – [release notes](https://github.com/borisowsky/react-rich-starter/releases/tag/v1.1.0).
- Great development experience using [hot-rolading](https://github.com/gaearon/react-hot-loader), linting with [TSLint](https://palantir.github.io/tslint/) and [Prettier](https://github.com/prettier/prettier).
- Built-in SCSS/Sass integration with [CSS Modules](https://github.com/css-modules/css-modules) for `*.module.(css|scss|sass)` files.
- Pre-configured [normalize.css](https://necolas.github.io/normalize.css/).
- Production-ready Webpack configuration with code splitting, ES5 transpilation and minification.
