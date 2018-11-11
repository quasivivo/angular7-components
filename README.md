# Starter

This project demonstrates a simple way to define an Angular app as a customElement and embed it within another app using a defined tag name.  This relies on the @angular/elements package.  Basic steps required:

$ npm run bundle

$ cp dist/starter/elements.js /your/project/assets/elements/my-cool-element.js

Within your project, inject a script tag on demand with "my-cool-element.js" as the source.  Any instance of "my-cool-element" will render your Angular app.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
