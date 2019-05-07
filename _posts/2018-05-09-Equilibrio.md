---
layout: post
section-type: post
title: Estática
category: 
tags: [ ]
---

<script src='https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.2/MathJax.js?config=TeX-MML-AM_CHTML'></script>

Estática
========

Es la rama de la física que se estudia a los cuerpos en equilibrio. Esta rama es
parte de la dinámica solo que estudia el caso en el cual el valor de la
aceleración es igual a cero.

### Equilibrio

Un cuerpo está en equilibrio si no tiene aceleración, esto es, si la aceleración
de un cuerpo es cero. O un cuerpo está en equilibrio cuando la suma de las
fuerzas externas que actúan sobre es cero.

El equilibrio se puede clasificar en equilibrio estático cuando el cuerpo
permanece en reposo y en equilibrio dinámico cuando el cuerpo tiene un
movimiento rectilíneo uniforme.

La fuerza resultante fue definida como una fuerza única cuyo efecto es el mismo
que el de un sistema dado de fuerzas.

#### Equilibrio de una partícula

Para simplificar el estudio de este tipo de cuerpos es equilibrio se pueden
despreciar sus dimensiones y considerarse como una partícula.

![]({{ site.baseurl }}/media/b9afb71649af9c3d222a65def6d48479.png)

![]({{ site.baseurl }}/media/aa4fdf693eb06a9a72faffc3bedffd14.png)

#### Condición de Equilibrio

Una partícula está en equilibrio cuando la suma vectorial de todas las fuerzas
que actúan sobre ellas es igual a cero. Ya que de acuerdo con la segunda ley de
Newton si la fuerza neta es igual a cero, entonces la aceleración es igual a
cero. Matemáticamente:

$$\overrightarrow{F_{n}} = 0$$

En función de todas las fuerzas actuantes:

$$\overrightarrow{F_{1}} + \overrightarrow{F_{2}} + \overrightarrow{F_{3}} + \ldots + \overrightarrow{F_{N}} = 0$$

O lo que es lo mismo:

$$\sum_{i = 1}^{N}{\overrightarrow{F_{i}} = 0}$$

En donde:

$$\sum = \ suma\ de\ldots$$

$$\overrightarrow{F_{i}} = fuerza\ i\ sobre\ la\ particula$$

$$\overrightarrow{F_{N}} = fuerza\ enecima\ sobre\ la\ particula$$

Expresando la ecuación anterior en función de componentes rectangulares de las
fuerzas:

$$\sum F_{x}=0$$

$$\sum F_{y}=0$$

Ejemplo:

Una persona que pesa 800N descansa sobre una hamaca. La cuerda cercana a la
cabeza de la persona hace un ángulo α de 25° con la horizontal, mientras que la
cuerda que se encuentra en los pies hace un ángulo $$\theta$$ de 40° con la
horizontal. Determina la magnitud de las tensiones que ejercen las cuerdas.

![]({{ site.baseurl }}/media/998787d43034b644b28663b1f394a3b3.png)

Solución:

Para determinar las componentes rectangulares de las fuerzas, determinamos los
ángulos que hacen dichas fuerzas con el eje x, es decir para T2 el ángulo será
180-25=155°, y para W será de 270°.

Emplearemos la siguiente tabla:

![]({{ site.baseurl }}/media/tablaEquilibrio.png)

Al aplicar las ecuaciones de condición de equilibrio:

$$\sum F_{x} = 0.766T_{1} - 0.906T_{2} = 0$$

$$\sum Fy = 0.642T_{1} + 0.423T_{2} - 800 = 0$$

Despejamos T1:

$$T_{1} = \frac{0.906\ T_{2}}{0.766\ }$$

Sustituyendo:

$$0.642\left( \frac{0.906}{0.766} \right)T_{2} + 0.423\ T_{2} - 800 = 0$$

$$1.182\ T_{2} = 800$$

Despejamos T2:

$$T_{2} = 676.81\ N$$

Sustituimos:

$$T_{1} = \ \frac{0.906}{0.766}\left( 676.81 \right)$$

$$T_{1} = 800.51N$$

#### Fuerza resultante y fuerza equilibrante

Cuando un cuerpo o una partícula está sometido a la acción de varias fuerzas y
se quiere conocer las fuerza que hay que aplicar para que dicho cuerpo
permanezca en equilibrio, lo que se determina primero es la fuerza resultante,
es decir la fuerza que puede sustituir a dichas fuerzas cuando actúan
simultáneamente, ya que produce el mismo efecto que ellas. Conocidas esta
fuerza, la fuerza equlibrante será la fuerza de igual magnitud y dirección que
la resultante pero, de sentido contrario.

![]({{ site.baseurl }}/media/85af82483afc3f38a8a88397d4adb3f7.png)

![]({{ site.baseurl }}/media/4c39b0683b66051cf7a4964dbe44b7ee.png)

![]({{ site.baseurl }}/media/112e5f2f92da43d2b70271a93bf65568.png)

#### Momento de una fuerza o torque

Es una magnitud física que indica la capacidad de una fuerza para producir
rotación a un cuerpo y se representa por la letra griega τ (tau).

El momento de fuerza depende tanto de la magnitud de la fuerza aplicada y de la
distancia del eje de giro del cuerpo al punto de aplicación de la fuerza como
del ángulo entre la fuerza y la línea que une al eje de giro con el punto de
aplicación.

![Resultado de imagen para llave tuerca torque]({{ site.baseurl }}/media/92b3275ba9b3196841514a02ff15b7c6.png)

