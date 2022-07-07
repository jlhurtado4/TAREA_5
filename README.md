UNIVERSIDAD DE LAS FUERZAS ARMADAS - ESPE

- NOMBRE: JUAN HURTADO
- NRC: 7318
- FECHA: 8 JULIO 2022

# InformeTarea5

1. OBJETIVOS

- Analizar y entender el capitulo 9 y 10 del libro "Principios de circuitos electricos - Floyd" para lo cual se debera leer y resolver los ejercicios pares que se encuentran al terminar el capitulo.

- - Realizar los ejercicios pares de cada capitulo y explicar como fueron resueltos.
- - Demostrar a travez de un video el conocimiento adquirido del capitulo.
- - Realizar un resumen del conenido de cada capitulo visto.

2. MARCO TEÓRICO (RESUMEN)

- **CAPITULO 9**

 ECUACIONES SIMULTÁNEAS EN EL ANÁLISIS DE CIRCUITOS: Los métodos de análisis de circuitos que se abordan en este capítulo permiten determinar dos o más corrientes o voltajes desconocidos por medio de ecuaciones simultáneas. Estos métodos de análisis, los cuales incluyen corriente en ramas, corriente en lazos, y métodos del voltaje en nodos, producen tanto ecuaciones como incógnitas. La cobertura se limita a ecuaciones con dos incógnitas (2o. grado) y ecuaciones con tres incógnitas (3er. grado). Estas ecuaciones pueden ser resueltas entonces simultáneamente para las incógnitas por medio de uno de los métodos abordados en esta sección. 

Las ecuaciones simultáneas se componen de un conjunto de n ecuaciones que contiene n
incógnitas, donde n es un número con un valor de 2 o más. El número de ecuaciones incluidas en
el conjunto debe ser igual al número de incógnitas. Por ejemplo, para determinar dos variables
desconocidas, se requieren dos ecuaciones; para tres incógnitas se requieren tres ecuaciones, y
así sucesivamente.

Ecuaciones de segundo grado en la forma estándar: 

Una ecuación con dos variables se llama ecuación de segundo grado. En análisis de circuitos, las variables representan incógnitas tales como corriente o voltaje. Para determinar las variables x1 y x2, debe haber un conjunto de dos ecuaciones que contengan esas variables expresadas en la forma estándar. En la forma estándar, las variables x1 ocupan la primera posición en cada ecuación, y las variables x2 ocupan la segunda posición en cada ecuación. Las variables con sus coeficientes están en el lado izquierdo de la ecuación, y las constantes en el lado derecho.

En estas ecuaciones simultáneas, la “a” es el coeficiente de las variables x1 y x2 y puede representar valores de componentes de circuito. Advierta que los subíndices de los coeficientes contienen dos números. Por ejemplo, a1,1 aparece en la primera ecuación como el coeficiente de x1, y a2,1 aparece en la segunda ecuación como el coeficiente de x1. La “b” es la constante y puede representar una fuente de voltaje. Esta notación será usada cuando se utilice una calculadora para resolver las ecuaciones.

MÉTODO DE LA CORRIENTE EN RAMAS: El método de la corriente en ramas es un método de análisis de circuitos que utiliza las leyes del voltaje y de la corriente de Kirchhoff para determinar la corriente que circula en cada rama de un circuito generando ecuaciones simultáneas. Una vez que se conocen las corrientes presentes en las ramas, se pueden determinar los voltajes.

Los siguientes son los pasos generales utilizados al aplicar el método de la corriente en ramas.

Paso 1. Asignar una corriente a cada rama del circuito en una dirección arbitraria.

Paso 2. Indicar las polaridades de los voltajes presentes en los resistores de acuerdo con las direcciones de las corrientes asignadas a las ramas.

Paso 3. Aplicar la ley del voltaje de Kirchhoff alrededor de cada lazo (la suma algebraica de los voltajes es igual a cero).

Paso 4. Aplicar la ley de la corriente de Kirchhoff en el número mínimo de nodos de modo que todas las corrientes de rama estén incluidas (la suma algebraica de las corrientes que entran o salen a un nodo es igual a cero).

Paso 5. Resolver las ecuaciones resultantes de los pasos 3 y 4 para determinar los valores de las corrientes de rama.

MÉTODO DE LA CORRIENTE DE LAZO: En el método de la corriente de lazo (también conocido como método de corrientes), se trabajará con corrientes de lazo en lugar de corrientes de rama. Un amperímetro colocado en una rama dada medirá la corriente que circula por esa rama. A diferencia de las corrientes de rama, las de lazo son cantidades matemáticas, y no corrientes físicas reales, que se utilizan para volver al análisis de circuitos un poco más fácil de lo que resulta con el método de corrientes de rama. 

En los pasos siguientes se proporciona un método sistemático para efectuar el análisis de lazos, la cual es la misma configuración de circuito utilizada en el análisis de corrientes de rama. Esta configuración demuestra muy bien los principios básicos.

