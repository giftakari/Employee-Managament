# I created a fake API using Json-Sever 

I created a fake server using json-server and then copied the response from ABCis api into, that way I can play with api locally and not mess original copy

To run the server Run `json-server --watch server/server.json`. The server runs on `localhost:3000`, to view the data visit `localhost:3000/todos`


# Use Boostrap for Styling. 

Considering the time frame for this project , Bootstrap is the best. 

# Components and routes

CRUD entails 
1. Create 
2. Read 
3. Update 
4. Delete

I created 3 components:
- Employee-create [Creates an employee]
- Employee-edit. [edits an empployee]
- Employee-list  [Display list of employees]

components as the delete does not need a component and all components have routes 

# HTTPClient API for data fetching | Dependency Injection(Services)

shared class,for the expected data and then 
used Observables. 

### Functionalities 

- CREATE EMPLOYEE
- DELETE EMPLOYEE
- UPDATE EMPLOYEE
- READ LIST OF EMPLOYEES

Rest api was created to manage this in the shared folder

Thank you for your time 


![EmployeeManagement3](https://user-images.githubusercontent.com/37270379/112063599-667cf380-8bad-11eb-9ad6-dfc8c627ccfe.png)


# EmployeeManagement

## Video demo of the project 

<video width="420" height="440" controls>
  <source src="https://user-images.githubusercontent.com/37270379/120446449-e94fd500-c3cc-11eb-9755-ce2dc6c081e0.mp4" type="video/mp4">
</video>


![EmployeeManagement3](https://user-images.githubusercontent.com/37270379/120446449-e94fd500-c3cc-11eb-9755-ce2dc6c081e0.mp4)


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
