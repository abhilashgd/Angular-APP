# Angular-APP

# References:

       LTS version:  https://nodejs.org/en/
       Angular commands: https://angular.io/cli
Pligins:  
       emmet

UI : http://localhost:4200/


# Angular APP

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.0.4.

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
-------------------------------------------------------------------------------------------------------------------------------------------------

# Planning the App

Components - 
Root, Header, Features

**Project Setup**

              1. project- Make sure, you do create that app by also adding the --no-strict flag to the ng new command 
                      $ ng new abhilashgd-angular-app  --no-strict
                             ? Would you like to add Angular routing? No
                             ? Which stylesheet format would you like to use? CSS
                      
              2. Install Bootstrap CSS Framework - npm install --save bootstrap@3
                           when using a project created with Angular CLI 6+ (check via ng v ), you'll have an angular.json  file instead of an .angular-cli.json  file. In that file, you still need to add Bootstrap to the styles[]  array a
                           Path: node_modules/bootstrap/dist/css/bootstrap.min.css
**Application Setup**
              
      1.  $ ng new appName --no-strict
       Inside project folder $ npm install --save bootstrap@3
      2.  ng_modules-->bootstrap-->dist-->css
       add a path in angular.json file (path should be relative to index.html file
       ../node_modules/bootstrap/dist/css/bootstrap.css
       
       Example: 
         "styles": [
              "../node_modules/bootstrap/dist/css/bootstrap.min.css",
              "src/styles.css"
            ],
       3. ng serve     http://localhost:4200/
            
            
            
