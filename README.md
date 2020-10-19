# Curso de Programacion Javascript

### ¿Qué voy a aprender?

> Conocerás los fundamentos del lenguaje JavaScript, lo versátil que puede volverse tu web con esta poderosa herramienta y las múltiples utilidades de este lenguaje. Te explicaremos desde los puntos basic: definición de variables y operadores, así como la creación de funciones,la efectividad de los bucles o ciclos para la optimizacion del codigo, etc.Finalmente pondremos a prueba las habilidades aprendidas.

### Tabla de Contenido

| Nº  | Contenido                                                       |
| --- | --------------------------------------------------------------- |
| 1   | [¿Qué es javascript?](#qué-es-javascript)                       |
| 2   | [Ventana de diálogo](#comprender-la-ventana-de-diálogo-console) |
| 3   | [La función Console](#la-función-console)                       |
| 4   | [Operadores](#Operadores)                                       |

**[⬆ Back to Top](#tabla-de-contenido)**

### ¿Qué es Javascript?

Javascript es un lenguaje flexible orientado a objetos, basado en prototipos.
Permite la interactividad, implementa el comportamiento dinámico del contenido, lo cual nos lleva a tener una web mas eficiente. En conjunto con el HTML y CSS la interfaz de la web se vuelve mas atractiva y poderosa que permita al usuario navegar con gran facilidad.
Es un lenguaje interpretado no compilado.

ECMAScript 6 es el nuevo estándar de JavaScript correo en todas partes e incluye arrow function (funciones de flechas) =>, estas mismas nos permiten mapear a ciertas variables.

[Codigo Lamda en Vista ]

Entre su características deja de tener utilidad prototype y existen las clases como tal, (programación orientada a objetos).

[Class en Js]

La declaración de variables con let y const que nos permite un uso eficiente de memoria.

[let y const]

Ademas Unicode que incluye el uso de tildes y en su forma mas divertida emojis dentro del código.

[UNICODE]

Las librerías y Framework de Front End los mas populares son:

React.js, Vue.js, Angular.js
Mientras que para la capa de datos:
Redux, GraphQl, Apollo, etc.

Para el Back End tenemos:

Express.js,Next,js, Koa.js, etc.

El lenguaje que colabora mejor con javascript es Python.
Para crear aplicaciones nativas de escritorio y móviles como mas populares encontramos React Native y Electron.
El mundo de javascript es de los mas populares y esta creciendo impresionantemente, pero es indispensable conocer desde lo mas simple como tal te presentamos en curso de Javascript, sigue leyendo.

**[⬆ Back to Top](#tabla-de-contenido)**

### Comprender la ventana de diálogo (console)

En esta lección daremos a conocer la ventana de dialogo o consolé.
Necesario para comenzar: un navegador actualizado puede ser (Google Chrome, Mozilla Firefox, Safari, etc), en el cual se integran dos herramientas útiles:

**La Consola Web o ventana de Dialogo** : que nos presenta información de la estructura de la web actual identificando cada una de las funciones ejecutadas en tiempo real, ademas esta complementada con algunas lineas de código para ejecutar expresiones Javascript.
¿Como abrir esta seccion del navegador?
Por ejemplo en el navegador Mozilla firefox:

Configuraciones/Desarrollador Web/Consola Web.

![Mozilla1-1](https://user-images.githubusercontent.com/24228373/96376498-97b44c00-1155-11eb-97e3-55e352b6269b.png)

Para Google Chrome : Configuraciones (tres puntos parte superior derecha)/Más herramientas / Herramientas del desarrollador.

En la parte inferior del navegador mostrará:

![Chrome](https://user-images.githubusercontent.com/24228373/96376609-5cfee380-1156-11eb-9e06-49951a51f4d7.png)

Presionando en el teclado F12 y seleccionando la segunda opción “Console”.

Utilizado para ejecutar sencillas lineas de código ya que no se puede guardar.

Esta interfaz se divide en tres secciones que son:

Barra de herramientas: Barra principal definida por secciones que contienen herramientas para visualizar los componentes o ejecutar expresiones en lenguajes como JavaScript o Css. Otras opciones como el “Modo de diseño reactivo”, “Fijar al lateral de la ventana del navegador” o “Mostrar en una ventana separada”.
Linea de comando: Espacio inferior de la ventana de dialogo que permite al usuario escribir la expresiones JavaScript simples.
Panel de Mensaje :Ubicada en la parte central, comprende la mayor parte de esta ventana, se muestran errores, resultados de expresiones, alertas o información de la pagina actual.
\*Borrador: Utilizada para expresiones multilineas, la recomendación es utilizar la opción de “Borrador”, esta modalidad esta diseñada para crear bloques de código que definen una acción.

Ubicada al igual que la consola web:

Configuraciones/Desarrollador Web/Borrador

Se abrirá una ventana como la siguiente:

![Mozilla2](https://user-images.githubusercontent.com/24228373/96376638-93d4f980-1156-11eb-9615-0c55e5c94428.png)

Tiene las opciones de guardar en el mismo borrador o en un archivo externo para poder seguir trabajando mas tarde.

**[⬆ Back to Top](#tabla-de-contenido)**

### La función console

Todo el código JS que se implemente en una pagina web esta alojado dentro de un Objeto Global, este se encuentra en los navegadores de forma ordinario, de la misma forma las variables son definidas e insertadas dentro del objeto global.
Encapsular variables para asignarles nombre correctas. (Attr)

Llamadas a archivos del archivo javaScript

```javascript
<script src="funciones.js"></script>
```

En ocasiones se utiliza un alert para saber el valor de alguna variable

```javascript
alert("Hola mundo");
```

![alert-hola-mundo](https://user-images.githubusercontent.com/24228373/96388911-93eaee80-1182-11eb-8232-5a9bb794e3ec.jpg)

Pero hacer que el proceso de ejecución se detenga; Otras formas mas eficiente de visualizar dicho valor es utilizando las siguientes opciones:

```javascript
console.log(variable);
console.warn(variable); // Warning
console.error(variable); // Error simple sin dejar de ejecutar el codigo.
console.info(variable); // Informativo
```

![Tipos-Console](https://user-images.githubusercontent.com/24228373/96388942-cac10480-1182-11eb-89c3-61c822cc6678.jpg)

Es posible hacer operaciones entre variables utilizando estas funciones console.

**[⬆ Back to Top](#tabla-de-contenido)**

### Operadores

Los operadores son fundamentales para ver a las variables hacer que funcione el código ya que con ellos podemos comparar, asignar, realizar funciones matemáticas, etc.

Para JavaScript los usados en la sintaxis de son + – \* % = >< en expresiones sencilla o grupos de expresiones como lo son:

```javascript
var resultado = (8 + 9) / 10 - 3;
```

El orden en el que se resuelve dichas expresiones es según la jerarquía de operaciones.
Al hablar de comparadores en Javascript no referimos a >,<, >=, <=, ==, !=

![Operadores](https://user-images.githubusercontent.com/24228373/96389374-900c9b80-1185-11eb-8698-2fc94f5cc934.png)

La manera en la que Javascript interpreta el texto plano:
Las cadenas de texto se escriben entre comillas dobles.
Para hacer concatenaciones se escribe un signo de mas en cada una de las uniones:

![1](https://user-images.githubusercontent.com/24228373/96389384-a9154c80-1185-11eb-8946-586dcfb11b20.png)

Los operadores logicos determinan la logica entre 2 valores o expresiones, representados por || para “ó”, && para “y” y ! para “no en una expresion booleana”

![logicos](https://user-images.githubusercontent.com/24228373/96389393-bcc0b300-1185-11eb-8f4f-49c2a8505561.png)

Algunos caracteres necesitan diagonal invertida para reconocerse como funcion en Javascript:

![2](https://user-images.githubusercontent.com/24228373/96389408-d2ce7380-1185-11eb-9948-65be1c91fdcd.png)

```javascript
\t espacio
\n para saldo de linea
\\ para una diagonal (\)
```

Para comparar texto se utiliza los operadores : == ó !=
Se debe mencionar que es sencible a mayusculas y minusculas.

![4](https://user-images.githubusercontent.com/24228373/96389436-fee9f480-1185-11eb-936a-80d238eb3027.png)

Para saber la longitud de la(s) palabras utilizamos la propiedad .lenght
Los espacios en blanco también son contados

![5](https://user-images.githubusercontent.com/24228373/96389457-19bc6900-1186-11eb-866d-5a92d0716c4f.png)

**[⬆ Back to Top](#tabla-de-contenido)**

### Operadores lógicos

Los operadores lógicos sirven para escribir expresiones que den como resultado un dato booleano, es decir verdadero o falso. Se utilizan especialmente en estructuras condicionales y/o de repeticion.
En Javascript los operadores lógicos son:

- && corresponde a y (AND)
- || corresponde a o (OR)
- ! corresponde a no (NOT)

**Operador Lógico AND &&**
Este operador solo regresa true o verdadero cuando las dos variables son true, para las demás combinaciones se regresa false, ejemplo:

<html>
  <head>
    ```javascript
    <script>
      var a = false; 
      var b = true; 
      var c = true; 
      alert(a&&b);// resultado false
      alert(b&&c);// resultado true
    </script>
    ```
  </head>
</html>

**Operador Logico OR ||**
Se determina por un par de pipes, para este operador regresa true cuando uno de las variables es true, ejemplo:

```javascript
<html>
  <head>
    <script>
      var a = false; var b = true; var c = false; alert(a||b);// resultado true
      alert(b||c);// resultado false
    </script>
  </head>
</html>
```

**Operador lógico NOT !**
Este operador da como resultardo lo contrario a la variable, ejemplo:

```javascript
<html>
  <head>
    <script>
      var a = false; var b = true; alert(!b); // resultado false alert(!a);
      //resultado true
    </script>
  </head>
</html>
```
