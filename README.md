# Curso de Programacion Javascript

### ¿Qué voy a aprender?

> Conocerás los fundamentos del lenguaje JavaScript, lo versátil que puede volverse tu web con esta poderosa herramienta y las múltiples utilidades de este lenguaje. Te explicaremos desde los puntos basic: definición de variables y operadores, así como la creación de funciones, la efectividad de los bucles o ciclos para la optimizacion del codigo, etc. Finalmente pondremos a prueba las habilidades aprendidas.

### Tabla de Contenido

| Nº  | Contenido                                                       |
| --- | --------------------------------------------------------------- |
| 1   | [¿Qué es javascript?](#qué-es-javascript)                       |
| 2   | [Ventana de diálogo](#comprender-la-ventana-de-diálogo-console) |
| 3   | [La función console](#la-función-console)                       |
| 4   | [Operadores](#operadores)                                       |
| 5   | [Operadores Lógicos](#operadores-lógicos)                       |
| 6   | [Operadores Aritméticos](#operadores-aritméticos)               |
| 7   | [Operadores de Asignación](#operadores-de-asignación)           |
| 8   | [Operadores de Cadena](#operadores-de-cadena)                   |
| 9   | [Operadores de Comparación](#operadores-de-comparación)         |
| 10  | [Variables](#variables)                                         |
| 11  | [Escritura Dinámica](#escritura-dinámica)                       |
| 12  | [Valor y Referencia](#valor-y-referencia)                       |
| 13  | [Creacion de funciones](#creacion-de-funciones)                 |

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

```html
<html>
  <head>
    <script>
      var a = false;
      var b = true;
      var c = true;
      alert(a && b); // resultado false
      alert(b && c); // resultado true
    </script>
  </head>
</html>
```

**Operador Logico OR ||**
Se determina por un par de pipes, para este operador regresa true cuando uno de las variables es true, ejemplo:

```html
<html>
  <head>
    <script>
      var a = false;
      var b = true;
      var c = false;
      alert(a || b); // resultado true
      alert(b || c); // resultado false
    </script>
  </head>
</html>
```

**Operador lógico NOT !**
Este operador da como resultardo lo contrario a la variable, ejemplo:

```html
<html>
  <head>
    <script>
      var a = false;
      var b = true;
      alert(!b); // resultado false
      alert(!a); //resultado true
    </script>
  </head>
</html>
```

**[⬆ Back to Top](#tabla-de-contenido)**

### Operadores aritméticos

Son aquellos con los que podemos manipular datos numéricos, por ejemplo suma, resta, multiplicación división. Los operadores para cada uno son:

- Suma +
- Resta –
- Multiplicación x
- Potencia
- División para obtener el cociente /
- División para obtener el restante %
- División para obtener la parte entera no es posible en Javascript

Ejemplos:

```html
<html>
  <head>
    <script>
      var a = 10;
      var b = 2;
      var c = 5;
      alert(a + b + c); // resultado 17
      alert(a - c); // resultado 5
      alert(a / c); // resultado 2
      alert(a * c * b); // resultado 100
      alert(15 / 2); // resultado 7.5
      alert(a ** c); // resultado 100
      alert(a % c); // resultado 0
    </script>
  </head>
</html>
```

**[⬆ Back to Top](#tabla-de-contenido)**

### Operadores de asignación

Los operadores de asignación

- Operador +=
- Operador -=
- Operador \*=
- Operador /=
- Operador %=
- Operador ==

Los operadores de asignación son los mas simples y mas utilizados ya que su función es apuntar un valor a una variable o guardarlo en la misma.

```html
<html>
  <head>
    <script>
      var a = 10;
      var b = 2;
      var c = 5;
      var d = 3;
      var e = 100;
      c += a;
      alert(c); // resultado 15
      b -= a;
      alert(b); // resultado -8
      a -= b;
      alert(a); // resultado 18
      c /= d;
      alert(c); // resultado 5
      d *= a;
      alert(a); // resultado 54
      e = a;
      alert(e); // resultado 54
      e %= c;
      alert(e); // resultado 4
    </script>
  </head>
</html>
```

**[⬆ Back to Top](#tabla-de-contenido)**

### Operadores de cadena

Los operadores de cadena sirven para concatenar cadenas u objetos.
Las variables de cadena se pueden asignar comillas simples ' o dobles de forma indistinta.

```html
<html>
  <head>
    <script>
      var PrimerNombre = "Luis";
      var segundoNombre = "Antonio";
      var Apellido = "Lara";
      var Nombre = PrimerNombre + SegundoNombre + Apellido;
      alert(Nombre);
    </script>
  </head>
</html>
```

El resultado es la unión de las tres cadenas pero veamos que no se separa entre cada unas de ellas, para eso necesitamos agregar lo siguiente:

```html
<html>
  <head>
    <script>
      var PrimerNombre = "Luis";
      var segundoNombre = "Antonio";
      var Apellido = "Lara";
      var Nombre = PrimerNombre + " " + SegundoNombre + " " + Apellido;
      alert(Nombre);
    </script>
  </head>
</html>
```

Como sucede con los operadores de asignación podemos utilizar:

```html
<html>
  <head>
    <script>
      var PrimerNombre = "Luis";
      var SegundoNombre = "Antonio";
      var Apellido = "Lara";
      var Nombre = "";
      Nombre += PrimerNombre;
      Nombre += " ";
      Nombre += SegundoNombre;
      Nombre += " ";
      Nombre += Apellido;
      alert(Nombre); //Luis Antonio Lara
    </script>
  </head>
</html>
```

Tengamos en cuenta que las variables pueden ser de cualquier tipo ya que en Javascript con especificar var al principio es suficiente.
Veamos un ejemplo donde el operador + funciona no solo para sumar si no también para concatenar cadenas :

```html
<html>
  <head>
    <script>
      var Nombre = "Luis Antonio Lara";
      alert(10 + 28 + " " + Nombre);
    </script>
  </head>
</html>
```

**[⬆ Back to Top](#tabla-de-contenido)**

### Operadores de comparación

Los operadores de comparación o relacionales son para relacionar, comprobar o cumplir alguna condición. El resultado de estos operadores siempre es una valor booleano

- == Igual a
- === Igual valor a tipo
- != Diferente
- !== Diferente tipo, diferente valor
- '> Mayor que'
- '< Menor que'
- '>= Mayor igual que'
- '<= Menos igual que'
- ? Ternario

```html
<html>
  <head>
    <script>
      var a, b, c, d, e, f;
      a = 2;
      b = 3;
      c = 5;
      d = 15;
      e = "Hola";
      f = "Adios";
      alert(a > c); //false
      alert(b < d); //true
      alert(d == c); //false
      alert(b > c); //false
      alert(e != f); //true
      alert(a != f ? "Si" : "No"); //Si
    </script>
  </head>
</html>
```

**[⬆ Back to Top](#tabla-de-contenido)**

### Variables

En JavaScript todas las Variables son elementos utilizados para asignar valores o hacer referencia con otros valor. Se definen de la misma forma: con la palabra reservada “var” ya sea para asignar cadenas de texto o números, es igual en cualquier caso.

**Numérico**: utilizado para asignar valores enteros, decimales o flotantes;

```javascript
var Numero = 1.298;
var Total = 334.78;
```

Texto: para almacenar cadenas o palabras, la sintaxis correcta para asignarlo es escribir el texto entre comillas simples o dobles.

```javascript
var PrimerMes = "Enero";
var Saludo = "Buenos dias, un gusto verlos";
var Letra = "r";
```

Booleanos: almacena solo 2 valores “true” o “false”:}

```javascript
var Respuesta = false;
```

Arrays: Son considerados vectores o matrices que almacenan una serie de valores o cadenas de texto y/o numeros:

```javascript
var nombre_array = [dato1, dato2,dato3......, datoN];
var Meses = ["Enero","Febrero","Marzo","Abril".........,"Diciembre"];
```

Para hacer referencia a cada una de las valores del array se utiliza:

```javascript
var CuartoMes = Meses[3];
var segundoMes = Meses[1];
```

El conteo de las posiciones en el array comienza con cero.

DELETE: elimina una propiedad de un objeto:

```javascript
var DiasSemana = {PrimerDia:"Lunes",SegundoDia:"Martes",TercerDia:"Miercoles"....., SeptimoDia:"Domingo"}
delete DiasSemana.SegundoDia;
```

IN: Devuelve un valor booleano para cada caso donde se cumpla o no lo especificado:

```javascript
var colores = new Array("Rojo", "Azul", "Verde", "Amarillo", "Blanco");
0 in colores;
true;
3 in colores;
true;
6 in colores;
false;
"Morado" in colores;
false;
```

Otras predefinidas son:

```javascript
"PI" in Math;
true;
NaN in Number;
true;
length in String;
false;
```

**[⬆ Back to Top](#tabla-de-contenido)**

### Escritura dinámica

Para comprender mejor la escritura dinámica se debe aclarar que existen 2 tipos de datos:
Primitivos y objetos

**\*Primitivos**: un tipo de datos que apunta a un solo valor, estos a su vez se clasifican en
5 tipos:

- Strings (Cadenas de texto)

```javascript
var z = "Hola mundo";
```

- Booleano (True, False)

```javascript
var Opcion = false;
```

- Undefined (Contiene undefined)

```javascript
var Instruccion;
Instruccion;
undefined;
```

- Null (Contiene null)

```javascript
var variableNula = null;
variableNula;
null;
```

- Number (Valores numéricos)

```javascript
var intervalo = 8;
```

Algo que tenemos en consideración las variables no están asignadas a un tipo de dato especifico podemos asignar un valor numérico en uno que anteriormente tenia asignado un dato booleano.

```javascript
var a = "Hola mundo";
a = false;
a = 1245;
```

**\*Objeto**: Colección de tipos de datos primitivos u otros objetos.
Dentro de los objetos esta dentro de algo llamado nomenclatura de pares
Cada una de las propiedades tiene que tener un par.

Comprende 3 Tipos:

- Tipos predefinidos de JavaScript

Date (Contiene fecha)
Constructor: new Date(año_num,mes_num,dia_num [,hor_num,min_num,seg_num,mils_num])

```javascript
var cumpleanos = new Date("April 11, 1990 14:20:00");
cumpleanos
Wed Apr 11 1990 14:20:00 GMT-0500 (Hora de verano central (México))
```

Error (Mensaje de error)

```javascript
var ErrorLiteral = new Error("Error al ejecutar el código");
ErrorLiteral
Error: Error al ejecutar el código
    at <anonymous>:1:20
```

- Arrays

```javascript
Serie de elementos o formación de tipo vector o matriz
Constructor: new Array(longitudDelArray) new Array(elemento0, elemento1, …, elementoN)

var DiasSemana = ['Lunes', 'Marte', 'Miercoles', 'Jueves', 'Viernes', 'Sabado', 'Domingo'];
DiasSemana
(7) ["Lunes", "Marte", "Miercoles", "Jueves", "Viernes", "Sabado", "Domingo"]
DiasSemana.length;
7
DiasSemana[0]
"Lunes"
DiasSemana[4]
"Viernes"
DiasSemana.forEach(function (elemento, indice, array) {
    console.log(elemento, indice);
});
VM3284:2 Lunes 0
VM3284:2 Marte 1
VM3284:2 Miercoles 2
VM3284:2 Jueves 3
VM3284:2 Viernes 4
VM3284:2 Sabado 5
VM3284:2 Domingo 6
undefined
DiasSemana.push('Lunes2')
8
DiasSemana
(8) ["Lunes", "Marte", "Miercoles", "Jueves", "Viernes", "Sabado", "Domingo", "Lunes2"]
DiasSemana.pop();
"Lunes2"
DiasSemana
(7) ["Lunes", "Marte", "Miercoles", "Jueves", "Viernes", "Sabado", "Domingo"]
```

Cabe mencionar que existen otros tipos llamados especiales que esta construidos por el usuario o que comprenden una función compuesta. En la lección de funciones hablaremos sobre este tema.

**[⬆ Back to Top](#tabla-de-contenido)**

### Valor y Referencia

Las variables de tipo primitivos siempre se pasan por valor, es decir ambos tienen su propio espacio en memoria.
Para cada una de las variables declaradas se crea un espacio en memoria y guarda el valor para cada una de ellas, así que si se asigna un valor diferente después de igualar a otra variable conserva el valor que inicialmente se le asigna.

```javascript
var x = 35;
var y = x;

console.log(x);
console.log(y);

x = 55;

console.log(x);
console.log(y);
```

Con los objetos siempre se pasan por referencia, es decir se declara un objeto con cada una de sus propiedades y se queda en un espacio de memoria, si se igualan dos objetos, en realidad es el mismo espacio de memoria solo apuntado desde dos objetos, por lo tanto si se asigna un valor distinto a una propiedad del objeto cuando hacemos referencia al mismo tendrá el valor referenciado las veces que se llame.

```javascript
var a = {
  nombre: "Karen",
};

var b = a;

console.log(a);
console.log(b);

c.nombre = "Eduardo";

console.log(a);
console.log(b);

c.nombre = "Ana";

console.log(a);
console.log(b);
```

Con esto podemos diferencia entre asignar por valor o por referencia segun el espacio de memoria asignado o apuntado.

**[⬆ Back to Top](#tabla-de-contenido)**

### Creacion de Funciones

Las funciones son fragmentos de código que definen una o varias acciones (se hace llamar código modular), que puede usarse tantas veces como sea necesario, usado así para optimizar el código y evitar repetirlo.

La estructura iniciara con la palabra reservada _function_ seguida del _nombre_, entre paréntesis los _paramentos_, o bien sin parámetros, entre llaves el _bloque de instrucciones_ que cumplirá.

Función con parámetros:

```javascript
function NombreDeLaFuncion (parametros1, paremetro2, ..... parametro n)
{
   Bloque;
   De;
   Instrucciones;
}
```

Para invocar la función, basta con escribir el nombre que se le asigno, recuerda que tiene que ser sintacticamente igual.

```javascript
NombreDeLaFuncion(a,b,.....n);
```

Las funciones y procedimientos son iguales, en otros lenguajes de programación se cuenta con un palabra reservada antes del nombre, por ejemplo en otros lenguajes podría llevar, void, public, private, en el caso de Javascript solo existe un tipo de instrucción y es la _function_.

Todas las funciones de Javascript regresan un valor, por ejemplo:

```javascript
function FuncionDePrueba() {}
var valor = FuncionDePrueba();
console.log(valor);
```

El valor que regresara es :

```javascript
undefined;
```

Es importante mencionar que lleve o no parametros siempre para reconocerla como una fucion al ser invocada debe de escribirse un par de parentesis.

Veamos un ejemplo:

```javascript
function FuncionDePrueba() {
  console.log("Dentro de la funcion");
}

var ValorResultante = FuncionDePrueba;
```

Como ya lo mencionamos todo regresa un valor, incluso puede regresar la definición de una función, en este caso retorna un objeto que es una función.

```javascript
>FuncionDePrueba
<-function FuncionDePrueba() {
  console.log("Dentro de la funcion");
}

>FuncionDePrueba();
<-Dentro de la funcion
```

**[⬆ Back to Top](#tabla-de-contenido)**

### Estructura de condicionales

Es importante recordar que la ejecución de código en JS es lineal, es decir linea a linea en el orden en el que se lee.

Para controlar este flujo se utilizan:

- Ciclos o bucles,
- Condicionales,
- Palabras reservadas para romper el flujo
- De control de excepciones.
- En este caso explicaremos las condicionales.

Las condicionales son palabras reservadas que te ayudan a crear un ambiente para que el código tenga un flujo mas especifico y eficiente, la mas básica es el if, la estructura es la siguiente:

```javascript
if (Condicion) {
  //Bloque de codigo
}
```

Es importante especificar que si para la condición solo se ejecutara una instrucción se pueden omitir las {}, aunque no significa que no se pueda llevar aun si es solo una. Si es un bloque de instrucciones si debe de llevar.

**_If_** en ocasiones esta acompañado con la **_else_**, ejemplo:

```javascript
if (Condicion) {
  //Bloque de codigo que cumple la condicion
} else {
  //Bloque de codigo que no cumple con la condicion
}
```

Pero tengamos en cuenta que **_if_** y **_else_** representan 2 opciones de ejecución, pero que sucede si se requieren mas condiciones. Otras complemento opcional de if es **_else-if_**, ejemplo:

```javascript
if (Validacion.includes("1 -"))
  direct = "/system?D=5PCuXo4GT2pkgfji1q1se47SnQu8QxM/JRPN";
else if (Validacion.includes("2 -"))
  direct = "/system?D=5PCuXo4Gr8r9T2pkgfji1q7SndjE1RkWiiZv";
else if (Validacion.includes("3 -"))
  direct = "/system?D=FVqQLVdRAMf5r72s0kpWzWkSrOJQ==";
else if (Validacion.includes("4 -"))
  direct = "/system?D=FVqQLVdRAM3gert58a2fUZNMS1DKA=58=";
else direct = "/system?D=a";
```

Explicando el ejemplo anterior, podemos decir que la estructura de if, incialmente es la

```javascript
if (Condicion)// Si Condicion se cumple
{
   //Bloque de código
}
else if (Condicion2) //Si Condicion no se cumple, se revisa si Condicion2 se cumple
{
   //Bloque de código
}
else if (Condicion3) //Si Condicion y Condicion2 no se cumple, se revisa si Condicion3 se cumple
{
   //Bloque de código
}
.
.
.
.
else //No se cumple ninguna de las anteriores
{
   //Bloque de código
}
```

**_Condiciones_**

La sección de la condición es fundamental, para esto hacemos énfasis que se pueden utilizar e interpretar lo que decimos con palabras en una linea de código.

Dato booleano: es decir datos que solo contienen los valores **_true_** o **_false_** para utilizarlo en condicion es:

```javascript
// Si se comprueba que el usuario se autentico muestra una lista de clientes si no devuelve error
function Revisar(Autenticacion) {
  if (Autenticacion) {
    //true
    ListadoCliente();
  } //false
  else {
    console.log("No se puede Listar");
  }
}
```

Dato Numérico/Texto:

Igual: == ó .equals()
Menos que: <
Menos o igual que: <=
Mayor que: >
Mayor o igual que: >=
Distinto: !=

```javascript
if (Dia == "Lunes") {//Bloque de codigo}
  else if (Dia != "Viernes") {//Bloque de codigo}
  //--------------------------------------
  if (Conteo < 10) {//Bloque de codigo}
  esle if (Conteo <= 30) {//Bloque de codigo}
  else if(Conteo > 100) {//Bloque de codigo}
  else if(Conteo >= 50) {//Bloque de codigo}
```

Disyunción ó: ||
Conjunción y: &&

También se utilizan para agregar varias partes una condición y así ser mas específicos para cada acción de código.

```javascript
if (Dia == "01" && Mes == "Enero") {
  console.log("Feliz año nuevo");
}
```

```javascript
if ((Dia == "24" || Dia == "23") && Mes == "Diciembre") {
  console.log("Se acerca la Navidad");
}
```

Las condicionales son una forma de organizar la funcionalidad del código, para que según los casos de uso, pueda funcionar y responder de una manera mas eficiente y ordenada.

Utilizando la lógica y según el tipo de dato con el que interactuemos podamos construir condiciones para cada una de las situaciones.

**[⬆ Back to Top](#tabla-de-contenido)**

### Estructura de ciclos

Un ciclo es una instrucción muy útil si sabemos como utilizarla y estructurarla, ya que nos permite ejecutar funciones varias veces; Si bien estos ciclos o también llamados bucles son utilizados para determinar de una forma dinámica en lugar de agregar la función n numero de veces.

Comencemos con el ciclo **_For_**, su estructura es

```javascript
for (
Se inicializar variable que sera el contador, solo pasa por aqui al iniciar el ciclo var a =0;
Se determina el numero de veces que se ejecutara el bloque de código a < 10;
Se ejecutara cada vez  que termine el bloque de código (por lo regular se utiliza para aumentar o disminuir segun lo que se quiera hacer con el contador del cliclo a++)
)
{
   //Bloque de codigo
}
```

Ejemplo 1:

```javascript
for (var a = 0; a < 10; a++) {
  //Bloque de codigo
  console.log(a + "Hola mundo");
}
```

Ejemplo 2:

```javascript
var x = 0,
  Medida;
var Dias = ["L", "M", "Mi", "J", "V"];
Medida = Dias.length;
for (x; x < Medida; x++) {
  console.log(Dias[x]);
}
```

Ciclo **_For/in_**

Este tipo de ciclo es determinado por la cantidad de datos, que contiene un objeto por ejemplo un arreglo, una matriz, etc.

```javascript
var Equipo = {"Karen", "Eduardo", "Ana", "Maria", "Jorge"};
var c;
for (c in Equipo) {
  console.log(Equipo[c]);
}
```

Ciclo **_While_**

Este tipo de Ciclos se ejecutan siempre y cuando una condicion especifica sea verdadero (true)

La estructura es:

```javascript
while (Condicion) {
  // Bloque de codigo
}
```

Ejemplo:

```javascript
var i = 0;
while (i < 20) {
  console.log(i);
  i++;
}
```

Ciclo **_Do While_**

Variante del ciclo While, este tipo de ciclo primero ejecuta el bloque de código sin importar si la condición es verdadera, en seguida repetirá siempre y cuando la condición se cumpla.

La estructura es:

```javascript
do {
  // Bloque de codigo
} while (condicion);
```

Ejemplo:

```javascript
var z = 11;
do {
  console.log("Contador en " + z);
  z++;
} while (z < 10);
```

El resultado seria:
Contador en 11.

**[⬆ Back to Top](#tabla-de-contenido)**

### Método getElementById

Es un método que permite seleccionar un elemento del documento por medio del valor del atributo id que se le haya asignado.
La sintaxis es importante ya que si hace distinción, tanto en el atributo id del objeto como en el método.
La sintaxis es la siguiente:

```javascript
document.getElementById("id");
```

Ejemplo:

```javascript
<html>
  <head>
    <title>Método </title>
  </head>
  <body>
    <p id="DivBotones">Seccion Ocultar/Mostrar</p>
    <button onclick="Accion('Ocultar');">Ocultar</button>
    <button onclick="Accion('Mostrar');">Mostrar</button>
  </body>
</html>
```

```javascript
function Accion(Tipo) {
  var elem = document.getElementById("DivBotones");
  if (Tipo == "Ocultar") elem.style.display = "none";
  else elem.style.display = "";
}
```

| Elegido por su atributo id          |         Elegido por su atributo name          | Elegido por el tipo de etiqueta HTML (tag) |
| :---------------------------------- | :-------------------------------------------: | -----------------------------------------: |
| document.getElementById(‘valorId’); |   document.getElementsByName(‘valorName’);    | document.getElementsByTagName(‘valorTag’); |
| document.getElementById (menu1);    | document.getElementsBy Name(‘peticionDatos’); |      document.getElementsByTag Name(span); |

**[⬆ Back to Top](#tabla-de-contenido)**

### InnerHTML

InnerHTML es una propiedad que nos permite leer un dato o asignarlo al contenido de un div o bien, del mismo control. Nos facilita la asignación de valores a controles.

Ejemplo 1:

```html
<html>
  <body>
    <div id="DivContenedor"><p>Texto inicial</p></div>
    <p>Clic para tomar texto inicial</p>
    <button onclick="AccionInnerHTML()">Try it</button>
    <p id="TextoResultante"></p>
    <script>
      function AccionInnerHTMLn() {
        var ConseguirDatoInicial = document.getElementById("DivContenedor")
          .innerHTML; //Leer valor
        document.getElementById("TextoResultante").innerHTML =
          "El texto inicial es: " + ConseguirDatoInicial; //Asignar valor
      }
    </script>
  </body>
</html>
```

La sintaxis es:

Leer valor de control:

```javascript
HTMLElementObject.innerHTML;
```

Asignar valor a control:

```javascript
HTMLElementObject.innerHTML = Texto;
```

En el ejemplo utilizamos la propiedad document.getElementById para tomar la referencia del id del contenedor.

Ejemplo 2:

```html
<html>
  <body>
    <div id="DivContenedor">
      <h1>Texto inicial</h1>
    </div>
    <script>
      var element = document.getElementById("DivContenedor");
      element.innerHTML = "Texto final";
    </script>
  </body>
</html>
```

**[⬆ Back to Top](#tabla-de-contenido)**

### Arreglos

Colección de datos similares. Se reconoce como un arreglo por que se presenta con un par de corchetes [ ].

```javascript
var arreglo = ["a", "b", "c", "d", "e", "f", "g"];
console.log(arreglo);
```

![Arreglos1](https://user-images.githubusercontent.com/24228373/97820509-4cd62080-1c8d-11eb-82a3-e377193374b6.png)

Los elementos de un arreglo comienzan desde el numero cero es decir la primera posición del arreglo es cero y así de forma ascendente para cada uno de los elementos:

```javascript
console.log(arreglo[3]);
```

Si se especifica una posición que no existe en el arreglo es decir que esta fuera de los limites del mismo o bien conocido como desbordamiento de arreglo, JavaScript a diferencia de otros lenguajes de programación no regresara un error si no el valor undefined:

```javascript
console.log(arreglo[2] arreglo[4] arreglo[16]);
```

Una vez declarado el arreglo , al hacer referencia a el en seguida escribimos un punto lo cual nos mostrara un listado de todas las funciones que son prototipos del mismo.

![Arreglos2](https://user-images.githubusercontent.com/24228373/97820600-9e7eab00-1c8d-11eb-9104-0ec5c2c4325e.png)

**[⬆ Back to Top](#tabla-de-contenido)**

### Funciones de los arreglos

```javascript
var arreglo = [5, 4, 3, 2, 1];
console.log(arreglo);
console.log(arreglo[0], arreglo[4], arreglo[5]);
```

.reverse: invierte el orden del arreglo

```javascript
arreglo.reverse();
console.log(arreglo);
```

.map(): Nos permite ejecutar una función con cada uno de los componentes del arreglo sin necesidad de recorrer con un bucle. En el siguiente ejemplo no solo ejecutamos map, si no regresamos el valor del elemento ya multiplicado al arreglo.

```javascript
arreglo = arreglo.map(function (elem) {
  elem *= elem;
  return elem;
});

console.log(arreglo);
```

.join: convierte todas las posiciones del arreglo en una cadena de texto, al no especificar parámetro para la función. El carácter que se especifique como parámetro para la función sera el que separara a los elemento que componen el arreglo, al no especificar ninguno la función separa los elementos con una coma.

```javascript
arreglo = arreglo.join(";");
console.log(arreglo);
```

.split: Corta el arreglo con el carácter que se especifica como parámetro, al no especificar ninguno solo regresa una cadena.

```javascript
arreglo = arreglo.split(";");
console.log(arreglo);
```

.push: Javascript permite agregar un elemento extra al arreglo son necesidad de definirlo inicialmente como se haría en algún otro lenguaje de programación.

```javascript
arreglo.push("6");
console.log(arreglo);
```

**[⬆ Back to Top](#tabla-de-contenido)**

### Objetos

Javascript esta diseñado en un paradigma basado en objetos. Un objeto es una colección de propiedades que lo definen como tal.

Los objetos en Javascript se pueden comparar con objetos de la vida real, por ejemplo: una mesa un objeto tangible, tiene propiedades como medidas, color, etc. que la definen. De esta misma forma en Javascript se pueden caracterizar los objetos.

Los objetos tiene propiedades asociadas que son lo mismo que las variables comunes de JavaScript. Las propiedades de un objeto definen las características de un objeto. La sintaxis para identificar cada una de ellas es

**Id_NombreDelObjeto.Propiedad**

Existen 3 formas para definir un objeto:

```html
<script>
  var Taza = {Taza.color = "blanca",Taza.peso = "350 gramos",Taza.volumen = "250 cm3"};
</script>
```

Es la forma básica pero también la mas sencillas, ya que las propiedades del objeto se definen entre corchetes únicamente separados por comas (,)

```html
<script>
  var Taza = new Objeto();
  Taza.color = "blanca";
  Taza.peso = "350 gramos";
  Taza.volumen = "250 cm3";
</script>
```

En esta forma utilizamos el operador “new” para crear un instancia de un tipo de objeto a partir de una función

```html
<script>
  function Taza(color, peso, volumen) {
    this.Color = color;
    this.Peso = peso;
    this.Volumen = volumen;
  }
  var clasificar = new Taza("blanca", "350 gramos", "250 cm3");
</script>
```

Para esta forma se crear un objeto haciendo una función.
