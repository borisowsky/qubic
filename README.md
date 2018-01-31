# React Rich Starter
React starter project with pre-configured development and production-ready build scripts

## Usage
| Command | Action |
| --- | --- |
| `yarn dev` | Runs project in *development* mode |
| `yarn build` | Runs `yarn clean` command and build application in *production* mode |
| `yarn clean` | Removes project's build folder (`public/dist`) |
| `yarn start` | Runs [Express](http://expressjs.com/) server in *production* mode |
| `yarn test` | Runs tests using [Jest](https://facebook.github.io/jest/) |

## Features
* Latest stable versions of React, React-Router, Webpack etc.
* Great development experience (HMR with [RHL](https://github.com/gaearon/react-hot-loader), [Redux DevTools](https://github.com/gaearon/redux-devtools), [Linting](https://eslint.org/))
* Seperated Webpack configs
* Sass (SCSS) with [CSS Modules](https://github.com/css-modules/css-modules)
* Pre-configured styles with [Bootstrap](https://getbootstrap.com/) grid system and [normalize.css](https://necolas.github.io/normalize.css/)
* Production-ready Webpack configuration with vendor splitting, gzip compression, JS/CSS minification and [bundle analysis](https://www.npmjs.com/package/webpack-bundle-analyzer)