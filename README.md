# AngularTourOfHeroes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.1.3.

This is based on the Angular tutorial [Tour of Heroes application](https://angular.io/tutorial/tour-of-heroes)

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


## learnings

### Section 2: The Hero Editor 

#### Show HeroesComponent
When adding the new hero component to the component view be sure to import the component into the app.component.ts file. After some research found out that I was missing the `--no-standalone` it was mentioned as a note in the first page that I had missed. This is because I am using Angular 17+.

#### Format with the UppercasePipe
The pipe does not work on it's own. When you add the pipe you should import the in this case the CommonModule which contains the UppercasePipe into the `heroes.component.ts`.

### Section 3: Create a feature component

## Show the HeroDetailComponent
The component must be imported into the parent component in this case the `heroes.component.ts` file. 