## Frontend styles helpers kit

Helpers kit for scss / sass based on webpack

### How use kit:

> `git clone https://github.com/TeriFash/scss-helpers-kit.git` in your folder.<br />

> `@import "./src/styles/core.scss"` in your scss, or copy folder `./src/styles` in project styles

### Extended use:

✍ Run installation dependencies.<br />

> `npm install` or `yarn install` 

🏃 Start Dev Server environment.<br />

> `npm start` or `yarn start`

🎁 Build production version.<br />

> `npm build` or `yarn build`

🚚 Features:

* ES6 Support via [babel](https://babeljs.io/) (v7)
* SASS Support via [sass-loader](https://github.com/jtangelder/sass-loader)
* Linting via [eslint-loader](https://github.com/MoOx/eslint-loader)

When you run `npm run build` we use the [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) to move the css to a separate file. The css file gets included in the head of the `index.html`.
