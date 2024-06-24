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