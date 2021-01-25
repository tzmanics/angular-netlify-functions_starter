# o(^▽^)o Angular Netlify Functions Starter

This project has the bare-bones pieces to get you started adding serverless functions to you Angular application. [Netlify Functions](https://www.netlify.com/products/functions/?utm_source=repo&utm_medium=ng-func-starter-tzm&utm_campaign=devex) wrap up AWS Lambda Functions so you don't need an AWS account, manage your functions alongside your app in Netlify, and Netlify handles all the infrastructure.

> 📓 [Check out this blog post](TODO: add blog post) to get even more details about what's going on in this project.

## Setup

### Local Setup

- run `ng build` to build out the project.
- install the Netlify CLI to run the functions locally `npm i netlify-cli -g`
- run `netlify dev` to start up the project locally
- got to [`http://localhost:8888/.netlify/functions/hello?location=Lorain`](http://localhost:8888/.netlify/functions/hello?location=Lorain) to see the function output
- feel free to change the `location=Lorain` query parameter to see it change.

### Productions Setup

- install the Netlify CLI `npm i netlify-cli -g`
- run `netlify init` to setup the project on Netlify & deploy it!
- run `netlify open` to open the project dashboard, under the 'Functions' tab you can find the endpoint for your function as well as see all the logs.

To skip all this you could also just click this button:

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/tzmanics/angular-netlify-functions_starter)

## The Pieces

There are two things added to the angular skeleton app in this project. A Netlify configuration file (`netlify.toml`) and a directory holding one serverless function file (`.functions/hello.js`).

Want more details on what these pieces are and why they are there? [There's a blog post for that, check it out!](TODO: add blog post).

# Angular CLI Infos

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
