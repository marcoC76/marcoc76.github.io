---
layout: post
section-type: post
title: Algoritmos
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
                 height: 100%;" width="550" height="400" src="https://marcoc76.github.io/musical-pancake/algoritmos.html"></iframe></div><br>

[Pantalla completa](https://marcoc76.github.io/musical-pancake/algoritmos.html "Presentación en pantalla completa")

### Algoritmos  

La lógica computacional está relacionada íntimamente con la manera en
que utilizas tu pensamiento lógico, esto es, con la  forma en que
resuelves un problema.

Cuando se plantea un problema, para su resolución se aplican diferentes
técnicas, como lo son la lineal, las estructurada y la orientada a
objetos.

Un algoritmo es un procedimiento para resolver un problema dado. Un
algoritmo se describe con un conjunto finito y ordenado de pasos que
deben llevarse a cabo para producir la solución a dicho problema.

Pasos para solucionar un problema

1.- Diseño del algoritmo, describe la secuencia ordenada de pasos, sin

ambigüedades, que conducen a la solución de un problema dado. (Análisis
del

problema y desarrollo del algoritmo).

2.- Expresar el algoritmo como un programa en un lenguaje de
programación

adecuado. (Fase de codificación).

3.- Ejecución y validación del programa por computadora.

![](https://i.chzbgr.com/full/9172487680/hB9EB3712/)

La completa ejecución de un algoritmo debe finalizar con la producción
del resultado esperado a partir de las entradas proporcionadas.

![]({{ site.baseurl }}/img/entradaysalida.PNG)

> Corresponde al insumo, a los datos necesarios que requiere el proceso
para ofrecer los resultados esperados.

> Pasos necesarios para obtener la solución del problema o la situación
planteada.

> Resultados arrojados por el proceso como solución.

El orden en que se disponen los pasos del algoritmo debe ser riguroso;
esto implica que deben existir unos pasos antes que otros u otros antes
de unos. No se podrá multiplicar A por B si, previamente, no se conocen
sus respectivos valores.

El algoritmo es la antesala del programa que ejecutará la computadora, y
cuando éste se traslada al lenguaje escogido para representarlo se debe
conservar el orden preestablecido en él, independientemente del lenguaje
seleccionado. 

Un algoritmo, una vez construido, puede expresarse en
lenguajes diferentes de programación y ejecutarse en computadoras
distintas; sin embargo, el algoritmo será siempre el mismo. De ahí que
los errores lógicos que se cometan en la elaboración de éste pasarán al
lenguaje y, por ende, a la computadora, el cual reproducirá exactamente
lo que se le ha mandado; éste no tiene el poder para detectar errores
humanos.

Los algoritmos tienen las siguientes propiedades:

> Un algoritmo debe ser preciso e indicar el orden de realización de
    cada paso.

> Un algoritmo debe estar definido. Si se sigue un algoritmo dos
    veces, se debe obtener el mismo resultado cada vez.

> Un algoritmo debe ser finito. Si se sigue un algoritmo, se debe
    terminar en algún momento; o sea, debe tener un número finito de
    pasos.

![](https://www.picgifs.com/graphics/r/rubiks-cube/animaatjes-rubiks-cube-7217468.gif)

Ejemplos de algoritmos

<hr>

Se quiere abrir una puerta, la persona se encuentra frente de ella,
tiene la llave que abre

¿Qué pasos requieres hacer para abrirla?


> Paso 1 Coloca la llave en  la cerradura                                 
> Paso 2 Gira la  llave a la derecha                                  
> Paso 3 Da una vuelta                                       
> Paso 4 El pasador cede                                                 
> Paso 5 La puerta se abre

![](https://i.pinimg.com/originals/39/ac/41/39ac41a313ae2e231910cf5a58883cd9.gif)

<hr>

Algoritmo para comprar las boletas de entrada al cine.

    ​1. Inicio
    ​2. Seleccionar la película
    ​3. Llegar al lugar de proyección de la película
    ​4. Revisar la cartelera
    ​5. Hacer la fila de pago
    ​6. Esperar el turno
    ​7. Solicitar la película.
        Si la hay
    ​       7-1. Entregar el dinero
    ​       7-2. Esperar por las boletas y la diferencia de pago
    ​       7-3. Retirarse
        Si no hay la película
    ​       7-4. Escoger otra película o retirarse
    ​8. Fin

![](https://www.gifmania.com/Gif-Animados-Peliculas-Cine/Imagenes-Elementos-Cine/Cines/Cine-Antiguo-82068.gif)

<hr>

Calcular el área y el perímetro de un rectángulo.

Datos de entrada:

base y altura

Datos de salida:

área y perímetro

Operaciones a ejecutar:

area resulta de base\*altura

perímetro resulta de 2\*(base + altura)

Algoritmo:


    Inicio                                                                  
        Leer (base , altura)                                                  
        area vale base\*altura                                                
    perimetro vale 2\*( base + altura)                                     


### Diagramas de flujo 

Un diagrama de flujo es una técnica que te permite la representación
gráfica de un algoritmo, muestra los pasos o procesos para alcanzar la
solución a un problema , utiliza símbolos estandarizados y normalizados
por ANSI (American National Standars Institute), en donde cada símbolo
representa el tipo de operación a ejecutar.

Elaboremos el algoritmo y el diagrama de flujo de la suma de dos números

![]({{ site.baseurl }}/img/ejemplo.png)

Con base en lo anterior se aprecian los principales símbolos:

![]({{ site.baseurl }}/img/elementosDiagrama.png)


Cuando se utiliza el símbolo de decisión, puede ser simple o múltiple:

![](https://media1.tenor.com/images/74a87da6760e119fdfbb1ee9d2914871/tenor.gif?itemid=5437251)

Decisión simple: Se evalúa una condición en su interior, y dependiendo
del resultado, se selecciona uno de los caminos establecidos.  Este
símbolo también es conocido como estructura algorítmica (o de control)
selectiva sí entonces y sí entonces / sino.

![]({{ site.baseurl }}/img/image6.png)

Decisión múltiple: En su interior se evalúa una condición, y a partir
del valor del resultado, se selecciona una de las acciones planteadas ,
en caso no existir una opción equivalente al resultado, se podrá
implementar una acción para una respuesta diferente a las esperadas.
También se le llama estructura algorítmica selectiva múltiple.

![]({{ site.baseurl }}/img/decisionMultiple.jpg)

Algunas reglas que debes de tener en cuenta al construir los diagramas
de flujo son:

​1. Debe ser de arriba hacia abajo (top - down) y de izquierda a derecha
(left to right).

​2. Debe tener un inicio y un fin.

​3. Las líneas de flujo para indicar la dirección del flujo de
información deben ser rectas , verticales y horizontales.

​4. Todas las líneas de flujo que se utilizan para indicar la dirección
deben estar conectadas a algún símbolo .

​5. La notación utilizada debe ser independiente del lenguaje de
programación .

​6. No debe de llegar más de una línea a un símbolo.

![]({{ site.baseurl }}/img/joder2.png)
![]({{ site.baseurl }}/img/unicornio.png)
![]({{ site.baseurl }}/img/image7.png)

### Pseudocódigo 

Una de las formas de especificar un algoritmo es mediante la escritura
en lenguaje natural  de una secuencia de pasos numerados. El regreso a
un paso anterior o el salto a un paso posterior se indica con palabras.
Otra de las formas de especificarlo es mediante el pseudocódigo, en éste
se utiliza un lenguaje estructurado y cercano a lo que será finalmente
el programa de computadora .

El pseudocódigo es un lenguaje para la especificación de algoritmos con
una sintaxis para las estructuras de control similar a la expresada en
un lenguaje de programación . Traducir un algoritmo escrito en
pseudocódigo a un lenguaje de programación resulta más sencillo que
hacer la traducción desde un algoritmo expresado en lenguaje natural.

![](https://sites.google.com/site/info080910/_/rsrc/1413734217198/pseudocodigo/diagrama2.gif)

Las acciones y las estructuras de control se representan en el
pseudocódigo con palabras reservadas, similares a las utilizadas en los
lenguajes de programación estructurada. Entre estas palabras reservadas,
las más usadas en inglés son: begin, read, write, if-then, if-then-else,
while-end, do-while, repeat for-to y end. 

En español se utilizan
palabras como las siguientes: inicio, leer, escribir, si-entonces,
si-entonces-sino, mientras-hacer, hacer-mientras, repetir desde-hasta y
fin. Es muy recomendable utilizar solo una de estas dos formas durante
la escritura de un algoritmo, ya que la mezcla o uso indistinto de
palabras procedentes del inglés y palabras procedentes del español puede
causar confusión y dificultad en la lectura e interpretación del
algoritmo.

Cuando se usa el pseudocódigo como lenguaje de especificación de un
algoritmo, el programador puede concentrarse en la lógica y en las
estructuras de control,  sin preocuparse por la sintaxis y reglas del
lenguaje de programación.

Con base en esto tenemos que:

> El pseudocódigo es compacto.

> Puede modificarse fácilmente.

> Se utilizan palabras claves en mayúsculas en español , que
identifican las estructuras algorítmicas secuenciales, selectivas y
repetitivas.

> Se construye de manera estructurada (de arriba hacia abajo).

> No existen reglas estándar para utilizarlo.

> No se tiene una representación gráfica de la lógica del programa ,

> No puede ser representado en una computadora .

Pseudocódigo de la suma de dos números

    Inicio                                                                
        Lee (N1)                                                              
        Lee (N2)                                                              
        Suma = N1 + N2                                                        
        Escribe (Suma)                                                        
    Fin                                                                  

Dado un número del 1 al 7, decir qué día de la semana es, partiendo de
que el lunes es 1.


    Inicio
        Escribe ('día' )          
        Lee día                   
        Caso día:                 
            1:Escribe ('Lunes' )   
            2:Escribe  ('Martes')   
            3:Escribe ('Miércoles' )
            4:Escribe  ('Jueves')   
            5:Escribe ( 'Viernes')
            6 :Escribe ('Sábado' ) 
            7:Escribe  ('Domingo') 
        Fin_caso                
    Fin                      


[El conejo y las zanahorias](https://www.google.com/url?q=https://g.co/doodle/ygxau2?ds%3Dcl&sa=D&ust=1537900270722000)
 

### Lenguajes de programación 

![](https://blog.dinahosting.com/wp-content/uploads/2018/06/lenguajes-de-programaci%C3%B3n-1-1.jpg)

Cuando se aplica cualquier metodología para la resolución de problemas,
con la intención de presentar un programa que se pueda ejecutar en la
computadora, forzosamente tendremos que elegir el lenguaje de
programación a utilizar.

Es importante aclarar que la computadora tiene su propio idioma, de tal
forma que tendremos que considerar los diferentes lenguajes que existen,
tales como:

Lenguaje máquina. Serie de instrucciones directamente entendibles por la
computadora, pero de muy difícil manejo para cualquier programador.

![](https://media.giphy.com/media/l1J9RFoDzCDrkqtEc/giphy.gif)

Lenguaje de bajo nivel. Conjunto de instrucciones específicas
entendibles por la computadora. Las instrucciones se escriben en códigos
alfabéticos conocidos como mnemotécnicos.

Lenguaje de alto nivel. Serie de instrucciones escritas con palabras muy
similares al idioma propio, esto implica que la computadora requerirá de
un traductor para entender convertirlo al lenguaje máquina, el cual es
el único idioma que interpreta la computadora.

![  |](https://technical.ly/philly/wp-content/uploads/sites/2/2018/07/code.gif)

Lo anterior requiere que manejes los elementos mínimos necesarios para
manipular el ambiente, lo que implica el uso de menús, operaciones con
los bloques de  instrucciones, así como la forma de imprimir tus códigos
y pantallas de ejecución.

En algunos casos se requiere que la información procesada dentro del
programa se almacene para su posterior tratamiento, por lo cual se
tendrán que definir estructuras de datos especialmente para esto.

Los archivos que se revisaran son los de tipo texto y los estructurados,
donde en el primero la forma de almacenamiento es mediante código ASCII,
mientras que en el segundo es mediante el uso de registros.

![](https://static01.nyt.com/images/2018/10/19/business/19AIcover-illo/19AIcover-illo-mediumThreeByTwo210-v5.gif)

Mas informacion:
[http://uapas1.bunam.unam.mx/matematicas/diagramas\_flujo/](https://www.google.com/url?q=http://uapas1.bunam.unam.mx/matematicas/diagramas_flujo/&sa=D&ust=1537900270724000)


