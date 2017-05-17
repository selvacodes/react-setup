**React Setup**

Simple React starter kit 

Uses Express for server

**Features**
 - Has sample components with proper linting
 - Minimal [Webpack](https://webpack.js.org/) config with loaders
 - [ESLint](http://eslint.org/) configured with recommended settings 
 - [Babel](https://babeljs.io/) plugins configured
 - [Flow](https://flow.org/en/) configured and type files added for used libs
 - [Prettier](https://github.com/prettier/prettier) configured for formatting
 - Git hooks configured with [husky](https://github.com/typicode/husky) and [lint-staged](https://github.com/okonet/lint-staged)
 - [Styled components](https://github.com/styled-components/styled-components) are used for CSS-in-js

** Scripts	**

``` js

yarn install // install deps

yarn run build  // webpack build

yarn run start  // runs express @4000

yarn run fix // formats and fixes lint

yarn run lint-strict // formats,fixes lint and type checks

```
Has pre-commit git hook which prevents you to check in bad code
