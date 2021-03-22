# I created a fake API
I created a fake server using json-server and then copied the response from ABCis api into, that way I can play with api locally and not mess original copy

To run the server Run `json-server --watch server/server.json`. The server runs on `localhost:3000`, to view the data visit `localhost:3000/todos`


# Use Boostrap for Styling. 
Considering the time frame Boostrap is easier for the project again 

# Components and routes
CRUD entails Create , Read, Update , Delete
I created 3 (employee-create, employee-edit, employee-list for Reading all data)components as the delete does not need a component and all components have routes 

# HTTPClient Api for data fetching
shared class,for the expected data and then 
used Observables. 
### Functionalities created
CREATE EMPLOYEE
DELETE EMPLOYEE
UPDATE EMPLOYEE
READ LIST OF EMPLOYEES
Rest api was created to manage this in the shared folder

Thank you for your time XXX^

# EmployeeManagement

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.1.

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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
