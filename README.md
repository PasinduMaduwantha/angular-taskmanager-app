# AngularLearning

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.1.6.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Backend
JSON Server is a freely available Node package that can turn a JSON file on your computer into mock data storage. When JSON Server is running, we can send requests to get data from storage or add data to it, as though we were talking to a server with a database. A huge benefit of JSON Server is that we don't have to spend much time setting the mock server up, allowing us to focus on developing the frontend of an application first.
Use jasom server install it with npm ,

npm install json-server

"server": "json-server --watch db.json --port 5000"
add to the package.json

to run json server 
type npm run server and press enter 

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
