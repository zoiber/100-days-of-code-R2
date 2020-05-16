# Pronóstico

## El comienzo

---

 El pronóstico es una ayuda importante para una planificación efectiva y eficiente. La previsibilidad de un evento o una cantidad depende de varios factores que incluyen:

- qué tan bien entendemos los factores que contribuyen a ello;
- cuántos datos hay disponibles;
- si los pronósticos pueden afectar lo que estamos tratando de pronosticar.
Si se cumplen estas tres condiciones los pronósticos seran muy precisos.

Por ejemplo, la demanda de electricidad puede ser pronosticada con mayor precisión dado que cumple los tres factores antes mencionados. Por otra parte,  al pronosticar los tipos de cambio de moneda, solo se cumple una de las condiciones: hay muchos datos disponibles. Sin embargo, tenemos una comprensión limitada de los factores que afectan los tipos de cambio, y las previsiones del tipo de cambio tienen un efecto directo sobre los tipos mismos.

A menudo, en el pronóstico, un paso clave es saber cuándo se puede pronosticar algo con precisión y cuándo los pronósticos no serán mejores que lanzar una moneda. Los buenos pronósticos capturan los patrones y las relaciones genuinas que existen en los datos históricos, pero no replican eventos pasados que no volverán a ocurrir.

Muchas personas suponen erróneamente que los pronósticos no son posibles en un entorno cambiante. Cada entorno está cambiando, y un buen modelo de pronóstico captura la forma en que las cosas están cambiando. Lo que normalmente se supone es que la forma en que cambia el entorno continuará en el futuro. Es decir, un entorno altamente volátil seguirá siendo altamente volátil; un negocio con ventas fluctuantes continuará teniendo ventas fluctuantes; y una economía que ha pasado por auges y caídas continuará atravesando auges y caídas.

Un modelo de pronóstico tiene como objetivo capturar la forma en que se mueven las cosas, no solo dónde están las cosas.

### La selección de un método de pronóstico

La elección del método depende de los datos disponibles y de la previsibilidad de la cantidad a pronosticar.

Tipos de pronósticos:

1. Cualitativo: Son utilizados si los datos disponibles no son relevantes para los pronósticos.

2. Cuantitativo: Son aplicables cuando se cumplen dos condiciones:

- Existe información númerica histórica disponible
- Es razonable suponer que algunos aspectos de los patrones pasados continuarán en el futuro.

La mayoría de los problemas de predicción cuantitativa utilizan datos de series de tiempo (recopilados a intervalos regulares a lo largo del tiempo).

Ejemplos de series temporales:

- Precios diarios de acciones de IBM
- Lluvia mensual
- Resultados de ventas trimestrales para Amazon
- Ganancias anuales de Google

Existen dos series temporales; las que se observan a intervalos regulares de tiempo (por ejemplo, cada hora, diariamente, semanalmente, mensualmente, trimestralmente, anualmente) y las series temporales espaciadas irregularmente.

Los intervalos de predicción son una forma útil de mostrar la incertidumbre en los pronósticos. En este caso, se espera que los pronósticos sean precisos y, por lo tanto, los intervalos de predicción son bastante estrechos.

Los métodos de predicción de series de tiempo más simples utilizan solo información sobre la variable a pronosticar, y no intentan descubrir los factores que afectan su comportamiento. Por lo tanto, extrapolarán tendencias y patrones estacionales, pero ignorarán toda otra información, como iniciativas de marketing, actividad de la competencia, cambios en las condiciones económicas, etc.

El modelo que se utilizará en el pronóstico depende de los recursos y los datos disponibles, la precisión de los modelos competidores y la forma en que se utilizará el modelo de pronóstico.

Nota: **Tener en cuenta la tendecia y los patrones estacionales, en caso de haberlos, para desarrollar un modelo de pronóstico**

### Pasos para realizar una tarea de pronóstico

#### Paso 1. Definición del problema

