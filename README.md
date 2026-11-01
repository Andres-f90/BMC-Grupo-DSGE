# Este archivo README explica el Jupyternotebook de la competencia BMC-Afadeco del grupo DSGE

## Limpieza de los datos
Nosotros usamos los datos de MCP-MERCOP y buscamos dejar solo los datos necesarios que usaremos en el futuro siendo estos datos:
* El valor total del negocio
* La fecha de pago
* La descripción subyacente
* El departamento de ubicación
* ECI
* RCI
Estos datos los usaremos para ubicar espacialmente de donde se originan los datos, lo cual puede representar una oportunidad
para los agentes compradores en la Bolsa Mercantil.

## Datos de complejidad económica
### Estadisticas Descriptivas
Estos datos de complejidad económica los calculamos basados en literatura económica, encontramos la ubicuidad de los productos
transados en la bolsa lo que se puede explicar como la complejidad de producción de los productos o que otros departamentos
fabrican estos productos, y la diversificación que se explica como que departamento produce mayor variedad de productos.
Para observar la relación entre estos dos computos en la realidad lo gráficamos con el eje Y con la ubicuidad, y el eje X la
diversificación donde observamos una relación decreciente con mayor diversificación menor ubicuidad y viceversa.

Estos datos serán usados en una matriz para encontrar las ventajas comparativas (RCA) y las matrices endogenas.

### Medición complejidad económica y fitness
Aquí calculamos la complejidad económica de las producciones y la gráficamos con multiples iteraciones para mostrar la
convergencia de los datos dependiendo de las iteraciones.

Luego la matriz MCP ordenada por fitness y complejidad que manifiesta una función relación  logarítmica de mayor complejidad o nivel de especialización en la producción usan el fitness como un cálculo algorítmico , la complejidad es una función más teórica bajo ello se gráfica la función de forma transversal, en relación a estos tipos de subyacentes.

y creamos la matriz de adyacencia que muestra las múltiples correlaciones entre las distintas industrias o producción de distintos artículos entre departamentos,  entre más conectados estén en razon a la gráfica reflejando una mayor conexión , de lo contado hay máyor propensión a choques especulativas, está demuestra un posible puente entre las distintas actividades de acuerdo a esas ventajas.

Por último intentamos realizar una gráfica de correlación espacial dimensional basados en la taxonomía de los productos pero no logramos que la gráfica funcionará de manera correcta no supuso un problema ya que no dependemos de esta gráfica para entender la complejidad de los datos y su correlación.

Y por último creamos una hoja en el mismo excel con los datos para tener los datos que requerimos en la construcción del Dashboard "Complex-Board"
