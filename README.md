# TestCordovaApp

### Creating your own cordova/angular2 project

Like any other Angular 2 application, start with @angular/cli.  This will generate the basic Angular 2 application with all dependencies.

```
ng new testCordovaApp
cd testCordovaApp
cordova create cordova <bundle-identifer> "<App-Name>"
cd cordova
cordova platform add <platform>
cordova run [ios | android | browser]
```

---

To run a mobile app platform or in the browser through cordova, ```cd``` into the cordova directory and run

```
cordova run [ios | android | browser]
```

This will automatically build the angular cli project and move the files into the ```www``` directory.


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.6.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