A menudo, esta es la parte más difícil de la previsión. La definición cuidadosa del problema requiere una comprensión de la forma en que se utilizarán los pronósticos, quién los requiere y cómo se ajusta la función de pronóstico dentro de la organización que los requiere. Un pronosticador necesita pasar tiempo hablando con todos los que estarán involucrados en la recopilación de datos, el mantenimiento de bases de datos y el uso de pronósticos para la planificación futura.

#### Paso 2. Recopilación del problema

Siempre se requieren al menos dos tipos de información: (a) datos estadísticos, y (b) la experiencia acumulada de las personas que recopilan los datos y utilizan los pronósticos. A menudo, será difícil obtener suficientes datos históricos para poder ajustar un buen modelo estadístico. En ese caso, se pueden utilizar los métodos de pronóstico crítico. Ocasionalmente, los datos antiguos serán menos útiles debido a cambios estructurales en el sistema que se pronostica; entonces podemos elegir usar solo los datos más recientes. Sin embargo, recuerde que los buenos modelos estadísticos manejarán los cambios evolutivos en el sistema; no deseche buenos datos innecesariamente.

Paso 3. Análisis preliminar (exploratorio)

Comience siempre graficando los datos. ¿Hay patrones consistentes? ¿Hay una tendencia significativa? ¿Es importante la estacionalidad? ¿Hay evidencia de la presencia de ciclos económicos? ¿Hay valores atípicos en los datos que deben ser explicados por aquellos con conocimiento experto? ¿Qué tan fuertes son las relaciones entre las variables disponibles para el análisis? 

Paso 4. Elección y ajuste del modelo(s)

El mejor modelo a utilizar depende de la disponibilidad de datos históricos, la fuerza de las relaciones entre la variable de pronóstico y cualquier variable explicativa, y la forma en que se utilizarán los pronósticos. Es común comparar dos o tres modelos potenciales. Cada modelo es en sí mismo una construcción artificial que se basa en un conjunto de supuestos (explícitos e implícitos) y generalmente involucra uno o más parámetros que deben estimarse utilizando los datos históricos conocidos.

Paso 5. Uso y evaluación de un modelo de pronóstico.

Una vez que se ha seleccionado un modelo y se han estimado sus parámetros, el modelo se usa para hacer pronósticos. El rendimiento del modelo solo puede evaluarse adecuadamente después de que los datos para el período de pronóstico estén disponibles.  Cuando se utiliza un modelo de pronóstico en la práctica, surgen numerosos problemas prácticos, como cómo manejar valores perdidos y valores atípicos, o cómo lidiar con series de tiempo cortas.

### La perspectiva del pronóstico estadístico

Lo que estamos tratando de pronosticar es desconocido (o no lo estaríamos pronosticando), por lo que podemos considerarlo como una variable aleatoria . Por ejemplo, las ventas totales para el próximo mes podrían tomar un rango de valores posibles, y hasta que sumemos las ventas reales al final del mes, no sabemos cuál será el valor. Entonces, hasta que sepamos las ventas para el próximo mes, es una cantidad aleatoria.

En la mayoría de las situaciones de pronóstico, la variación asociada con lo que pronosticamos se reducirá a medida que se aproxime el evento. En otras palabras, cuanto más adelante pronostiquemos, más inseguros estamos.

Cuando obtenemos un pronóstico, estamos estimando la mitad del rango de valores posibles que la variable aleatoria podría tomar. A menudo, un pronóstico va acompañado de un intervalo de predicción que proporciona un rango de valores que la variable aleatoria podría tomar con una probabilidad relativamente alta. Donde el promedio de los posibles valores futuros, llamamos pronósticos puntuales .

## Gráficos de series temporales

---

Lo primero que debe hacer en cualquier tarea de análisis de datos es trazar los datos. Los gráficos permiten visualizar muchas características de los datos, incluidos patrones, observaciones inusuales, cambios a lo largo del tiempo y relaciones entre variables. Así como el tipo de datos determina qué método de pronóstico usar, también determina qué gráficos son apropiados.


