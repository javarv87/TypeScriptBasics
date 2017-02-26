# TypeScript Fundamentos y Ejemplos Básicos

![alt text](https://github.com/javarv87/typeScriptExamples/raw/master/common/images/typescript.jpg "Logo TypeScript")

## TypeScript

**TypeScript** es un lenguaje de programación libre y de código abierto desarrollado por **Microsoft**. Es un superconjunto de **JavaScript**, que esencialmente añade tipado estático y objetos basados en clases.

> **Anders Hejlsberg**, diseñador de **C#**, ha trabajado en el desarrollo de **TypeScript**.

**TypeScript** extiende la sintaxis de **JavaScript**, por tanto cualquier código JavaScript existente debería funcionar sin problemas. Está pensado para grandes proyectos, los cuales a través de un compilador de TypeScript se traduce a código JavaScript original. Permite además trabajar sin problemas con famosas librerías de JavaScript como **jQuery**, **MongoDB**, **Node.js**, y **D3.js**, **Angular** por ejemplo esta realizado con **TypeScript**.

Tiene una sintaxis intuitiva, los navegadores no convertirán **TypeScript** a **Javascript** si no que TypeScript cuenta con un ***Transpiler*** que convierte el código **TS** a **JS** y puedes elegir si usar ***ES5*** ó ***ES6***

## Instalación

Para instalar TypeScript necesitaremos tener instalado previamente **Node.js** y **npm**, si no es el caso puedes revisar el tutorial [Cómo instalar nodejs y npm en mac](https://medium.com/javascript-comunidad/cómo-instalar-node-js-y-npm-en-mac-9d80f26fb88d#.zcpt051n2) y continuar con la instalación de TypeScript.

Necesitaremos ingresar en nuestra terminal el siguiente comando.

**`npm install -g typescript`**

Con esto estaremos listos para usar **TypeScript**, crea un archivo con extensión ***.ts***

## Datos básicos de TypeScript

### Variables

En **TypeScript** las variables se declaran igual que en Javascript, pero se especifica que tipo de dato es, por ejemplo:

```javascript
  // Tipo de dato string
  var name:string = 'Tu nombre';
  
  // Tipo de dato number
  var age:number = 29;
  
  // Tipo de dato boolean
  var havePets:boolean = true;
```

Las **variables** tienen la palabra reservada ***"var"*** pero el tipo de dato que se va a utilizar ó estará asignado a la variable se denota con ***"nombreVariable:tipoDato"***, a estos tipos de dato se les denomina **datos primitivos**, y son:
* string
* number
* boolean