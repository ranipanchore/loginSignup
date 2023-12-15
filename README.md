# Demo

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.2.10.



<!-- important package and command to create project -->

ng new demo
cd demo

npm i bootstrap
npm i axios

add in style.css file------    @import "~bootstrap/dist/css/bootstrap.css";


ng generate environments
    add this two:-- 
    apiUrl: 'apiBASE URL here',  
    apiKey: 'insert_api_key_here'


ng generate component login
ng generate component register
ng generate component dashboard


ng generate service user-auth
ng generate interface user/user

	
ng serve

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
