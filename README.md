# Webpack Starter Template
A webpack boilerplate template for getting a web page up quickly with webpack

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Support](#support)
- [Contributing](#contributing)

## Installation
Download to your project directory, add `README.md`, and commit:

```sh
git clone https://github.com/ZachTRice/webpack-starter-template.git
npm install
npm run build
npm start
```

## Usage
### Build
`npm run build` - Creates the project in **production** mode and outputs to the dist folder.   
`npm run watch` - Creates the project in **development** mode and outputs to the dist folder.   
`npm start` - Creates the project in production mode, runs webpack-dev-derver, watches changes & refreshes page. Changes are output to the dist folder.   

### Test
`npm run test` - Runs lint tests; Add unit and e2e as needed   
`npm run lint` - Runs eslint and stylelint tests   
`npm run lint:js` - Runs eslint test   
`npm run lint:css` - Runs stylelint test   

### Tools
`npm run generate:images` - Create a placeholder image (Right now you must manually update tools/image-generator.js to change the image size)

## Support
Please [open an issue](https://github.com/ZachTRice/webpack-starter-template/issues/new) for support.

## Contributing
Please contribute using [Gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow). Create a feature branch, add commits, and [open a pull request](https://github.com/ZachTRice/webpack-starter-template/compare/).
