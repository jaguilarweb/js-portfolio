# js-portfolio

## Introducción

Este proyecto es un ejercicio que se realiza en el marco del curso de webpack de Platzi, adquiriendo práctica y experiencia en el manejo de esta herramienta.

Este proyecto explora diferentes configuraciones para crear el ambiente de desarrollo y de producción, con diferentes herramientas como loaders y plugins, que facilitan el desarrollo de aplicaciones.

## Webpack

En lo principal, webpack es un empaquetador de módulos estáticos para aplicaciones modernas en JavaScript. Cuando webpack procesa la aplicación, internamente construye un gráfico de dependencias lo que mapea cada módulo que necesita el proyecto y genera uno o más paquetes.


## Nodejs y NPM

Para este proyecto se requiere tener instalado Nodejs.
Para MacOS instalar primero homebrew: 

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)
`

Luego instalar Nodejs:

`
$ brew install node
`

Instalación de webpack en la carpeta raíz del proyecto.

`
$ npm install webpack webpack-cli -D
`

Los principales loaders y plugins que se instalan en este proyecto son los siguientes:

`
npm install -D babel-loader @babel/core @babel/preset-env @babel/plugin-transform-runtime -D

npm i html-webpack-plugin -D

npm i mini-css-extract-plugin css-loader -D

npm i stylus stylus-loader -D

npm i copy-webpack-plugin -D

npm i url-loader file-loader -D

npm i css-minimizer-webpack-plugin terser-webpack-plugin -D

npm i -D dotenv-webpack

npm install -D clean-webpack-plugin

npm install webpack-dev-server -D

npm install -D webpack-bundle-analyzer

`

## Acceso a la aplicación de ejemplo.

Esta aplicación ha sido desplegada en la plataforma Netflif.

https://js-portfolio-jaguilarweb.netlify.app/


## Autors

Esta aplicación fue creada por el profesor Oscar Barajas y la adaptación y documentación por Jenny Aguilar.

