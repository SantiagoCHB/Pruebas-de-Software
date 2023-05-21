# Pruebas-de-Software

## Tabla de contenidos

- [¿Qué son las Pruebas de Software?](#qué-son-las-pruebas-de-software)

## [¿Qué son las Pruebas de Software?](#qué-son-las-pruebas-de-software)

> "Son el mejor método para confirmar la funcionalidad del producto que se esta desarrollando"(Vive UNIR, 2022).
>
En otras palabras, las pruebas son un proceso de instrospeccón que se realiza en un proyecto de software,todo esto con el fin de descrubrir fallos o errores no vistos en el momento.
Principalmente porque, "lo que se lleva a cabo durante estas pruebas es una evaluación minuciosa para verificar la funcionalidad de un determinado producto" (Vive UNIR, 2022).
Por ende, el beneficio de esta evaluación es comprobar que todo funcione tal y como debe, ayudando a cerrar el margen de error en temprana fases del desarrollo. Esto no quiere decir que solo se puedan realizar en estas fases, ya que estas pruebas pueden llevarse a cabo en diferentes etapas del ciclo de vida del desarrollo de software.

### **Tipos de Pruebas de Software**

Dentro de estas evaluaciones, "existen diversos tipos, donde cada uno se caracteriza por poseer sus propias particularidades y, por lo tanto, aplicaciones distintas"(uniR, 2022). A continuación los tipos:

#### 1. **Pruebas unitarias o _until testing_**

> "Comprueban que cada una de las piezas o unidades más pequeñas del software en el que se está trabajando funcione correctamente" (Viva UNIR, 2022)

El objetivo prinicipal de las pruebas unitarias es veirficar que cada unidad de código funcione correctamente de manera individual y aislada, de acuerdo con las especificaciones y los requisitos establecidos. Al momento de realizar estas pruebas unitarias, se busca identificar cualquier error o defecto en la lógica o el comportamiento de una unidad en particular.

Las pruebas unitarias por lo generalmente se desarrollan por los propios desarrolladores y se llevan a cabo en un entorno controlado.

Entre sus ventajas y beneficios encontramos el aislamiento del código o la detección temprana de errores. Asimismo "está el ahorro de tiempo y de dinero, ya que permiten detectar errores al principio y evitar seguir avanzando arrastrando ese fallo que va a condicionar el resto del proyecto" (Viva UNIR, 2022).

#### 2. **Pruebas de integración**

>"el objetivo de estas pruebas es comprobar que los difernetes componentes operan bien juntos" (Viva UNIR, 2022)

En otras palabras, estas se enfocan en evaluar la correcta interacción y comunicación entre los diferentes componentes o unidades de código que se han integrado en un sistema o aplicación. El obejtivo principal de las pruebas de integración es identificar problemas o errores que puedan surgir cuando las diferentes partes del software interactuen entre si.

Estas pruebas de integración se realizan despues de las pruebas unitarias y antes de las pruebas de sistemas. Algunos enfoques comunes son:

- Pruebas de integración ascendente (bottom-up): Comienza probando las unidades más pequeñas o los componentes indivuales y luego avanza hacia niveles superiores de integración.

- Pruebas de integración descendente (top-down): Comienza probando los componentes más altos o de nivel superior y luego se avanza hacia niveles inferiores de integración

- Pruebas de integración combinadas (sandwich): Combina enfoques ascendentes y descendentes, realizando pruebas de integración en diferentes niveles y direcciones para asegurar una cobertura exhaustiva.

Asimismo, algunos de los benificios de las pruebas de integración son la detección temprana de problemas de interoperabilidad o la verificación de la funcionalidad completa del sistema.

#### 3. **Pruebas de rendimiento**

> "Se trata de chequear la respuesta del software ante cargas de trabajos diferentes y en condiciones reales." (Viva UNIR, 2022)

En concreto, el objetivo principal de las pruebas de rendimiento es medir y analizar el rendimiento, la velocidad, la estabilidad y la escabilidad del software. Estas pruebas se llevan a cabo para simular situaciones de uso realistas y determinar cómo responde el software ante un alto volumen de usuarios, una gran cantidad de datos o una carga intensiva. Al realizar pruebas de rendiiento, se busca identificar posibles cuellos de botella, puntos de estrangulamiento o en general debilidades del sistema.

Por ende, algunos aspectos que se suelen evaluar son: tiempo de respuesta, escalabilidad, estabilidad, uso de recursos, resistencia al estrés, entre otros. Gracias a esto, los beneficios que traen estas pruebas son la identificación de cuellos de botellas y puntos debiles, y mejora de la experiencia del usuario.

#### 4. **Pruebas de estrés**

> "es necesario comprobar cuánta tensión puede soportar el sistema antes de que se produzca algún error" (Viva UNIR, 2022)

Su funcion es determinar el punto de quiebre o límite del sistemas y observar cómo se comporta bajo una carga intesiva o un alto volumen de transacciones. Durante las pruebas de estrés, se somete al sistema a condiciones de carga máxima o más allá de lo límites normales de uso. Esto se hace para identificar posibles problemas de rendimiento, estabilidad, resistencia y recuperación en situaciones extremas.

Algunas de las situaciones donde se puede aplicar la prueba son:

- Carga máxima: Se simula el máximo volumen de usuarios o solicitudes concurrentes que se espera que el sistema pueda manejar. Se evalúa cómo el sistema se comporta y si puede mantener su rendimiento y estabilidad bajo esa carga extrema.

- Sobrecarga de datos: Se evalúa cómo el sistema maneja grandes volúmenes de datos, como bases de datos masivas o archivos de gran tamaño. Se busca identificar posibles problemas de rendimiento o capacidad.

- Carga sostenida: Se somete al sistema a una carga constante y sostenida durante un período prolongado de tiempo. Esto permite evaluar la resistencia del sistema y su capacidad para mantener un rendimiento estable a largo plazo.

- Picos de carga: Se simulan situaciones en las ue se produce un aunmento repentino y significativo de usuarios o tráfico en el sistema. Se evalúa cómo el sistema responde y si puede manejar eficientemente el aumento repentino de la carga.

Durante estas sistuaciones, se suele monitorear y analiza cada comportamiento que el sistema pueda llegar a hacer. Derviado de esto los beneficios que tenemos es la mejora de la cofianza del sistema y asu vez la validación de los límites del sistema.

#### 5. **Pruebas de regresión**

> "Tiene como objetivo comprobar que los cambios en un componente del software no provocan reacciones no deseadas" (Viva UNIR, 2022)

Cuando se realizan cambios en el software, como la adición de nuevas características, la corección de errores o la optimización del código, existe el riesgo de que esos cambios afecten negativamente a otras partes del sistema que antes funcionaban correctamente. Las pruebas de regresión se llevan a cabo para mitigar este riesgo y asegurar que las funcionalidades existentes no se vean afectadas por los cambios realizados.

Asi que derivado de lo anterior, algunos aspectos clave en las pruebas de regresión son:

- Selección de casos de pruebas: Se seleccionan casos de prueba relevantes que cubren las funcionalidades afectadas por los cambios recientes y las áreas relacionadas.

- Ejecución repetida de pruebas: Los casos de prueba seleccionados se vuelven a ejecutar para verificar si siguen produciendo los resultados esperados después de los cambios. 

- Automatización de pruebas: Para agilizar el proceso de pruebas de regresion, se puede utilizar la automatización de pruebas. Esto implica desarrollar scripts o programas que ejecuten automáticamente los casos de prueba seleccionados y verifiquen los resultados.

- Identificación y resolución de regresiones: Si se detectan nuevos errores o regresiones durate las pruebas de regresión, se deben documentar y solucionar adecuadamente. 

Por consiguiente, los beneficios obtenidos de la prueba serían un mantemiento de la calidad del software y detección de problemas.

#### 6. **Pruebas de humo**

> "Ayudan a determinar si el conjunto del software funciona bien y si esta preparado para ser sometido a pruebas más exhaustivas" (Viva UNIR, 2022)

Su objetivo principal es identificar problemas graves o errores evidentes que peudan impedir que el software funcione correctamente. Se denominan asi; "humo" porque se asemejan a encender un dispositivo y veirficar si sale humo. Al igual que en ese escenario, las pruebas de humo buscan detectar problemas obvio antes de profundizar en pruebas más detalladas.

Durante las pruebas de humo, se ejecutan casos de prueba básicos y sencillos que cubren las funcionalidades principales y críticas del software. Estas pruebas suelen ser rápidas y no implican una cobertura exhaustiva de todas las caracteristicas o casos de uso posibles.

Los beneificos que pueden llegar a traer estas pruebas de humo son realmente utiles, como lo pueden ser detección temprana de problemas graves que puedan atentar al sistemas más adelante, ahorro de tiempo y recursos y garantía mínima de estabilidad.

En rasgos generales, esos son los tipos más conocidos y usado de pruebas de software; sin embargo, existen varios tipos más, cada uno dependiendo de sus aspectos específicos del sistema y a la par sus objetivos particulares.

Por nombrar algunos tenemos:

#### 7. **Pruebas de sistema**
#### 8. **Pruebas de aceptación**
#### 9. **Pruebas de seguridad**
#### 10. **Pruebas de usabilidad**
#### 11. **Pruebas de compatibilidad**
#### 12. **Pruebas de localización.


## **¿Qué son los Patrones de desarrolllo GOF?**

> "El objetivo de los patrones es facilitar la reutilización de diseños y arquitecturas software que han tenido éxito capturando la experiencia y haciéndola accesible a los no expertos." (Gracia, 2013)

Los patrones de desarrollo GoF o por sus siglas en ingles (Gang of Four) ofrecen soluciones probadas y comunes para problemas recurrentes en el diseño de software orientado a objetos (POO).

>Según menciona Gracia (2013), estos patrones fueron documentos y estudiados por Erich Ganma, Richard Helm, Ralph Johnson y John Vlissides en su mítico libro Design Patterns

Estos patrones se clasifican en tres categorías:

### 1. **Patrones de creación**: 

Estos patrones se centran en la creación de objetos de manera flexible y eficiente. Algunos ejemplos de patrones de creación incluyen el patrón Singleton, que garantiza la existencia d euna única instancia de una clase, y el patrón Factory Method, que delega la creación de objetos a subclases.

### 2. **Patrones de estructura**: 

Estos patrones se enfocan en la composición y estructuración de clases y objetos. Ejemplos de patrones de estructura incluyen el patrón Adapter, que permite la interoperabilidad entre interfaces incompatibles, y el patrón Composite, que permite tratar objetos individuales y colecciones de objetos de manera uniforme.

### 3. **Patrones de comportamiento**: 

Estos patrones se centran en el comportamiento y la comunicación entre objetos. Algunos ejemplos de patrones de comportamiento incluyen el patrón Observer, que define una relación uno a muchos entre objetos, y el patrón Strategy, que permite encapsular algoritmos y cambiarlos dinámicamente.

Los patrones de desarrollo GoF proporcionan un vocabulario común y una guía para el diseño de software orientado a objetos, lo que facilita la comunicación y el entendimiento entre desarrolladores. Estos patrones no son soluciones universales para todos los problemas de diseño, pero ofrecen enfoques probados y comunes que pueden mejorar la flexibilidad, reutilización y mantenibilidad del software.



## **Referencias**
- Un poco de Patrones de Diseño GoF, (Gang of Four). Lusimi Gracias (2013, January 2). Un Poco de Java; Un poco de Java. 
https://unpocodejava.com/2013/01/02/un-poco-de-patrones-de-diseno-gof-gang-of-four/

- Vive UNIR. (2022, August 26). La importancia de las pruebas de software. UNIR; UNIR. 
https://www.unir.net/ingenieria/revista/pruebas-software/

‌

‌
