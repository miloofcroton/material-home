# Angular Material Homepage

## About

This project is to create a modern single page app that functions extremely well as a homepage with diverse topics that need to have proper navigational separation. Material Design is beautiful and will therefore be used as a base.

## Things to Fix

#### Design
* decide how to make photosharing easy in the 'life' tab

#### Content
* make fetch-assets.sh and fetch-assets-local.sh point to local html
* change categories for top tabs and add some minified html for bare minimum
* make markdown script convert local markdown to local html
* create actual markdown documents to get site started
* add LaTeX/KaTeX/MathJax support to markdown engine

#### Style
* make background on homepage randomize like other website
* host background images
* customize 'theme button' to include different/better options
* consider alternate fonts

#### Features
* add multiple tiers in sidebar menu, perhaps with collapsible content
* add search bar with dropdown results as you type
* add mindmap view to pages

#### Tools
* set up hosting
* integrate with CircleCI
  * add build icons to readme confirming success of builds
* consider adding any other desirable tools
  * gulp, webpack
  * mongoose, mongodb
  * express
  * nginx
  * docker

#### Versions
* upgrade angular-cli.json version to recent Angular CLI version


--------------------------------------------

## Preview
https://material2-docs-dev.firebaseapp.com/

## Deployment instructions
```
> npm install

# Development
> npm run publish-dev

# Production
> npm run publish-prod
```

For development builds use the usual `ng serve` and `ng build` commands.


----------------------------------------------------------------------------------------------------------------


This project was generated with [angular-cli](https://github.com/angular/angular-cli) version 1.0.0-beta.19-3.

## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

#### Issues

One solution if you get `Error: Cannot find module 'webpack/lib/node/NodeTemplatePlugin'` error with Webpack:

*Note: This will hopefully be fixed after upgrading Angular-CLI version in the angular-cli.json*

```
npm install -g @angular/cli
npm install @angular/cli
npm install
```


## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the `angular-cli` use `ng --help` or go check out the [Angular-CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

----------------

## Credits and Inspiration

* [https://material.angular.io/](The Material Design project for Angular) for doing almost everything right
* [James Friedman and rmwc](https://jamesmfriedman.github.io/rmwc/) for making the best Material framework for React, which made me focus on Material Design before I saw Angular's team did it better
* [Google Earth](earthview.withgoogle.com) for taking awesome pictures and letting us use them freely
* [https://github.com/andrewbanchich/dimension-jekyll-theme](Andrew Banchich) for showing me how easy it is to make a nice-looking website
