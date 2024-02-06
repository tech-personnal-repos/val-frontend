Following env var should be set as secrets in a "production" environnement:

- APP_PATH: the path where you want the front files to be (in my case "/var/www/front")
- BACKEND_HOST: the IP address of your backend server
- HOST: the IP address where the front should be hosted
- SSH_KEY: the private ssh key which will be used by ansible to connect to your front and deploys it
- USER: the user to use to connect to the front server  
  
---
module:			T-NSA-700
title:			devOps
subtitle:   README front

noFormalities: true

author:     ??
version:    0.3
---


# Front

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.1.4.

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
