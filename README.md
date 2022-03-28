# Versions

## [1] When project was created

`node -v`
v16.14.0

`npm -v`
8.5.5

`ng version`
Angular CLI: 13.3.0
Node: 16.14.0
Package Manager: npm 8.5.5
OS: win32 x64

Angular: 13.3.0
... animations, cli, common, compiler, compiler-cli, core, forms
... platform-browser, platform-browser-dynamic, router

@angular-devkit/architect 0.1303.0
@angular-devkit/build-angular 13.3.0
@angular-devkit/core 13.3.0
@angular-devkit/schematics 13.3.0
@schematics/angular 13.3.0
rxjs 7.5.5
typescript 4.6.3

## [2] Version upgrades after project was created

N/A

---

# List of steps performed:

### 1 - Create project

`ng new NgApp --routing --style=scss`

### 2 - Add angular material

`ng add @angular/material` [Getting Started with Angular Material](https://material.angular.io/guide/getting-started)

selections: Indigo/Pink, Global Typography (No), Browser Animations (Yes)

### 3 - Add ng bootstrap (installs standard bootstrap)

`ng add @ng-bootstrap/ng-bootstrap` [NG Bootstrap - Angular powered Bootstrap widgets](https://www.npmjs.com/package/@ng-bootstrap/ng-bootstrap)

Note: This installs bootstrap as well as a dependemcy (verified by inspecting package.json)

---

Default README

# NgApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
