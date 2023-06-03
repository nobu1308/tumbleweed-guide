---
title: "Consejos para principiantes en Tumbleweed"
---

Esta es una traducción del documento «[Consejos para principiantes de Tumbleweed](/beginner-advice/)» escrito por Tellorion. Traducción hecha por poechicero.

# Consejos para principiantes en Tumbleweed

La idea de esta guía es ayudarte a evitar errores comunes que cometen los principiantes en el juego de Tumbleweed, y ayudarte a estructurar tu pensamiento durante tus partidas. Algunos de estos errores pueden ser movimientos que parecen correctos pero que te hacen perder una pila, o «malos hábitos» inducidos por otros juegos a los que juegas (especialmente Go). La mayoría de los puntos siguientes se han elegido porque aparecen a menudo en partidas de principiantes en Board Game Arena. Las secciones que tratan estos errores se complementan con otras secciones sobre principios generales de Tumbleweed. Estos deberían ser útiles para tener una mejor sensación del «flujo de movimientos» y encontrar objetivos a alcanzar en una posición.

Antes de leer esta guía, se recomienda haber jugado algunas partidas y haber visto el siguiente vídeo que explica los escudos y paradas: [Estrategias básicas de defensa en Tumbleweed.](https://www.youtube.com/watch?v=b1q3ZtuE-cc)

Otra cosa: una pequeña observación sobre la terminología del español. En inglés, una pila se traduce como «a stack» y los términos utilizados para las piezas del juego son, por lo tanto, «a 1-stack», «a 2-stack», etc. Dado que es un poco pesado en español, elijo eliminar la palabra «pila» y escribir «un 1», «un 2», etc. en lugar de «una pila de 1», «una pila de 2», etc.

## Jugar un 1 en contacto con una pila adversaria es a menudo malo

Jugar un 1 en contacto con una pila enemiga es generalmente malo si este 1 no es una amenaza directa. Por ejemplo, en el diagrama de la izquierda, Rojo acaba de jugar E5. Blanco puede responder en E6, atacando E5 inmediatamente, y Rojo no tiene ninguna forma de salvar su pila.

{{< columns >}}
![Diagram 1](1.png)
<--->
![Diagram 2](2.png)
{{< /columns >}}

Hay que recordar que los 1 son débiles cuando se colocan. Es posible solidificarlos más adelante, añadiendo líneas de visión sobre ellos, pero inicialmente son muy vulnerables. En general, los 2 o más son mejores para movimientos agresivos en contacto (pero cuidado, los 2 también pueden caer rápidamente si el ataque no es lo suficientemente fuerte). Sin embargo, como se mencionó anteriormente, esto no significa que nunca deba colocarse un 1 en contacto. Si juegas un 1 en contacto que amenaza directamente una captura, por ejemplo, tu adversario tendrá que manejar la amenaza antes de poder contraatacar (ver el diagrama a continuación, donde Rojo juega E6).

{{<figure src="3.png" alt="Diagram 3">}}

La pila roja en E6 ataca D5. Blanco no tiene tiempo de jugar D6 o E5 para atacar E6, ya que en ese caso Rojo simplemente podría capturar D5. Así que para Rojo, jugar este 1 en E6 es un buen movimiento.

## Presta atención a las pilas «muertas» de tu adversario

Cuando se acerca el final del juego, a menudo quedan algunas pilas del adversario aisladas en tu territorio, que puedes capturar en cualquier momento. Puede parecer lento tomar el tiempo para capturarlas, pero a veces es crucial deshacerse de ellas. No subestimes el daño que pueden hacer. Esto se debe a las reglas de Tumbleweed, que hacen que cualquier pila en el tablero dé un cierto número de movimientos posibles al jugador al que pertenece. Esta idea está relacionada con la importancia de las capturas en el juego de Tumbleweed (a diferencia del Go, por ejemplo, donde generalmente no es necesario quitar piedras del tablero para que se considere que están muertas). ¡Capturar una pila reduce el número de movimientos que tu adversario puede jugar! Veamos la siguiente posición, donde una piedra que no tiene ninguna posibilidad de vivir puede ser utilizada para hacer un gran daño.

{{< columns >}}
![Diagram 4](4.png)
<--->
![Diagram 5](5.png)
{{< /columns >}}

Después del movimiento de Blanco en K10, Rojo debe poner un escudo en J9, o Blanco podría capturar I8 y crear una brecha en el muro. Pero después de este escudo de Rojo en J9, Blanco puede jugar H10 o I10 para un doble ataque poderoso.

{{<figure src="6.png" alt="Diagram 6">}}

## La intersección de dos enlaces es un punto crucial

Como se explica al principio del documento [Formas fundamentales en Tumbleweed](/fundamental-shapes/#link), los enlaces son los segmentos entre dos pilas del mismo color que se ven (en otras palabras, que están alineadas). Los enlaces son las «piezas fundamentales» del juego y deben estar en el centro de tu estrategia. El siguiente diagrama muestra un tipo de posición en el que los principiantes a menudo se pierden un movimiento importante, cuando uno de sus enlaces cruza un enlace enemigo.

{{<figure src="7.png" alt="Diagram 7">}}

Los dos enlaces se cruzan en D4. El control de este punto es urgente para ambos jugadores. Una posibilidad es jugar directamente un 2 en D4, otra es jugar en B2 o en F6 para añadir una tercera línea de visión sobre D4 (y por lo tanto impedir este movimiento al oponente). Vamos a ver un ejemplo de partida en la que este tema se presenta desde los primeros movimientos ([Tumblebot](http://34.233.90.87:8000/api/analysis/site) contra sí mismo), después de 1. B2 G8 2.E5G33.E9B3.

{{<figure src="8.png" alt="Diagram 8">}}

Los hexágonos C3 y E6 se encuentran en la intersección de un enlace rojo y uno blanco, por lo tanto son movimientos a considerar para ambos jugadores. La razón para elegir cuál de los dos movimientos es el mejor es un poco más avanzada. Pero para resumir, E6 está más en el centro, y si Rojo jugara C3 y permitiera a Blanco jugar E6, Rojo podría estar demasiado concentrado en la parte superior del tablero, lo que lo pondría en una posición desfavorecida. La secuencia de movimientos recomendada por Tumblebot desde esta posición es, por lo tanto, Rojo en E6, Blanco en C3.

## Reforzar es malo a menos que no haya otra opción

Reforzar una pila es generalmente malo, a menos que no haya otra forma de defenderse de un ataque y si no quieres sacrificar la pila. Por ejemplo, en la siguiente apertura, la pila roja en E5 está siendo atacada, y reforzar el 1 en un 2 sería malo. Reforzar defiende contra el ataque de Blanco, pero no hace nada más. Es un movimiento muy pasivo. Un movimiento mucho mejor para Rojo es jugar una defensa en C5 como en el siguiente diagrama, lo que defiende E5 y abre nuevas líneas de visión, por ejemplo la línea C5-I11 que puede ayudar a Rojo a avanzar hacia abajo. Esto también añade un defensor en el hexágono C3, lo que podría ser útil si Blanco juega B3 después.

{{< columns >}}
![Diagram 9](9.png)
<--->
![Diagram 10](10.png)
{{< /columns >}}

Una buena regla para saber cómo manejar los ataques es: en lugar de reforzar un 1 en 2, es mejor jugar una defensa (añadir una tercera línea de visión sobre el 1). Y antes de jugar un 2, trata de comprobar si no tendrás que reforzarlo pronto en un 3, ya que esto generalmente no es muy eficaz. Sin embargo, en la última parte del juego es normal tener que reforzar pilas.

## El equilibrio del desarrollo

Esta sección es menos un error de principiante que un tema central del juego de Tumbleweed (y una idea que se encuentra en muchos juegos abstractos, especialmente en los juegos territoriales). Como jugador, estás constantemente tratando de encontrar el equilibrio adecuado entre ampliar tu territorio y hacerlo más sólido. Lo interesante es que Tumbleweed tiene un buen indicador para medir esto: la altura de una pila, ya que el número en la pila que quieres colocar indica por definición el número de líneas de visión que tienes sobre ella. Por ejemplo, jugar un 4, un 5 o un 6 no es efectivo en absoluto, ya que este hexágono/casilla ya estaba dentro de tu territorio de forma sólida. Y esta pila no te abre muchas líneas de visión nuevas para desarrollar tu influencia en el tablero.

Tienes que decidir en cada movimiento del juego (excepto en los movimientos forzados) cuál es la forma de proceder. ¿Es el 1 que quieres jugar demasiado arriesgado o solo es un movimiento de desarrollo rápido y efectivo? ¿Jugar un 3 en otro lugar sería lento y poco eficaz o un movimiento sólido que aseguraría tu posición? La respuesta depende del estado del juego. Estas son buenas preguntas que hacerse, y responderás mejor a ellas cuanto más juegues a Tumbleweed.

## Prepara tus formas con anticipación

En la última sección de esta guía, hablaremos un poco más sobre la forma de los grupos y más específicamente, sobre los ángulos. Hay muchas sutilezas y casos especiales, pero es un concepto importante para entender mejor el «flujo» del juego.

Delimitar un territorio en línea recta de un extremo al otro del tablero sería ideal, pero en general tu oponente no será muy cooperativo. Por lo tanto, tus zonas de influencia tendrán ángulos/esquinas. Si has jugado un cierto número de partidas, quizás hayas notado que un tipo de ángulo es el más común: los ángulos obtusos, que son más efectivos que los ángulos agudos.

{{< columns >}}
![Diagram 11](11.png)
<--->
![Diagram 12](12.png)
{{< /columns >}}

En los dos diagramas anteriores, siete pilas se encuentran en la frontera roja (sin contar el 1 en F7), pero el ángulo obtuso a la izquierda delimita el territorio rojo de manera mucho más efectiva que el ángulo agudo a la derecha (es decir, permite hacer más puntos). Además, un hexágono en un ángulo obtuso como el 3 en C4 se puede colocar de manera muy natural: Rojo solo necesita las líneas de visión C6-C5 y D4-G4 (que están presentes para construir las paredes) y una pila de apoyo en F7. Mientras que el 4 rojo en D4, en el diagrama de la derecha, no puede ser construido naturalmente a partir de la forma de territorio que Rojo obtiene al final (hay que utilizar líneas de visión que vienen desde el exterior del triángulo rojo). Un ángulo obtuso debe poder ser reforzado al menos en un 3, y un ángulo agudo debe poder ser reforzado al menos en un 4. No es siempre necesario jugar exactamente en los ángulos, basta con controlarlos teniendo suficientes líneas de visión sobre ellos.

Esto explica por qué generalmente es mejor jugar ángulos obtusos en lugar de agudos. Otra idea muy importante es que los ángulos de tu forma son puntos clave. Es mejor no olvidarlos durante la partida, y es una buena idea decidir de antemano qué ubicaciones quieres usar para tus ángulos. Por supuesto, a menudo tendrás que cambiar tus planes según lo que haga tu oponente, pero tener esto en cuenta te ayudará a dar más estructura a tu juego.

La siguiente posición proviene de una partida entre testing_qwerty (Rojo) y komacchin (Blanco) ([enlace a la partida](https://tumbleweed.games/log/4160/15/).

{{< columns >}}
![Diagram 13](13.png)
<--->
![Diagram 14](14.png)
{{< /columns >}}

Rojo acaba de jugar en H4, atacando al 1 blanco en H7. Y Blanco respondió en H5, un escudo que protege a H7 del ataque rojo. Es un movimiento que también cumple otras funciones. En primer lugar, el movimiento de Blanco en H5 abre nuevas líneas de visión para él a lo largo de la línea D1-K8. Además, pone una tercera línea de visión sobre G5. Así que si el próximo movimiento de Rojo es en G4 para tratar de limitar el acceso de Blanco a la parte superior del tablero, Blanco cuenta con un ángulo sólido en G5 que puede ser reforzado en un 3.