![]({{ site.baseurl }}/media/0004717a4a8c4a5e4b4ffb232508b6e3.png)

El momento de fuerza es una magnitud vectorial cuya magnitud se puede obtener
por:

$$\tau = rF\sin\theta$$

En el SI, la unidad del momento de fuerza o torque es el newton-metro (Nm).

Ejemplo:

Un técnico ejerce una fuerza de 80N en el extremo de una llave inglesa de 20cm.
Si esta fuerza forma una ángulo de 70° con el mango de la llave, ¿Cuál es la
magnitud del momento de fuerza producido en la tuerca?

![]({{ site.baseurl }}/media/6870750eb9e5bf85476149b137e1c117.png)

Solucion:

La magnitud se calcula por:

$$\tau = rF\sin\theta$$

Al sustituir valores:

$$\tau = \left( 0.20m \right)\left( 80N \right)\sin{70}$$

$$\tau = 15Nm$$

#### Momento de fuerza resultante

El momento resultante se obtiene de sumar algebraicamente los momentos de fuerza
positivos y negativos debidos a cada fuerza. Matemáticamente:

$$\tau_{R} = \sum \tau$$

Ejemplo:

Determina el momento de fuerza resultante sobre un sube y baja, si uno de los
niños pesa 250N y se encuentra a 0.70m del eje de giro. El otro niño pesa 220N y
se encuentra a 1.5 m del eje de giro.

![]({{ site.baseurl }}/media/7dbc1dddf713154924483a29c547c9df.png)

Solución:

Primero elaboramos un diagrama de cuerpo libre

Datos:

$$r_{1} = 1.5\ m$$

$$r_{2} = 0.7m$$

$$F_{1} = 220N$$

$$F_{2} = 250N$$

$$\overrightarrow{\tau_{r}} = \overrightarrow{\tau_{1}} + \overrightarrow{\tau_{2}}$$

$$\tau = r_{1}F_{1} - r_{2}F_{2}$$

$$\tau = \left( 1.5m \right)\left( 220N \right) - \left( 0.7m \right)\left( 250N \right)$$

$$\tau = 155\ Nm$$

#### Par de fuerzas

Cuando dos fuerzas de igual magnitud y sentidos contrarios actúan sobre el mismo
punto de un cuerpo rígido, este permanecerá en equilibrio, pero si estas fuerzas
se aplican en untos diferentes, de manera que sus líneas de acción sean
paralelas, el cuerpo girara.

Dos fuerzas de igual magnitud pero opuestas y cuyas líneas de acción sea
paralelas constituyen un par de fuerzas. El momento resultante es independiente
de la elección del punto a partir del cual se miden las distancias. La magnitud
del momento de fuerza resultante se obtiene de la siguiente ecuación:

$$\tau = Fd$$

Donde

$$F = magnitud\ de\ las\ fuerzas\ actuantes\ en\ el\ par$$

$$d = distancia\ entre\ las\ dos\ fuerzas$$

Ejemplo:

Sobre un volante de 60cm de diámetro se aplica un par de fuerzas. La magnitud de
las fuerzas aplicadas es de 30N. ¿Cuál es la magnitud del momento de fuerza
resultante?

Solución:

$$d = 60cm = 0.6m$$

$$F = 30N$$

Formula:

$$\tau = Fd$$

$$\tau = \left( 30N \right)\left( 0.6m \right)$$

$$\tau = 18Nm$$

#### Equilibrio de cuero rígido

Un cuerpo rígido es aquel en el que las distancias entre dos de sus puntos
cualquiera permanecen constantes, es decir, no se deforman por la acción de
fuerzas externas.

<br>
<div style="width:100%;height:0;padding-bottom:104%;position:relative;"><iframe src="https://giphy.com/embed/9qmq1WGohyFbO" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div>
<br>

Un cuerpo rígido debe satisfacer las siguientes condiciones para estar en
equilibrio.

1.- Equilibrio de traslación. La suma vectorial de todas las fuerzas que actúan
sobre el cuerpo debe ser cero.

$$\sum \overrightarrow{F} = 0

En función de sus componentes:

$$\sum \overrightarrow{F_{x}} = 0$$

$$\sum \overrightarrow{F_{y}} = 0$$

2.- Equilibrio de rotación. Para que un cuerpo rígido se encuentre en
equilibrio, la fuerza resultante debe ser cero y el momento de fuerza resultante
también debe de ser cero.

$$\sum \overrightarrow{\tau} = 0$$

<hr>
<br>
<div style="position: relative;
            padding-bottom: 56.25%;
            height: 0;
            overflow: hidden;">
<iframe style="position: absolute;
                 top:0;
                 left: 0;
                 width: 100%;
                 height: 100%;"  id="iframe_container" frameborder="0" webkitallowfullscreen="" mozallowfullscreen="" allowfullscreen="" width="550" height="400" src="https://prezi.com/embed/9rs1ocvqyy9t/?bgcolor=ffffff&amp;lock_to_path=0&amp;autoplay=0&amp;autohide_ctrls=0&amp;landing_data=bHVZZmNaNDBIWnNjdEVENDRhZDFNZGNIUE1UdnROaC9ZSXU1QU5qY2Y5OVdnMXI4WUl6Y3pLTXVtdnBzWis1N3VRPT0&amp;landing_sign=-C6VBL2urBykj9pAPDzGFLeCnghmmw4ByHZ36uZL0Bs"></iframe></div><br>