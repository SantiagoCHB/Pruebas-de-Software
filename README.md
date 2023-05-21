# Pruebas-de-Software
**¿Qué son las Pruebas de Software?**

> "Son el mejor método para confirmar la funcionalidad del producto que se esta desarrollando"(Vive UNIR, 2022). 
>
En otras palabras, las pruebas son un proceso de instrospeccón que se realiza en un proyecto de software,todo esto con el fin de descrubrir fallos o errores no vistos en el momento.
Principalmente porque, "lo que se lleva a cabo durante estas pruebas es una evaluación minuciosa para verificar la funcionalidad de un determinado producto" (Vive UNIR, 2022).
Por ende, el beneficio de esta evaluación es comprobar que todo funcione tal y como debe, ayudando a cerrar el margen de error en temprana fases del desarrollo. Esto no quiere decir que solo se puedan realizar en estas fases, ya que estas pruebas pueden llevarse a cabo en diferentes etapas del ciclo de vida del desarrollo de software.

**Tipos de Pruebas de Software**

Dentro de estas evaluaciones, "existen diversos tipos, donde cada uno se caracteriza por poseer sus propias particularidades y, por lo tanto, aplicaciones distintas"(uniR, 2022). A continuación los tipos:

1. **Pruebas unitarias o _until testing_**

> "Comprueban que cada una de las piezas o unidades más pequeñas del software en el que se está trabajando funcione correctamente" (Viva UNIR, 2022)

El objetivo prinicipal de las pruebas unitarias es veirficar que cada unidad de código funcione correctamente de manera individual y aislada, de acuerdo con las especificaciones y los requisitos establecidos. Al momento de realizar estas pruebas unitarias, se busca identificar cualquier error o defecto en la lógica o el comportamiento de una unidad en particular.

Las pruebas unitarias por lo generalmente se desarrollan por los propios desarrolladores y se llevan a cabo en un entorno controlado.

Entre sus ventajas y beneficios encontramos el aislamiento del código o la detección temprana de errores. Asimismo "está el ahorro de tiempo y de dinero, ya que permiten detectar errores al principio y evitar seguir avanzando arrastrando ese fallo que va a condicionar el resto del proyecto" (Viva UNIR, 2022).

2. **Pruebas de integración**

>"el objetivo de estas pruebas es comprobar que los difernetes componentes operan bien juntos" (Viva UNIR, 2022)

En otras palabras, estas se enfocan en evaluar la correcta interacción y comunicación entre los diferentes componentes o unidades de código que se han integrado en un sistema o aplicación. El obejtivo principal de las pruebas de integración es identificar problemas o errores que puedan surgir cuando las diferentes partes del software interactuen entre si.

Estas pruebas de integración se realizan despues de las pruebas unitarias y antes de las pruebas de sistemas. Algunos enfoques comunes son:

- Pruebas de integración ascendente (bottom-up): Comienza probando las unidades más pequeñas o los componentes indivuales y luego avanza hacia niveles superiores de integración.

- Pruebas de integración descendente (top-down): Comienza probando los componentes más altos o de nivel superior y luego se avanza hacia niveles inferiores de integración

- Pruebas de integración combinadas (sandwich): Combina enfoques ascendentes y descendentes, realizando pruebas de integración en diferentes niveles y direcciones para asegurar una cobertura exhaustiva.

Asimismo, algunos de los benificios de las pruebas de integración son la detección temprana de problemas de interoperabilidad o la verificación de la funcionalidad completa del sistema.

3. **Pruebas de rendimiento**

> "Se trata de chequear la respuesta del software ante cargas de trabajos diferentes y en condiciones reales." (Viva UNIR, 2022)

