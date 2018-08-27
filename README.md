# Ventrips

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.5.

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

# ventrips
1. sudo npm install -g npm
2. sudo npm install -g @angular/cli
3. clone ventrips-app repo
4. cd into ventrips directory
5. sudo npm install
6. ng serve --open

Visual Studio Code
1. Install ESLint
2. Install TSLint
3. Install GitLens

Deploy
1. Open Google Cloud Shell or visit: https://console.cloud.google.com/cloudshell/editor?project=ventrips-214422&shellonly=true&fromcloudshell=true
2. Pull the latest repo
3. ng build --prod
4. [Optional to test web preview of latest changes] node server.js
5. gcloud app deploy