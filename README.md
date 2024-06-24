# T2-PDDM
## Instrucciones para correr el notebook
Para correr el notebook se necesita:

Tener instalado Pyspark (O en su defecto hacer la ejecución en google collab)

!pip install pyspark

En el caso de arrancarlo localmente es necesario tener Java, o bien crear un contenedor Docker.


## Instrucciones para correr el notebook de Neo4j local.

Para correr el notebook de neo4j se necesita tener una cuenta en Neo4j, y luego se debe crear a nivel local
una instancia de servidor, el se aloja generalmente en el puerto 7687.

Para poder conectarse desde pyspark a dicho servidor, también es necesario contar con el usuario y contraseña de la cuenta de Pyspark.

Una vez procesadas ambas informaciones en un Builder de pyspark, es posible generar una rdd con la base de datos en Neo4j.


## Bibliografía utilizada

1. Apuntes de clases sobre Pyspark. Disponibles en: https://github.com/IIC2440/Syllabus-2024-1/tree/main/Slides%20y%20otros/Clase%2009%20-%20Notebooks%20Map%20Reduce
2. Apuntes de clases sobre Neo4j. Disponibles en: https://github.com/IIC2440/Syllabus-2024-1/tree/main/Actividades/06%20-%20Grafos
2. GPT-4 - OpenAI (Más que nada para optimizar el código de los cuadrados y para formular consultas de Neo4j)