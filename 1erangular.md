## Prerequisites


Before you start, you need to install and configure the tools:

* [git](https://git-scm.com/)
* [Node.js and npm](https://nodejs.org/)
* [Angular CLI](https://angular.io/cli)
https://youtu.be/CgND0FEzmWI?si=oiqRNJEnTZU68PDp
* [Docker Engine](https://docs.docker.com/engine/install/)
* IDE (e.g. [Visual Studio Code](https://code.visualstudio.com/))
https://youtu.be/GsnhSTATwOU?si=GebBTXsrWoHtObls



## Getting started


### Create the Angular application


[Angular](https://angular.io/) is a development platform for building WEB, mobile and desktop applications using HTML, CSS and TypeScript (JavaScript). Currently, Angular is at version 17 and Google is the main maintainer of the project.

**1.** Let's create the application with the Angular base structure using the `@angular/cli` with the server-side rendering (SSR) disabled, the route file and the SCSS style format.

```powershell
ng new angular-docker --ssr false --routing true --style scss
CREATE angular-docker/README.md (1067 bytes)
CREATE angular-docker/.editorconfig (274 bytes)
CREATE angular-docker/.gitignore (548 bytes)
CREATE angular-docker/angular.json (2806 bytes)
CREATE angular-docker/package.json (1045 bytes)
CREATE angular-docker/tsconfig.json (903 bytes)
CREATE angular-docker/tsconfig.app.json (263 bytes)
CREATE angular-docker/tsconfig.spec.json (273 bytes)
CREATE angular-docker/.vscode/extensions.json (130 bytes)
CREATE angular-docker/.vscode/launch.json (470 bytes)
CREATE angular-docker/.vscode/tasks.json (938 bytes)
CREATE angular-docker/src/main.ts (250 bytes)
CREATE angular-docker/src/favicon.ico (15086 bytes)
CREATE angular-docker/src/index.html (299 bytes)
CREATE angular-docker/src/styles.scss (80 bytes)
CREATE angular-docker/src/app/app.component.scss (0 bytes)
CREATE angular-docker/src/app/app.component.html (20884 bytes)
CREATE angular-docker/src/app/app.component.spec.ts (940 bytes)
CREATE angular-docker/src/app/app.component.ts (373 bytes)
CREATE angular-docker/src/app/app.config.ts (227 bytes)
CREATE angular-docker/src/app/app.routes.ts (77 bytes)
CREATE angular-docker/src/assets/.gitkeep (0 bytes)
✔ Packages installed successfully.
    Successfully initialized git.
```

**2.** Now we will run the application with the command below.

```powershell
npm start

> angular-docker@0.0.0 start
> ng serve


Initial Chunk Files | Names         |  Raw Size
polyfills.js        | polyfills     |  82.71 kB | 
main.js             | main          |  23.23 kB | 
styles.css          | styles        |  96 bytes | 

                    | Initial Total | 106.03 kB

Application bundle generation complete. [1.504 seconds]
Watch mode enabled. Watching for file changes...
  ➜  Local:   http://localhost:4200/
```

**3.** Ready! Next, we will access the URL `http://localhost:4200/` and check if the application is working.

![YOUTUBE](https://youtu.be/K71m7H_P7XE?si=YSbn_2Wn4l_2GjUc)


