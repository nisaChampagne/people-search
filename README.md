# CokPeopleSearchFrontend

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.2.1.

## Development server

Run `(!searchValidationResult.valid) ` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `npm run build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `npm run test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `npm run e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Deploying

run `AWS_PROFILE=cok npm run build:dev:deploy` or `AWS_PROFILE=cok npm run build:prod:deploy`

## Monitor logs

AWS_PROFILE=cok serverless logs -f FUNCTION -s dev -t

AWS_PROFILE=cok serverless logs -f FUNCTION -s production -t


API Documentation
https://docs.google.com/document/d/1145R9-FcmA1NMXMAwbzFmNZ4DRtdWuazCsZYtJa8Owg/edit#heading=h.fzmuu9lzv3sm
