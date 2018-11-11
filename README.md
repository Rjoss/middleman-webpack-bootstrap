# Middleman Template

The base Middleman application ready to deploy to [Netlify](https://www.netlify.com/).

## Configuration

This template uses [Webpack] for asset processing through the external pipeline. Features include:

- [Sass]
- [Autoprefixer]
- [Babel]

  [Webpack]: https://webpack.js.org/
  [Sass]: https://sass-lang.com
  [Autoprefixer]: https://github.com/postcss/autoprefixer
  [Babel]: https://babeljs.io

## Use

`middleman init MY_PROJECT_FOLDER -T git@github.com:rjoss/middleman-webpack-bootstrap.git`

Install dependencies:

`bundle`

`yarn`

Server:

`bundle exec middleman`

Build:

`bundle exec middleman build`
