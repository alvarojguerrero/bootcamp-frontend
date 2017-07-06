# Bootcamp-Frontend
## *Notas de Clase*

Definiciones

1. _Frontend: Tecnologias de diseño y desarrollo web que corren en el navegador, ejemplos: HTML, JavaScript, CSS_

1. _Backend:Teecnologias que corren al lado del servidor como: PHP, JAVA, Python, Ruby_

------

### [*Webtask*](https://webtask.io/)

Webtask funciona como una plataforma para construir aplicaciones web sin tener que preocuparse por la cuestion de los servidores.

WebTas.io te permite construir aplicaciones sin tener que pensar en enteramente en su estructura, simplemente escribir la logica del cliente-servidor, desarrollando todas las funciones a traves de Webtask CLI (_Command Line Interface_) y acceder a al backend sin servidor a traves de HTTP.

#### Webtask CLI
Lo unico por lo que hay que preocuparse es por el codigo. Con la herramienta de linea de comandos para Webtask se puede crear microservicios en segundos.

#### Instalacion
En la terminal escribir:

```bash
$ npm i -g wt-cli

$ wt init
```
### Primera Aproximacion

Creando el primer codigo

```javascript
module.exports = function (cb) {
  cb (null, "Hello World")
}
```
------

### __Comandos Terminal__
#### ls -l
list dir contents long format

#### ls -a
list dir contents including hidden

#### .carpeta
oculta(ex: carpetas, archivos)

#### mkdir nombre
crear carpeta

#### rm -r dir
remove dir

#### rm -rf *

#### cp -r dir1 dir2
copiar (dir) y se va a llamar (dir2)

#### cd -
devolver al anterior directorio

#### mv file1 file2
renombrar un archivo

#### touch.extension
crear archivo

#### more file
mirar archivo

------
## Git
![alt text](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)

Es un sistema de *__control de versiones distribuido__* para dar seguimiento a los archivos para poder manipular eficientemente los cambios guardados, mas aun cuando se trabaja en proyectos coordinados con diferentes personas.

#### Instalacion de Git
Git viene instalado usualmente por defecto en Linux y Mac, para comprobarlo se puede utilizar el comando __ git --version __
Es un sistema de *__control de versiones distribuido__*

##### Comandos Basicos de Git
```bash
 $ git init
  #inicar carpeta con version de controles
```
```bash
$ git status
```

```bash
$ git add archivo
  #subir al stage
```

```bash
$ git commit -m "comentario para reconocer el archivo"
  #subir a history
```
  ```bash
$ git master
```
```bash
$ git add -A .
  #para agregar todo
```
---
### SSH Key

Git utiliza una autenticacion a través de una clave pública y otra privada. Al usar una llave SSH se puede acceder facilmente al servidor sin tener que ingresar un **password** cada vez.

Si ya se tiene una clave SSH, ésta se guardara por defecto en la carpeta `~/.ssh`, en la cual debera existir por defecto dos archivos llamados: `id_rsa`(clave privada) y `id_rsa.pub`(clave publica).
De no tener estos archivos se utilizara el `ssh-keygen`, ingresando en la terminal:
> ssh-keygen -t rsa -b 4096 -C ("Nuestro Email")

## GitHub ![alt text](https://octicons.github.com/img/og/mark-github.png)
Es una plataforma web que utiliza el sistema de control de versiones Git para crear repositorios de proyectos o alojarlos en principio.
***
## Sintaxis basica Markdown
***
# H1
## H2
### H3
#### H4
##### H5
###### H6

_Enfasis italica_

__Enfasis fuerte__, **otra manera**

**_Enfasis fuerte italica_**

> ## Listas
1. Un item
1. segundo item
1. tercer item

> ## Listas sin orden
* un intem
* otro item ...
+ otros items


*********************************
## Notas aun por organizar

search engine optimization = buenas busquedas


etiqueta <br/> es un salto de linea
<p> es un elemento de bloque
<hr> pinta una linea

Anchors
<a href=""> nombre </a>

Link Absoluto
schema+dominio+path

url amigables

montar imagenes <img src="" , alt="" , width="" (estos son atributos)

<video
buscar i18n

HTML Entities

caracteres especiales

pluggin picments

CSS Floats


JavaScript

libros
you don't know JavaScript
Up and going


notacion polaca inversa
 lenguajes skim lisp

 var age=prompt("Cual es tu edad")
Number
Boolean
String

Operadores de asignacion directa
+= *= /=

age= "26"
string literal `
`Yo tengo ${age} años

age= +age (lo convierte a number igual que Number())

++age (incrementa directamente)
age++ (incrementa cuando ya se lo vuelve a llamar)



Un bloque es definido por llaver, ejemplo las funciones

if tripartito


Funciones para poner en documento

var
function imprimirBalance(Balance){
 //Imprimir balance
}
function retirarDinero(dinero){

//Solo puede retirar dinero si es menor que el balance
}
function transferir(balance, balance2){
//Transferir balance a otro balance2
}
function imprimirBalance2 (balance2){
//Imprimir el balance2
}
function RetirarTodoMiDinero(){
/* Retirar de 100 en 100*/
}

console.assert(suma(2,5)==7)
