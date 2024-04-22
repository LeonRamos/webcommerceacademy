## Prerequisites


Before you start, you need to install and configure the tools:

* [git](https://git-scm.com/)
* [Node.js and npm](https://nodejs.org/)
* [Angular CLI](https://angular.io/cli)
* [Docker Engine](https://docs.docker.com/engine/install/)
* IDE (e.g. [Visual Studio Code](https://code.visualstudio.com/))
  

## COMIENZO


### CREANDO UNA APLICACION EN ANGULAR


[Angular](https://angular.io/) Angular es una plataforma de desarrollo para construir aplicaciones web, móviles y de escritorio utilizando HTML, CSS y TypeScript (JavaScript). Actualmente, Angular se encuentra en la versión 17 y Google es el principal mantenedor del proyecto.

**1.** Creemos la aplicación con la estructura base de Angular utilizando @angular/cli, con la representación del lado del servidor (SSR) deshabilitada, el archivo de rutas y el formato de estilo SCSS.

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

**2.** Ahora ejecutaremos la aplicación con el siguiente comando

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

**3.** A continuación, accederemos a la URL DEL LOCALHOST y comprobaremos si la aplicación está funcionando.

**4.** Instalación [![YouTube](https://img.shields.io/badge/YouTube_Music-FF0000?style=for-the-badge&logo=youtube-music&logoColor=white)](https://youtu.be/CgND0FEzmWI?si=oiqRNJEnTZU68PDp)
**5.**[![YouTube](https://img.shields.io/badge/YouTube_Music-FF0000?style=for-the-badge&logo=youtube-music&logoColor=white)](https://youtu.be/GsnhSTATwOU?si=GebBTXsrWoHtObls)
**6.**[![YouTube](https://img.shields.io/badge/YouTube_Music-FF0000?style=for-the-badge&logo=youtube-music&logoColor=white)](https://youtu.be/K71m7H_P7XE?si=YSbn_2Wn4l_2GjUc)


