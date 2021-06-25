# Webpack

## ¿Que es?

Es una herramiento para preparar en código para productivo, nos permite trabajar con casi todo tipo de archivos. Además de trabajar en un apartado dev.

Se pueden gestionar dependencias, css, habilitar un entorno dev para pruebas, entre otros. Es una filosofia modular. prepara todo nuestro desarrollo en un paquete, haciendo uso de pligins y demás.

Paquete de módulos, mapea cada modulo para generar más.
trabaja con un punto de salida, carpeta dist, que se ecnuentran los elementos preparados por webpack, modos de desarrollo y productivo serán posibles. dispone de louder y pligins. Lo splugins extiende los elementos y sus funcionalidades. 

## Configuración

Inicializamos con `git init` y adicional iniciamos un proyecto con `npm init -y`para la configuración rápida.

Creamos la carpeta src para tener nuestros archivos core. y creamos el index.js.

Instalmos webpack con el comando `npm install webpack webpack-cli -D`, instalado el paquete de webpack y cli para tener comandos desde terminal y -D para agregarlo a una dependencia de desarrollo.

Ejecutamos `npx webpack`para validar nuestro archivo de origen y nuestro proyecto. Nos arroja unos ***WARNING** que nos quieren dar a entender que debemos setear un modo 'development' o 'production'.

Si revisamos lo creado en el proyecto nos dmos cuenta que creó la carpeta dist, con un archivo main y que en su interior tiene el código pero optimizado.

Luego, para ejecutar webpack en su modo dev colocamos `npx webpack --mode development`. Esto activa una vista en el archivo que facilita el debbuggin del proyecto.

Si ejecutamos `npx webpack --mode production`. el código resultante será el optimizado y listo para productivo.