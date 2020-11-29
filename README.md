# SpaceX Test App

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.0.1 with HTML, SCSS and responsive UI.

It's developed using SpaceX API with three filters: Launch date, Successful Launch & Successful Landing.

If user select any filter it will reflect in the URL. All filters are grouped and have toggle behaviour in respective group of options.

Once user refresh the page then instead of showing all the results it will load the data with last applied filters.

## Demo

[Live Link](https://hasan-spacex.herokuapp.com/)

## SSR Implemented

Server Side Rendering is also implemented on this application, which load the page with boilerplate page and helps to show the page instantly.


## Development Server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

Run `npm run dev:ssr` for start rendering your app with Universal on your local system.

## Code Scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Lighthouse Report

Accessability: **100** - SEO: **89** - Performance: **74**

[Report Link](https://www.awesomescreenshot.com/image/5736499/9150f1608744347e3dd8845ccf029efe)