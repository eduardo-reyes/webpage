# Proyecto Desarrollo Web Frontend: Página web

## Autores

    1. Erick Iram García Velasco
    2. José Luis López Bautista
    3. Eduardo Alfonso Reyes López

## Pre-ejecución

Crear un esquema en MySQL. En la carpeta database/ se encuentran dos scripts SQL. El archivo DDL contiene las definiciones de las tablas de la base de datos. Mientras que el DML tiene el poblamiento de la misma.
Para visualizar en su totalidad la página web, es necesario ejecutar ambos scripts en el correspondiente esquema MySQL.

En el archivo application.properties en la carpeta API-DWF_v1.0.5 hacer los siguientes cambios en cada campo:
    -> En el url cambiar schema_name por el nombre del esquema correcto.
    -> En username cambiar root por el usuario MySQL relacionado con el esquema y los permisos necesarios.
    -> En password poner la constraseña de ese usuario.
    -> En path poner la ruta absoluta hasta el directorio donde se encuentra la carpeta del proyecto y finalizar con src/assets.

Ejecutar en el proyecto:
    -> npm install -g @angular/cli
    -> npm install bootstrap jquery @popperjs/core

Usando "npm install" instalar:
    -> NgxPhotoEditorModule
    -> sweetalert2

## Ejecución

En la carpeta API-DWF_v1.0.5 ejecutar por línea de comandos "java -jar dwf-api-1.0.5.jar".

En la carpeta del proyecto escribir "ng serve -o".

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.1.

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