Paso 1. Aunque la dirección asignada a una corriente de lazo es arbitraria, se asignará una corriente en el sentido de las manecillas del reloj (SMR) alrededor de cada lazo no redundante, por consistencia. Ésta puede no ser la dirección de la corriente real, pero no importa. El número de asignaciones de corrientes de lazo debe ser suficiente para incluir las corrientes que circulan a través de todos los componentes del circuito.

Paso 2. Indicar las polaridades de las caídas de voltaje en cada lazo con base en las direcciones de corriente asignadas.

Paso 3. Aplicar la ley del voltaje de Kirchhoff alrededor de cada lazo. Cuando más de una corriente de lazo pasa a través de un componente, se deberá incluir su caída de voltaje. Esto produce una ecuación para cada lazo.

Paso 4. Resolver las ecuaciones resultantes para las corrientes de lazo utilizando sustitución o determinantes. 

Circuitos con más de dos lazos:

El método de la corriente en lazos puede ser sistemáticamente aplicado a circuitos que tengan cualquier cantidad de lazos. Desde luego, mientras más lazos haya, más difícil será encontrar la solución, pero las calculadoras han simplificado en gran medida la resolución de ecuaciones simultáneas. La mayor parte de los circuitos con que usted se encontrará no tendrá más de tres lazos. Recuerde que las corrientes de lazo no son corrientes físicas reales sino cantidades matemáticas asignadas para propósitos de análisis. Un circuito ampliamente utilizado con el que ya se topó usted es el puente Wheatstone. Éste originalmente se diseñó como un instrumento de medición autónomo, pero ha sido reemplazado en gran medida por otros instrumentos. No obstante, el circuito puente Wheatstone se encuentra incorporado en instrumentos de medición automáticos, y como previamente se explicó, se utiliza mucho en la industria de las básculas y en otras aplicaciones de medición. Un método para determinar los parámetros del puente, y que conduce directamente a encontrar la corriente en cada brazo del puente y la corriente de carga, es escribir ecuaciones de lazo para el puente.

MÉTODO DEL VOLTAJE EN NODOS: Otro método de análisis de circuitos de lazos múltiples se denomina método del voltaje en nodos. Se basa en la determinación de los voltajes presentes en cada nodo del circuito mediante la ley de la corriente de Kirchhoff. Recuerde que un nodo es la unión de dos o más componentes. 

Los pasos generales para aplicar el método del voltaje en nodos al análisis de circuitos son los
siguientes:

Paso 1. Determinar el número de nodos.

Paso 2. Seleccionar un nodo como referencia. Todos los voltajes serán con respecto al nodo de referencia. Asignar designaciones de voltaje a cada nodo donde el voltaje es desconocido.

Paso 3. Asignar corrientes en cada nodo donde se desconoce el voltaje, excepto en el nodo de referencia. Las direcciones son arbitrarias.

Paso 4. Aplicar la ley de la corriente de Kirchhoff a cada nodo donde se asignan las corrientes.

Paso 5. Expresar las ecuaciones de corriente en función de voltajes, y resolver las ecuaciones para determinar los voltajes de nodo desconocidos mediante la ley de Ohm.

Método del voltaje en nodos para el circuito puente T:

Al aplicar el método del voltaje en nodos al circuito puente T se obtienen también dos ecuaciones con dos incógnitas. Igual que en el caso del puente Wheatstone, hay cuatro nodos. El nodo D es la referencia y el A es el voltaje de fuente, de tal suerte que los dos voltajes desconocidos están en los nodos C y D. El efecto de un resistor de carga en el circuito es casi siempre la pregunta más importante, por lo que el voltaje en el nodo C es el objetivo principal. La solución de las ecuaciones simultáneas con una calculadora se simplifica para analizar el efecto de varias cargas porque solamente la ecuación para el nodo C se ve afectada cuando cambia la carga.

- **CAPITULO 10**

EL CAMPO MAGNÉTICO: Un imán permanente tiene un campo magnético alrededor de él. El campo magnético consiste en líneas de fuerza que se irradian desde el polo norte (N) hasta el polo sur (S) y de regreso al polo norte a través del material magnético.

Flujo magnético (fi): El grupo de líneas de fuerza que van del polo norte al polo sur de un imán se llama flujo magnético, simbolizado mediante fi (la letra griega fi). El número de líneas de fuerza presentes en un campo magnético determina el valor del flujo. Mientras más líneas de fuerza haya, más grande es el flujo y más intenso el campo magnético.

Densidad de flujo magnético (B): La densidad de flujo magnético es la cantidad de flujo por unidad de área perpendicular al campo magnético. Se simboliza mediante B, y su unidad SI es el tesla (T). Un tesla es igual a un weber por metro cuadrado (Wb/m2). La fórmula siguiente expresa la densidad de flujo:

ELECTROMAGNETISMO: El electromagnetismo es la producción de un campo magnético por una corriente en un conductor. 

