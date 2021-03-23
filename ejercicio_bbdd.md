# Ejercicio sobre bases de datos. Construye una base de datos a partir de un texto descriptivo.


> + **_Versión_**: 2020-2021
> + **_Asignatura (titulación)_**: Ciclo de gestión del dato: ecoinformática (máster conservación, gestión y restauración de la biodiversidad. UGR). Curso 2020-2021
> + **_Autor_**: Curro Bonet-García (fjbonet@uco.es)



## Objetivos del ejercicio

Esta actividad tiene el siguiente objetivo de aprendizaje:

Trasladar el conocimiento adquirido sobre la construcción de bases de datos a un caso de estudio concreto y real. Esto permitirá entrenar dichos conocimientos y contribuirá a que se afiancen en vuestra memoria a largo plazo. 

## Tareas a realizar

Lee atentamente el siguiente texto:

Imagina que te contratan para trabajar en la Red de Información Ambiental de Andalucía para construir una base de datos que permita almacenar información sobre un mapa de vegetación. Dicho mapa consta de dos metodologías complementarias, cada una de las cuales tiene una componente geográfica y otra alfanumérica. Son las siguientes:

+ Fotointerpretación de la vegetación: Consiste en identificar manchas de vegetación homogéneas para una serie de variables estructurales (cobertura del estrato arbóreo, arbustivo, herbáceo, porcentaje de suelo desnudo y formación vegetal). Cada fotointérprete va dibujando polígonos en un SIG y les va asignando los valores de las variables anteriores. El parámetro de densidad se estima con rangos numéricos (Ausente, 1-25%, 26-50%, 51-75% y 76-100%). La formación vegetal se obtiene de una lista de formaciones vegetales de Andalucía. También se registra el nombre de la persona que delimita cada polígono. La escala de trabajo es 1:10.000.

+ Muestreos fitosociológicos: En virtud de la caracterización espacial obtenida anteriormente, se diseña un trabajo de campo que consiste en hacer muestreos fitosociológicos en una serie de puntos del territorio. En cada muestreo (caracterizado por un punto), se evalúan la presencia y abundancia de todas las especies vegetales existentes en un radio de xx m desde el centro de la parcela. La presencia de las especies se registra a través de un listado de taxones de Andalucía. Su abundancia se codifica según el criterio de Braun-Blanquet (búscalo en internet si no sabes lo que es). Cada muestreo es realizado por un equipo de personas cuyo número es variable. También es importante tener en cuenta que cada punto puede ser visitado en varias ocasiones. 

Ahora deberás hacer lo siguiente:
1. Construye un diagrama entidad-relación a partir de cada uno de los casos descritos más abajo. Identifica las entidades y los atributos importantes. Puedes poner los dos casos descritos en el mismo esquema o en dos difrentes. 
2. Traduce el o los diagramas entidad-relación en una o dos estructuras de bases de datos relacionales, con sus tablas y campos. 

## Evaluación
En la siguiente tabla podéis ver los criterios que se usarán para evaluar este ejercicio. Dicha rúbrica está basada en los pasos que hemos dado para construir la base de datos:

1. Identificación de entidades, atributos de la realidad que queremos modelar, así como las relaciones entre los mismos.
2. Traducción de los elementos anteriores a una estructura interpretable por un gestor de bases de datos relacionales: tablas, campos, relaciones.


<div style="page-break-after: always; break-after: page;"></div>

| Completitud de las entidades y sus atributos                 |             |                                                              |                                                              |                                                              |                                                              |                                                              |
| ------------------------------------------------------------ | ----------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Se evalúa en qué medida has identificado bien las entidades contempladas en el texto descriptivo, así como sus correspondientes atributos. |             |                                                              |                                                              |                                                              |                                                              |                                                              |
|                                                              | 0.0         | 1.0                                                          | 2.0                                                          | 3.0                                                          | 4.0                                                          | 5.0                                                          |
|                                                              | No entrega  | No identificación de variables ni de atributos               | Mezcla de atributos con entidades                            | Correcta identificación de ambos conceptos                   | Identificación completa de atributos y entidades             | Incorporas conceptos y/o atributos que mejoran la base de datos |
|                                                              |             | No has identificado correctamente ni los atributos ni las entidades. | Has mezclado ambos conceptos                                 | Has diferenciado bien entre entidades y atributos, pero faltan alguno de cualquiera de ellos. | Están todos los atributos y entidades.                       | Además de considerar todos los conceptos y atributos del enunciado, lo has mejorado. |
| **Completitud de las relaciones entre entidades**            |             |                                                              |                                                              |                                                              |                                                              |                                                              |
| Se evalúa en qué medida has identificado bien las relaciones entre entidades. |             |                                                              |                                                              |                                                              |                                                              |                                                              |
|                                                              | 0.0         | 1.0                                                          | 2.0                                                          | 3.0                                                          | 4.0                                                          | 5.0                                                          |
|                                                              | No entrega  | No has identificado correctamente ninguna relación.          | Faltan muchas relaciones                                     | Correcta identificación de relaciones                        | Identificación completa de relaciones                        | Incorporas nuevas relaciones que mejoran la base de datos.   |
|                                                              |             |                                                              | Has incluído alguna relación, pero faltan muchas.            | Has identificado adecuadamente la mayoría de las relaciones. | Están todas las relaciones y su cardinalidad es correcta.    |                                                              |
| **Traducción del modelo entidad relación a un diagrama de bases de datos** |             |                                                              |                                                              |                                                              |                                                              |                                                              |
| Se evalúa en qué medida has traducido el esquema de entidades-relaciones a un diagrama de tablas en una base de datos. |             |                                                              |                                                              |                                                              |                                                              |                                                              |
|                                                              | 0.0         | 1.0                                                          | 2.0                                                          | 3.0                                                          | 4.0                                                          | 5.0                                                          |
|                                                              | No entrega. | Muy incompleta traducción de entidades/atributos a tablas/campos | Incompleta asignación de entidades/atributos a tablas/campos | Correcta traducción de entidades/atributos a tablas/campos   | Traducción completa                                          | Incorporas nuevas tablas y campos que mejoran la estructura. |
|                                                              |             |                                                              | Has traducido bien algunos elementos, pero faltan muchos.    | Están realizadas correctamente casi todas las asignaciones entidad/atributo a tabla/campo. | Todas las entidades y sus atributos han sido traducidos a tablas y a campos. |                                                              |





La evaluación de este ejercicio se realizará siguiendo las siguientes fases, que se basan en la idea de re-evaluación y análisis en grupo de resultados.



+ **Primera entrega**: Los alumnos entregan el ejercicio solicitado usando el conocimiento adquirido en las sesiones teóricas.
+ **Sesión de evaluación conjunta del ejercicio:** El profesor realiza el ejercicio junto con los alumnos. Definimos una estructura de datos que sea compatible con el enunciado del ejercicio. El siguiente diagrama muestra el resultado obtenido. También se puede descargar aquí en formato .drawio. Además, en el siguiente vídeo se muestra la sesión de trabajo conjunto.









+ **Segunda ronda de evaluación:** Los alumnos rehacen el ejercicio teniendo en cuenta el nuevo conocimiento adquirido. La calificación se obtiene a partir de esta segunda entrega.