# PROVEEDORES
## Ejercicio técnico de la empresa proveedores
Automatizar un proceso que realice una búsqueda en la web de la Generalitat de Catalunya

### Pasos a automatizar
* Ir a la web de la Generalitat de Catalunya
https://web.gencat.cat/ca/inici
* Buscar “agenda cultural”
* Click en botón de buscar

### ¿Cómo realizar la tarea?
* Crear un proyecto en github compartido con el usuario jgalobart y usar git como control de versiones.
* Utilizar la librería Playwright, que funciona sobre NodeJS
https://playwright.dev/docs/intro
* Emular en Chromium, sin la opción headless y con la opción slow motion a 50.
chromium.launch({ headless: false, slowMo: 50 });
* Automatizar los pasos descritos anteriormente.

## Instalación 
_Para instalar las dependencias de Playwright utilizar el comando_

```
npm install
```

## Ejecución 
_Para ejecutar el proyecto utilizar el comando:_

```
node index.js
```


