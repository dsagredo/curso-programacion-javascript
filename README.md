# Curso de Programacion Javascript

### ¿Qué voy a aprender?

> Conocerás los fundamentos del lenguaje JavaScript, lo versátil que puede volverse tu web con esta poderosa herramienta y las múltiples utilidades de este lenguaje. Te explicaremos desde los puntos basic: definición de variables y operadores, así como la creación de funciones,la efectividad de los bucles o ciclos para la optimizacion del codigo, etc.Finalmente pondremos a prueba las habilidades aprendidas.

### Tabla de Contenido

| Nº  | Contenido                                                       |
| --- | --------------------------------------------------------------- |
| 1   | [¿Qué es javascript?](#qué-es-javascript)                       |
| 2   | [Ventana de diálogo](#comprender-la-ventana-de-diálogo-console) |
| 3   | [La función Console](#la-función-console)                       |

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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