En concreto, el objetivo principal de las pruebas de rendimiento es medir y analizar el rendimiento, la velocidad, la estabilidad y la escabilidad del software. Estas pruebas se llevan a cabo para simular situaciones de uso realistas y determinar cómo responde el software ante un alto volumen de usuarios, una gran cantidad de datos o una carga intensiva. Al realizar pruebas de rendiiento, se busca identificar posibles cuellos de botella, puntos de estrangulamiento o en general debilidades del sistema.

Por ende, algunos aspectos que se suelen evaluar son: tiempo de respuesta, escalabilidad, estabilidad, uso de recursos, resistencia al estrés, entre otros. Gracias a esto, los beneficios que traen estas pruebas son la identificación de cuellos de botellas y puntos debiles, y mejora de la experiencia del usuario.

4. **Pruebas de estrés**

> "es necesario comprobar cuánta tensión puede soportar el sistema antes de que se produzca algún error" (Viva UNIR, 2022)

Su funcion es determinar el punto de quiebre o límite del sistemas y observar cómo se comporta bajo una carga intesiva o un alto volumen de transacciones. Durante las pruebas de estrés, se somete al sistema a condiciones de carga máxima o más allá de lo límites normales de uso. Esto se hace para identificar posibles problemas de rendimiento, estabilidad, resistencia y recuperación en situaciones extremas.

Algunas de las situaciones donde se puede aplicar la prueba son:

- Carga máxima: Se simula el máximo volumen de usuarios o solicitudes concurrentes que se espera que el sistema pueda manejar. Se evalúa cómo el sistema se comporta y si puede mantener su rendimiento y estabilidad bajo esa carga extrema.

- Sobrecarga de datos: Se evalúa cómo el sistema maneja grandes volúmenes de datos, como bases de datos masivas o archivos de gran tamaño. Se busca identificar posibles problemas de rendimiento o capacidad.

- Carga sostenida: Se somete al sistema a una carga constante y sostenida durante un período prolongado de tiempo. Esto permite evaluar la resistencia del sistema y su capacidad para mantener un rendimiento estable a largo plazo.

- Picos de carga: Se simulan situaciones en las ue se produce un aunmento repentino y significativo de usuarios o tráfico en el sistema. Se evalúa cómo el sistema responde y si puede manejar eficientemente el aumento repentino de la carga.

Durante estas sistuaciones, se suele monitorear y analiza cada comportamiento que el sistema pueda llegar a hacer. Derviado de esto los beneficios que tenemos es la mejora de la cofianza del sistema y asu vez la validación de los límites del sistema.

5. **Pruebas de regresión**

> "Tiene como objetivo comprobar que los cambios en un componente del software no provocan reacciones no deseadas" (Viva UNIR, 2022)

Cuando se realizan cambios en el software, como la adición de nuevas características, la corección de errores o la optimización del código, existe el riesgo de que esos cambios afecten negativamente a otras partes del sistema que antes funcionaban correctamente. Las pruebas de regresión se llevan a cabo para mitigar este riesgo y asegurar que las funcionalidades existentes no se vean afectadas por los cambios realizados.

Asi que derivado de lo anterior, algunos aspectos clave en las pruebas de regresión son:

- Selección de casos de pruebas: Se seleccionan casos de prueba relevantes que cubren las funcionalidades afectadas por los cambios recientes y las áreas relacionadas.

- Ejecución repetida de pruebas: Los casos de prueba seleccionados se vuelven a ejecutar para verificar si siguen produciendo los resultados esperados después de los cambios. 

- Automatización de pruebas: Para agilizar el proceso de pruebas de regresion, se puede utilizar la automatización de pruebas. Esto implica desarrollar scripts o programas que ejecuten automáticamente los casos de prueba seleccionados y verifiquen los resultados.

- Identificación y resolución de regresiones: Si se detectan nuevos errores o regresiones durate las pruebas de regresión, se deben documentar y solucionar adecuadamente. 

Por consiguiente, los beneficios obtenidos de la prueba serían un mantemiento de la calidad del software y detección de problemas.

6. **Pruebas de humo**

