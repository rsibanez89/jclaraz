# Jclaraz

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.5.

* Run `ng new jclaraz --routing --style=scss --prefix=jc`

  * --routing: will do add routing to the project
  * --style=scss: will change default styling to be scss
  * --prefix=jc: will do all new components to be prefixed jc

* Run `npm install --save @angular/material @angular/cdk`
* Run `npm install --save @angular/animations hammerjs`
* Run `npm install --save @angular/flex-layout`


## Development server

* Run `npm install`
* Run `ng serve`. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

* Run `ng generate component component-name` to generate a new component. 
* Run `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Running unit tests

* Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Build for deployment

* Run `ng build --prod --aot` to build the project. The build artifacts will be stored in the `dist/` directory.

## Deploy to S3

 * Run `aws s3 cp ./dist/jclaraz s3://jclaraz --recursive`
 * Go to http://jclaraz.s3-website-sa-east-1.amazonaws.com