La corriente produce un campo magnético, llamado campo electromagnético, alrededor de un conductor. Las líneas de fuerza invisibles del campo magnético forman un patrón circular concéntrico alrededor del conductor y son continuas a todo lo largo de éste. A diferencia de la barra imantada, el campo magnético que rodea un conductor no tiene polos norte o sur. La dirección de las líneas de fuerza que rodean el conductor mostrado en la figura es para corriente convencional. Las líneas están en el mismo sentido que las manecillas del reloj. Cuando se invierte la corriente, las líneas del campo magnético van en dirección contraria a la de las manecillas del reloj. Aunque el campo magnético no es visible, tiene capacidad para producir efectos visibles. Por ejemplo, al insertar perpendicularmente en una hoja de papel un conductor que transporta corriente, limaduras de hierro colocadas en la superficie del papel se acomodan en líneas de fuerza magnéticas formando anillos concéntricos.

DISPOSITIVOS ELECTROMAGNÉTICOS: Muchos tipos de dispositivos útiles, tales como grabadoras de cinta, motores eléctricos, altavoces, solenoides y relevadores, están basados en el electromagnetismo. 

El solenoide: El solenoide es un tipo de dispositivo electromagnético provisto de un núcleo de hierro móvil llamado émbolo. El movimiento de este núcleo de hierro depende tanto del campo electromagnético como de la fuerza mecánica de un resorte. Consiste en una bobina cilíndrica de hilo arrollado alrededor de una forma hueca no magnética. Un núcleo de hierro estacionario está fijo en el extremo de la flecha y un núcleo de hierro deslizante (émbolo) está unido al núcleo estacionario por medio de un resorte.

HISTÉRESIS MAGNÉTICA: Cuando se aplica una fuerza magnetizante a un material, la densidad de flujo del material cambia en cierto modo. 

Intensidad de campo magnético (H): La intensidad de campo magnético (llamada también fuerza magnetizante) en un material se define como la fuerza magnetomotriz (Fm) por unidad de longitud (l) del material, y se expresa mediante la fórmula siguiente. La unidad de intensidad de campo magnético (H) es el amperevueltas por metro (ampere-turn/metro, At/m). 

La curva de histéresis y retentividad:

La histéresis es una característica de un material magnético por la cual un cambio de magnetización retrasa la aplicación de la intensidad de campo magnético. La intensidad de campo magnético (H) puede ser incrementada o reducida con facilidad variando la corriente a través de la bobina de alambre, y puede ser invertida invirtiendo la polaridad del voltaje presente en la bobina.

INDUCCIÓN ELECTROMAGNÉTICA: Cuando un conductor se mueve a través de un campo magnético, se produce un voltaje entre los extremos del conductor. Este principio se conoce como inducción electromagnética y el voltaje resultante es un voltaje inducido. El principio de inducción electromagnética es lo que posibilita la existencia de transformadores, generadores eléctricos, y muchos otros dispositivos.

Movimiento relativo:

Cuando un conductor se mueve a través de un campo magnético, existe un movimiento relativo entre el conductor y el campo magnético. Asimismo, cuando un campo magnético se mueve más allá de un conductor estacionario, también existe movimiento relativo. En ambos casos, este movimiento relativo produce un voltaje inducido (vind) en el conductor.

La letra minúscula v denota voltaje instantáneo. Sólo se induce voltaje cuando el conductor “corta” las líneas magnéticas como se muestra. La cantidad de voltaje inducido (vind) depende de la densidad de flujo, B, de la longitud del conductor, l, expuesta al campo magnético, y de la velocidad a la cual el conductor y el campo magnético se mueven uno con respecto al otro. Mientras más rápida es la velocidad relativa, más grande es el voltaje inducido.



3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

**EJERCICIOS CAPITULO 9**

![alt text]()

**EJERCICIOS CAPITULO 10**

![alt text]()

4. VIDEO



5. CONCLUSIONES

◆ El método de la corriente en ramas está basado en las leyes del voltaje y de la corriente de Kirchhoff.

◆ El método de la corriente en lazos está basado en la ley del voltaje de Kirchhoff.

◆ La corriente que circula en un lazo no es necesariamente la corriente real presente en una rama.

◆ El método del voltaje en nodos está basado en la ley de la corriente de Kirchhoff. 

◆ Los polos magnéticos desiguales se atraen entre sí y los polos iguales se repelen uno a otro.

◆ Los materiales que pueden ser magnetizados se llaman ferromagnéticos.

◆ Cuando hay corriente a través de un conductor, se produce un campo electromagnético alrededor del conductor.

◆ Se puede utilizar la regla de la mano derecha para establecer la dirección de las líneas de fuerza electromagnéticas presentes alrededor de un conductor.

◆ Un electroimán es básicamente una bobina de alambre alrededor de un núcleo magnético.

◆ Cuando un conductor se mueve adentro de un campo magnético, o cuando un campo magnético se mueve con respecto a un conductor, se induce un voltaje entre los extremos del conductor.

◆ Mientras más rápido es el movimiento relativo entre un conductor y un campo magnético, más grande es el voltaje inducido. 

6. BIBLIOGRAFÍA

Floyd, T. L, (2007). _PRINCIPIOS DE CIRCUITOS ELECTRICOS_. México: PEARSON EDUCACIÓN.

RUBRICA
![alt text]()
