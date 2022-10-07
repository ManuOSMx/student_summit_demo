# Taller TypeScript

## Descripción

Vamos a realizar un juego muy sencillo en TypeScript, posteriormente lo vamos a desplegar en Microsoft Azure con Servicio de Azure Static Web Apps.

## Demostración
---

> Da click en la imagen para ver el vídeo

[![Demostración](https://img.youtube.com/vi/ROJFLILoJ9U/0.jpg)](https://www.youtube.com/embed/ROJFLILoJ9U)

Proyecto de ejemplo para el taller:
[Juego](https://ambitious-island-09903000f.2.azurestaticapps.net/)
## Instrucciones
--- 

### Instalación Git

Instalar Git en tu computadora, para ello puede seguir las instrucciones de la página oficial de Git: [Instalar Git](https://git-scm.com/)

### Clonar el repositorio

- Hacer fork del repositorio en tu cuenta de GitHub.
- Clonar el repositorio en tu computadora.
    - Copiar la URL del Repositorio.
- Abrir la terminal de tu computadora.
- Pegar la URL del repositorio en la terminal.
    ```bash 
    $ git clone https://url_del_repositorio
    ```
- Entrar a la carpeta del repositorio.
     ```bash 
     $ cd taller-typescript
    ```


### Instalacion NodeJS

Instalar NodeJS en tu computadora, para ello puede seguir las instrucciones de la página oficial de NodeJS: [Instalar NodeJS](https://nodejs.org/es/).

Comandos para replicar el proyecto:

- Instalamos las dependencias:
    ```bash 
     $ npm i -g typescript
    ```

- Iniciamos el proyecto en **TypeScript**: 
    ```bash 
     $ tsc --init
    ```

- Creamos el archivo **main.ts** y lo compilamos:
    ```bash 
     $ tsc --w main.ts
    ```

Una vez abierto la pagina, coloca tu nombre y da click en el boton. Despues presiona una flecha para iniciar el juego. :)

### Azure Static Web Apps

Una vez que tengamos el proyecto funcionando, subiremos la aplicación a **Azure Static Web Apps**.

- Instalar la extension de Azure Static Web Apps en Visual Studio Code.
- Haremos commit de los cambios
- En la parte izquierda, en la sección de Azure, aparecerá un icono de Azure static Web Apps.
- Dar click en el icono y seleccionar la opcion de **Create New Static Web App**.
- Seguir las instrucciones del [vídeo](#demostración).

## Recursos
---
- Microsoft TypeScript: [https://www.typescriptlang.org/](https://www.typescriptlang.org/)
- Microsoft Learn: [https://learn.microsoft.com/es-mx/training/modules/typescript-get-started/](https://learn.microsoft.com/es-mx/training/modules/typescript-get-started/)
- TypeScript Playground: [https://www.typescriptlang.org/play](https://www.typescriptlang.org/play)