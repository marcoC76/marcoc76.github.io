---
layout: post
section-type: post
title: Fundamentos de Programación
category: SegundoPeriodo
tags: [ 'instrucciones' , 'pasos', 'secuencia', 'inicio', 'final']
---

### Presentación electronica

 <div style="position: relative;
            padding-bottom: 56.25%;
            height: 0;
            overflow: hidden;">
<iframe style="position: absolute;
                 top:0;
                 left: 0;
                 width: 100%;
                 height: 100%;" width="550" height="400" src="https://marcoc76.github.io/musical-pancake/fundamentosProg.html"></iframe></div><br>

[Pantalla completa](https://marcoc76.github.io/musical-pancake/fundamentosProg.html "Presentación en pantalla completa")

### Lenguajes de programación 

Cuando se aplica cualquier metodología para la resolución de problemas,
con la intención de presentar un programa que se pueda ejecutar en la
computadora, forzosamente tendremos que elegir el lenguaje de
programación a utilizar, en nuestro caso, un lenguaje de cuarta
generación como lo es Pascal.

Es importante aclarar que la computadora tiene su propio idioma, de tal
forma que tendremos que considerar los diferentes lenguajes que existen,
tales como:

Lenguaje máquina. Serie de instrucciones directamente entendibles por la
computadora, pero de muy difícil manejo para cualquier programador.

Lenguaje de bajo nivel. Conjunto de instrucciones específicas
entendibles por la computadora. Las instrucciones se escriben en códigos
alfabéticos conocidos como mnemotécnicos.

Lenguaje de alto nivel. Serie de instrucciones escritas con palabras muy
similares al idioma propio, esto implica que la computadora requerirá de
un traductor para entender convertirlo al lenguaje máquina, el cual es
el único idioma que interpreta la computadora.

Lo anterior requiere que manejes los elementos mínimos necesarios para
manipular el ambiente, lo que implica el uso de menús, operaciones con
los bloques de  instrucciones, así como la forma de imprimir tus códigos
y pantallas de ejecución.

Pascal es por naturaleza un lenguaje de programación estructurado, por
lo cual en el podrás codificar programas modulares con una metodología
de programación estructurada.

En algunos casos se requiere que la información procesada dentro del
programa se almacene para su posterior tratamiento, por lo cual se
tendrán que definir estructuras de datos especialmente para esto.

Los archivos que se revisaran son los de tipo texto y los estructurados,
donde en el primero la forma de almacenamiento es mediante código ASCII,
mientras que en el segundo es mediante el uso de registros.

### Javascript  
<!-- cambiar por progracion con bloques appLab -->

JavaScript es un lenguaje de programación de alto nivel, que se ejecuta
dentro de los navegadores. Por ejemplo, un sistema operativo (Linux,
Windows, Mac..) que gestiona programas como el navegador (Firefox,
Chrome, IE, etc…) y estos a su vez gestionan cómo se representan los
entornos visuales en las pantallas, los sonidos, etc…

Sabiendo todo esto, al final del día nuestro código puede sufrir
fluctuaciones a la hora de ejecutarse en función del entorno que estemos
usando, por suerte, el navegador gestionará de manera automática gran
parte de todo esto, pero aún así podemos sufrir gran cantidad de
variaciones debido a que cada navegador “interpreta” nuestro JavaScript
lo mejor que puede, aunque no de la misma forma.

Uno de nuestros principales cometidos, será hacer que nuestro código sea
capaz de lograr los objetivos que nos proponemos independientemente de
la plataforma donde se vaya a ejecutar, aunque a esto ya estaréis
familiarizados con el día a día desarrollando con HTML5 y CSS3.

### Fundamentos  

Todos los programas JavaScript se incluyen dentro de documentos HTML. En
HTML, un script se incluye con la etiqueta

    <script language=”JavaScript”  >.

Después de esto se a˜nade el texto de lo que es el script, formado por
una serie de instrucciones. Cuando se acaba de editar el script se
cierra con

    </script>

As´ı un texto en JavaScript incluido en un documento HTML debe tener la
siguiente apariencia:

    <script language ="JavaScript">                                           
        texto del script                                                            
    </script>                                                               


JavaScript tiene poca sintaxis. Para marcar el final de una l´ınea debe
ponerse un punto y coma (;). Se pueden dejar espacios en blanco y pulsar
Intro para que el texto sea más legible, pero las l´ıneas de c´odigo no
terminan hasta que se pone un punto y coma.

### Sintaxis y semántica de los lenguajes  

#### Sintaxis  

> Reglas que determinan cómo se pueden construir y secuenciar los
elementos del lenguaje

#### Semántica  

> Significado de cada elemento del lenguaje ¿Para qué sirve?

#### Editor  

> Bloc de notas, Wordpad, Word, Writer, Gedit, Kwrite, …

> (texto simple, sin formatos)

> Editores específicos: coloreado sintáctico

> Recomendación: Notepad++, visual studio code, brackets.io, etc...

#### Sangría y presentación  

La sangría en la programación informática, es una manera de estructurar
el código para hacerlo más legible. Las instrucciones son priorizadas en
varios niveles y espacios de usos o lengüetas para desplazar a la
derecha y crear una jerarquía. Un ejemplo de código sangrado:

Código: JavaScript


    function interruptor (elemID) {                                             
      var elem = document.getElementById(elemID);                              
      if (elem.style.display == 'block') {                                     

        var elem = document.getElementById(elemID);                            
      } else {                                                                  
        elem.style.display = 'block';                                           
      }                                                                         
    }                                                                          


#### Comentarios  

Los comentarios son anotaciones realizadas por el desarrollador para
explicar el funcionamiento de un script, una instrucción o incluso un
grupo de instrucciones. Los comentarios no interfieren con la ejecución
de un script.

Hay dos tipos de comentarios: los de fin de línea y los multilínea.

Comentarios de fin de línea. Se utilizan para comentar una instrucción.
Comienza con dos barras de división:

Código: JavaScript


    sentencia_1 //Esta es mi primera instrucción                             
    sentenci a_2;                                                              
    //La tercera declaración es la siguiente:                                 
    sentencia_3;                                                              


El texto colocado en un comentario se ignora cuando se ejecuta un
script, lo que significa que puedes poner un comentario, incluso en una
instrucción.

Código: JavaScript


    sentencia_1 // Esta es mi primera instrucción                             
    sentencia_2;                                                              
    // La tercera declaración da problemas, la cancelo temporalmente           
    // sentencia_3;                                                         


Comentarios multilínea. Este tipo permite saltos de línea. Un comentario
multilínea comienza con /* y termina con   * /:

Código: JavaScript


    /   * Este script consta de tres pasos:                                      
    - Instrucción uno está haciendo algo                                       
    - Instrucción dos para otra cosa                                           
    - Instrucción  tres que pone fin a la secuencia de comandos                 
       * /                                                                       
    sentencia_1;                                                               
    sentencia_2;                                                               
    sentencia_3 //Fin del script                                            


Ten en cuenta que un comentario de varias líneas se pueden mostrar en
una sola línea:

Código: JavaScript


   sentencia_1 /* Esta es mi primera instrucción* /                       
   sentencia_2;                                                             
 

### Variables  

Cuando programamos, podemos crear variables que son pequeños espacios de
memoria a los que ponemos un nombre como “nombre  _usuario”, y que nos
permite almacenar datos que posteriormente podremos modificar si
deseamos.

> En Pseudocódigo:


    // Esto es un comentario                                                    
    nombreUsuario = "Pepe"                                                      
    nombreOtroUsuario = "Roberta"                                              


> Equiparación en JavaScript:


    // Esto es un comentario                                                    
    var  nombreUsuario = "Pepe";                                                
    var nombreOtroUsuario = "Roberta" ;                                       


Las variables son espacios de memoria donde almacenamos temporalmente
datos desde los que podemos acceder en cualquier momento de la ejecución
de nuestros programas. Tienen varios tipos y clases que veremos a
continuación.

Para definir una variable en JavaScript, utilizamos la palabra reservada
var y le damos un nombre, por ejemplo:


    var miDato;                                                                


También le podemos asignar un valor en la misma línea que la declaramos,
por ejemplo, a continuación a la variable dato le asignamos el valor 5 :


    var dato = 5;                                                             


O podemos primero declarar la variable y más adelante, en otra línea,
asignarle un valor:


    var dato;                                                                   
    dato = 5;                                                                  


Debemos intentar que los nombres de las variables sean lo más
descriptivos posibles, de manera que con solo leerlos sepamos que
contienen y así nuestros desarrollos serán más ágiles.

#### Tipos  

JavaScript tiene 4 tipos primitivos de datos para almacenar en
variables. Estos son:

> number

> boolean

> string

##### number  

Sirve para almacenar valores numéricos. Son utilizados para contar,
hacer cálculos y comparaciones. Estos son algunos ejemplos:


   var miEntero = 1;                                                           
   var miDecimal = 1.33;                                                      


##### boolean  

Este tipo de dato almacena un bit que indica true o false . Los valores
booleanos se utilizan para indicar estados. Por ejemplo, asignamos a una
variable el estado false al inicio de una operación, y al finalizarla lo
cambiamos a true . Después realizamos la comprobación necesaria.


   var si  =  true;                                                            
   var  no  = false;                                                          


##### string  

Las variables de tipo string almacenan caracteres o palabras. Se
delimitan entre comillas simples o dobles. Ejemplo:


    var dato = "Esto es un string";                                             
    var otroDato = 'Esto es otro string' ;                                    


#### Operadores aritméticos  

JavaScript posee operadores para tipos y objetos. Estos operadores
permiten formar expresiones. Las más comunes son las operaciones
aritméticas.

> Suma de números: 5 + 2

> Resta: 5 - 2

> Operaciones con paréntesis: (3 + 2) - 5

> Divisiones: 3 / 3

> Multiplicaciones: 6   * 3

El operador suma + también puede usarse para concatenar strings de la
siguiente manera: "Hola " + "mundo" + "!" tendrá como resultado "Hola
mundo!".

JavaScript también posee los operadores post y pre incremento y
decremento que añaden uno o restan uno a la variable numérica en la que
se aplican. Dependiendo si son pre o post, la variable es
autoincrementada o decrementada antes o después de la sentencia. Veamos
un ejemplo:


    var x = 1; // x=1                                                           
    var y = ++x; // x=2, y=2                                                    
    var  z = y++ + x;// x=2, y=3, z=4                                          


Como vemos en el ejemplo, la sentencia y = ++x lo que hace es
incrementar x, que valía 1 y pasa a tener el valor 2, y la asignación y
= ++x hace que y valga lo que x , es decir 2.

En la última sentencia tenemos un postincremento, esto lo que hace es
primero evaluar la expresión y después realizar el incremento. Es decir
en el momento de la asignación z = y++ + x , y vale 2 y x también 2, por
lo tanto z vale 4, y después de esta asignación y es incrementada
pasando a tener el valor 3.

![](images/image1.png)

Ejemplo usando los operadores aritmeticos


    <html>                                                                   
        <head>  </head>                                                         
        <body>                                                                   
            <center>                                                                 
                <script language ="JavaScript">                                         
                    var  a=2+3;                                                               
                    var  b=2*3;                                                              
                    var  c=7/2;                                                               
                    var  d=7%2;                                                               
                    document.write( "a=" +a+ "  <br>" );                                      
                    document.write( "b=" +b+ "  <br>" );                                      
                    document.write( "c=" +c+ "  <br>" );                                      
                    document.write( "d=" +d+ "  <br>" );                                      
                </script>                                                               
            </center>                                                               
        </body>                                                                 
    </html>                                                                


### Condicionales  

Cuando necesitamos que el sistema tome decisiones, debemos plantearle
las múltiples opciones en una estructura condicional concreta.

Para que la lógica del sistema pueda decidir, necesitamos reducir todo a
comparaciones susceptibles de devolver un valor booleano (verdadero o
falso).

Por ejemplo:

##### Operaciones matemáticas

> 1+1 = 2

> 5 es mayor que 3

> -5 es menor que cero

##### Operaciones lógicas

> La variable “nombreUsuario” es igual a “Pepe”

> La variable “nombreUsuario” no esta vacía

A la hora de representar las opciones. PseInt nos da dos opciones
principales. La estructura Si.. entonces y Según, la diferencia en este
contexto está en función del número de opciones.

En el caso de Si…

Entonces solo manejamos dos opciones cuando la condición se cumple, y
cuando no se cumple.

En el caso de Según

Podemos manejar múltiples valores y con ello multiples opciones sobre
las que el sistema deberá decidir.

Si una condición puede cumplirse en múltiples casos, el sistema se
decidirá por la primera e ignorará el resto.

Si… Entonces

> En Pseudocódigo:


    Si  1 + 1 == 2 Entonces                                                     
        Escribir "La suma es correcta"                                            
    Sino                                                                        
        Escribir "La suma es incorrecta"                                          
    Fin Si                                                                     


> Equiparación en JavaScript:


    if ( 1 + 1 === 2) {                                                         
        console.log( "La suma es correcta" )                                       
    }else{                                                                   
        console .log("La suma es incorrecta" )                                      
    };                                                                         


Según

> En Pseudocódigo:


    Escribir  "hola usuario! ¿Cómo te llamas?"                                  
    Leer nombreUsuario                                                          
    Segun nombreUsuario Hacer                                                   
        "Pepe" :                                                                  
            Escribir "Hola Pepe! Yo te conozco"                                    
        "Lucia" :                                                                 
            Escribir "Hola Lucia! Yo te conozco"                                   
        De Otro Modo:                                                             
            Escribir "Eres nuevo... Bienvenido!"                                   
    Fin Segun                                                                  


> Equiparación en JavaScript:


    var nombreUsuario = prompt( "hola usuario! ¿Cómo te llamas?")               
    switch(nombreUsuario){                                                    
        case "Pepe":                                                           
            console.log( "Hola Pepe! Yo te conozco" );                             
            break;                                                                 
        case "Lucia":                                                         
            console.log( "Hola Lucia! Yo te conozco" );                           
            break;                                                                
        default:                                                                
            console.log( "Eres nuevo... Bienvenido!" );                           
    }                                                                          


Los condicionales son expresiones que nos permiten ejecutar una
secuencia de instrucciones u otra diferente dependiendo de lo que
estemos comprobando. Permiten establecer el flujo de ejecución de los
programas de acuerdo a determinados estados.

Como ya vimos en pseudocódigo, una de las estructuras más útiles a la
hora de gestionar el flujo de nuestra aplicación es el uso de
condicionales.

If nos permite evaluar una condición y actuar en consecuencia. Las
instrucciones que se encuentran entre corchetes, se ejecutan sólo cuando
la condición se cumple.

#### Sentencia IF  

Como hemos visto antes, dependiendo del resultado de una condición,
obtenemos un valor u otro. Si el resultado de la condición requiere más
pasos, en lugar de utilizar la asignación condicional, es mejor emplear
la sentencia if . Tenemos 3 formas de aplicarlo:

##### if simple  


    if  (condicion) {                                                           
        bloque_de_codigo                                                        
    }                                                                          
    if (1  === 1){                                                              
        console.log( "1 es igual a 1 y por eso me ejecuto" );                    
    }                                                                           
    if ( 1  === "1" ){                                                         
        console.log( "No son del mismo tipo y por eso... este texto jamás      
    será mostrado en la consola." );                                             
    }                                                                          


Si se cumple la condición dentro del paréntesis, se ejecuta el bloque de
código incluido entre las llaves { ... }

##### if/else  

En ciertas ocasiones, necesitaremos que nuestro script elija entre dos
caminos en función de si una premisa es verdadera o falsa, por eso
JavaScript nos permite utilizar else.

El programa solo puede ejecutar una de las dos opciones, por tanto una
parte del código quedará sin ejecutarse.

    if(condicion) {                                                           
        bloque_de_codigo_1                                                     
    }else{                                                                    
      bloque_de_codigo_2                                                     
    }                                                                          

Con este tipo de sentencia, si se cumple la condición pasa como el
anterior modelo, se ejecuta el bloque de código 1, y si la condición a
evaluar no se cumple, se ejecuta el bloque de código 2.

    console.log( "pase lo que pase... esto se ejecutará" );                    
    if  ( true ) {                                                             
        console.log( "true, por eso me ejecuto" );                              
    } else  {                                                                   
        console.log( "false, por eso me ejecuto" );                             
    }                                                                           
        console.log( "pase lo que pase... esto se ejecutará también" );          

### Sentencia Switch  

Con Switch, podemos sustituir un conjunto de sentencias if-else de una
manera más legible. Se comprueba la condición, y según el caso que
devuelva, ejecutará un bloque u otro. Para poder separar los bloques, se
utiliza la palabra break que permite salir de toda la sentencia. Tiene
un bloque default que se ejecuta en el caso de que no se cumpla ningún
caso. Veamos un ejemplo, esto sería un switch siguiendo el ejemplo
anterior del if-else :

    switch (condicion) {                                                        
        case  condicion_1:                                                        
            bloque_1                                                                   
        break ;                                                                    
        case  condicion_2:                                                        
            bloque_2                                                                   
        break ;                                                                    
        case  condicion_3:                                                        
            bloque_3                                                                   
        break ;                                                                    
        default :                                                                  
            bloque_4                                                                   
    }                                                                          

El bloque default no es obligatorio.

JavaScript dispone de una opción más para crear estructuras
condicionales. Switch permite crear estructuras más optimizadas para
cubrir un amplio abanico de casos posibles.

Por otra parte Switch tiene varias desventajas notables:

> No tiene una sintaxis sencilla

> Es importante utilizar y comprender conceptos propios como case, break
o default.

> En ocasiones puede ser difícil de depurar.

> Erróneamente se piensa que Switch es exageradamente más rápido que
if-else

Entendiendo la estructura:

    switch (expresión) {                                                        
     case  n1:                                                                  
     //Código                                                                   
     break ;                                                                    
     case  n2:                                                                  
     //Código                                                                   
     break ;                                                                    
     default :                                                                  
     //Código                                                                   
    }                                                                          

Trabajando con “casos únicos”:

    var  nombre = "" ;                                                          
     switch  (nombre) {                                                         
       case   "Pepe" :                                                          
         console .log( "Hola Pepe" );                                           
       break ;                                                                  
       case   "Luis" :                                                          
         console .log( "Hola Luis" );                                           
       break ;                                                                  
       case   "Antonio" :                                                       
         console .log( "Hola Antonio" );                                        
       break ;                                                                  
       default :                                                                
         console .log( 'Ninguno de los nombres que pensamos... es '            
    +nombre);                                                                   
    }                                                                          

### Array  

Es una colección de datos que pueden ser números, strings, objetos,
otros arrays, etc… Se puede crear de dos formas con el literal [...] o
creando una nueva instancia de la clase Array

    var  miArray = [];                                                          
     var  miArray = new   Array ();                                             
     var  miArray = [ 1 , 2 , 3 , 4 ]; // Array de números                      
     var  miArray = [ "Hola" , "que" , "tal" ]; // Array de Strings             
     var  miArray = [ { propiedad : "valor1"  }, { propiedad : "valor2"  }];   
    // Array de objetos                                                         
     var  miArray = [[ 2 , 4 ], [ 3 , 6 ]]; // Array de arrays, (Matriz);       
     var  miArray = [ 1 , true , [ 3 , 2 ], "Hola" , { clave : "valor" }];     
    // Array mixto                                                             

Se puede acceder a los elementos del array a través de su índice y con
length conocer su longitud.

    var  miArray = [ "uno" , "dos" , "tres" ];                                  
    miArray[ 1 ]; // Devuelve: "dos"                                            
    miArray.length; // Devuelve 3                                              

Si accedemos a una posición que no existe en el array, nos devuelve
undefined .

    miArray[ 8 ]; // undefined                                                 

### String  

Como vimos al principio de este libro, los strings son un tipo de
variable primitivo en JavaScript, pero también, al igual que con Number
tienen su clase propia y métodos.

Un string se comporta como un Array, no es más que un conjunto de
caracteres, con índices que van desde el 0 para el primer carácter hasta
el último. Veamos algunos ejemplos de cómo acceder a los caracteres y
los métodos que posee esta clase.

    // Supongamos el string  con el texto "javascript"                          
     "javascript" [ 2 ] // Acceso como array, devuelve el tercer carácter v    
    , ya que la primera posición                                               

    "javascript" .length() // Devuelve 10                                       
     "javascript" .charCodeAt( 2 ) // Devuelve el caracter en formato          
    UNICODE de "v" , el 118                                                     
     "javascript" .indexOf( "script" ); // Devuelve el índice donde comienza   
    el string   "script" , el 4                                                 
     "javascript" .substring( 4 , 10 ); // Devuelve la parte del string        
     comprendida entre los indices 4  y 10 -Para crear un string  podemos      
    hacerlo con notación de tipo o creando un nuevo objeto.                    

Por simplicidad se utiliza la forma primitiva.

    var  texto = "Hola Mundo" ;                                                 
    var  texto = new   String ( "Hola Mundo" );                               

Un string puede ser transformado en array con el método split()
pasándole como parámetro el delimitador que queramos que separe los
elementos. Por ejemplo:+

    var fecha = new Date();                                                     
    fecha = fecha.toString(); // "Wed May 20 2015 20:16:25 GMT+0200 (CEST)"    

    fecha = fecha.split( " " ); // [ "Wed" , "May" , "20" , "2015" ,           
    "20:16:25" , "GMT+0200" , "(CEST)" ]                                        
    fecha[4]; // "20:16:25"                                                    


### Bucles  

En ocasiones nos interesa que determinados bloques de código se ejecuten
varias veces mientras se cumpla una condición. En ese caso tenemos los
bucles para ayudarnos. Dependiendo de lo que necesitemos usaremos uno u
otro. A continuación veremos cuales son y algunos ejemplos prácticos
para conocer su uso.

Existen 3 elementos que controlan el flujo del bucle. La inicialización
que fija los valores con los que iniciamos el bucle. La condición de
permanencia en el bucle y la actualización de las variables de control
al ejecutarse la iteración.

Los bucles son instrucciones que permiten ejecutar repetidamente un
conjunto de mandatos.

#### While  

El primer bucle que veremos está específicamente diseñado para funcionar
de manera constante, mientras una condición dada siga cumpliéndose.

Este bucle está pensado para simplificar la sintaxis cuando el control
del bucle no se realiza mediante operaciones matemáticas (mayor que…
menor que…).

Para ejecutar un bucle, es necesario definir una condición. Mientras que
sea verdadera

(true), el bucle se repite. Una vez que la condición es falsa (false),
el bucle se detiene. Aquí se muestra un ejemplo de la sintaxis de un
bucle while:

Código: JavaScript

    while (condicion) {                                                         
    sentencia_1;                                                             
    sentencia_2;                                                             
    sentencia_3;                                                             
    }                                                                          

##### Funcionamiento  

> Estructura:

    while(-Condición-) {                                                      
    -Instrucciones>                                                           
    };                                                                         

> Ejemplo:

    var  condicion = true                                                       
     while  (condicion) {                                                       
     console .log( "hola" );                                                    
    condicion = false ;                                                         
    };                                                                         

Por ejemplo si queremos mostrar por consola los números del 1 al 10, con
un bucle while sería así:

    var  i = 1 ; // Inicialización                                              
     while  (i   < 11 ) { // Condición de permanencia                            
     console .log(i); // Código a ejecutar                                      
    i++; // Actualización de la variable de control                             
    }                                                                           
     // Devuelve: 1 2 3 4 5 6 7 8 9 10                                         

#### Do while  

Este bucle se asemeja mucho al bucle while, excepto que en este caso el
bucle se ejecuta siempre por lo menos una vez. En el caso de un bucle
while, si la condición no es válida, el bucle no es ejecutado Con do
while, el bucle se ejecuta una vez, entonces la condición se comprueba
para determinar si el bucle debe continuar. La sintaxis de un bucle do
while es:

Código: JavaScript

    do {                                                                        
    sentenci a  _1 ;                                                             
    sentenci a  _2 ;                                                             
    sentenci a  _3 ;                                                             
    } while (condición) ;


Hay una diferencia fundamental de escritura respecto al bucle while, que
puede hacer ver la diferencia entre ambos. Sin embargo, el uso de do
while no es muy común, y es muy posible que no tengas nunca que usarlo
porque los programadores suelen emplear un bucle while normal con una
condición que hace que siempre se ejecute una vez. Atención a la
sintaxis del ciclo do while: hay un punto y coma después del paréntesis
de cierre de while.

    var  i = 1 ;                                                                
     do  {                                                                      
     console .log(i);                                                           
    i++;                                                                        
    } while  (i   < 11 );                                                        
     // Devuelve: 1 2 3 4 5 6 7 8 9 10                                         


#### For  

Este bucle presenta una estructura optimizada para controlar la
ejecución de la iteración de manera numérica.

El bucle For se divide en tres partes separadas por un punto y coma.

##### Expresión inicial  

Será todo aquello que se ejecutará al iniciarse el bucle.

##### Condición  

Será evaluada antes de cada iteración. Este es el único parámetro
obligatorio.

##### Expresión de actualización  

Se ejecutará al final de cada iteración.

##### Funcionamiento  

> Estructura:


    for  (-Expresión inicial-; -Condición-; -Expresión Actualización-) {        
    -Instrucciones>                                                           
    };                                                                         


> Ejemplo clásico:


    for  (var i  = 0 ; i    < 10 ; i ++) {                                       
    console.log(i);                                                             
    }                                                                          


#### Errores comunes  

##### Bucle infinito  

Es un error muy común y deberías evitarlo a toda costa. Suele ocurrir
cuando no tenemos una estructura de control funcionando adecuadamente.

    while  ( true ) {                                                           
     console .log( "Este texto se imprime hasta el infinito..." );              
    };

##### Bucle que no se ejecutará  

Igualmente es un error más sutil, pero por definición un código que
jamás se ejecuta…

¡sobra!

    while  ( false ) {                                                          
     console .log( "Este texto jamas se imprimirá..." );                        
    };
    
Ejemplo:

   var  control = 1 ;                                                          
    while  (control   <= 10 ) {                                                 
    console .log(control);                                                     
   control++;                                                                  
   };                                                                         


### Funciones  

#### Sintaxis de la Función de JavaScript  

Una Función de JavaScript se definen con la clave palabra función ,
SEGUIDA DE UN nombre , Seguido de Paréntesis () .

Los nombres de: funciones pueden Contener letras, Dígitos, subrayados y
signos de Dólar (las Mismas reglas Que las variables de).

Los Paréntesis pueden Incluir nombres de Parámetros Separados por comas:

( parámetro1, parámetro2, ... )

El código se ejecutará Que, por la Función, se Coloca Entre llaves: {}

    function   name (parameter1, parameter2, parameter3) {                      
        //code to be executed                                                   
    }

Función parámetros se enumerar dentro de la paréntesis () en la
definición de función.

Función argumentos son los valores recibidos por la función cuando se
invoca.

Dentro de la Función, los Argumentos (los parámetros) se comportan Como
las variables locales.

Las funciones de JavaScript son el alma de este lenguaje, por eso se
consideran ciudadanos de primera clase (first-class citizen), además de
entidades de orden superior.

#### Manejo  

> Declarar funciones

Como valor de una variable:

    var  miFuncion = function (){                                               
       console.log( "Hola!" );                                                  
    }

> Ejecutar funciones

Ahora ejecutamos nuestras propias funciones y métodos.

    var  miFuncion = function (){                                               
       console.log( "Hola!" );                                                 
    }                                                                           
   miFuncion();

Las funciones normalmente, al acabar su ejecución devuelven un valor,
que conseguimos con el parámetro return . Se declaran con la palabra
reservada function y a continuación suelen llevar un nombre, para poder
invocarlas más adelante. Si no llevan nombre se les llama funciones
anónimas.

Veamos un ejemplo de función:

    var saludar = function  (nombre) {                                      
       return  ( "Hola "  + nombre + "!" );                                 
    }                                                                       
    saludar( "Carlos" ); // Devuelve "Hola Carlos!"                          


La función del ejemplo se llama saludar , y se le pasa un único
parámetro, entre paréntesis (...) , que es nombre . Ese parámetro
funciona como contenedor de una variable que es utilizada dentro del
bloque de código delimitado por las llaves {...}. El comando return
devolverá el String que concatena texto con el valor que contiene el
parámetro nombre.
