# Angular Tutorial

## Requirement

1. `node` and `npm` should be installed with the latest version.
2. Visual Code Studio

## Installation & Project Creation

### Installing Angular:

```
npm install -g @angular/cli
```

If it installed correctly then run the command `ng version` and check for the version. It should give output something like this:

```
     _                      _                 ____ _     ___
    / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
   / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
  / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
 /_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
                |___/
    

Angular CLI: 16.2.5
Node: 18.16.1
Package Manager: npm 9.7.2
OS: win32 x64

Angular:
...

Package                      Version
------------------------------------------------------
@angular-devkit/architect    0.1602.5 (cli-only)
@angular-devkit/core         16.2.5 (cli-only)
@angular-devkit/schematics   16.2.5 (cli-only)
@schematics/angular          16.2.5 (cli-only)
```


### Project Creation

Let's start with a new project. Create a folder where you want to start angular project and write the command:

```
ng new ProjectName
```

For example:

```
ng new ToDoApp
```

It will ask you few question and based upon your requirement answer them. For our project we chose the below ones:

```
? Would you like to add Angular routing? Yes
? Which stylesheet format would you like to use? CSS
```

### Executing Project

To run your application:
```
ng serve --open
```
or
```
ng serve
```

### Production Build

```
ng build
```

## Understanding Angular Project

Once the project has been created, there will be certain folders and files which will be of importance for us: 
* `node_modules`: All the libraries are installed inside this folder.
* `src`: This folder consist of all the source code of the app. This would be the folder we would mostly be working with.
* The `app.component.ts` is the component that is added to the project by Angular CLI. You will find it under the folder `app/src`.
* The root module is called `app.module.ts`. (under `src/app` folder). This is the module which loads first.

