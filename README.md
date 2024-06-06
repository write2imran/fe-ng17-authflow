# FeNg17Authflow

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.3.2.

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


# How it works

## run following commands using git baxh terminal, it will create three services
ng g s core/services/auth && ng g s core/services/storage && ng g s core/services/user && ng g s core/services/eventbus

## generate the components
ng g c auth/components/login  && ng g c auth/components/register && ng g c auth/components/home && ng g c auth/components/profile && ng g c auth/components/admin && ng g c auth/components/moderator && ng g c auth/components/user && ng g c auth/components/admin && ng g c auth/components/moderator

## generate interceptor
ng g interceptor auth/authinterceptor

Install 
- bootstrap
- popper
- jquery


