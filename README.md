# Alternativas a la Persistencia Relacional

Work in Progress: slides del curso de Base de Datos 2 que dicto en la [Universidad Nacional de Río Negro](http://sedeatlantica.unrn.edu.ar/).

## Contenidos
1. **Persistencia Orientada a Objetos**: Conceptos fundacionales: Persistencia por Alcance y Persistencia Transparente. Bases de Datos Orientadas a Objetos (OODBMS): DB4O/[ZooDB](https://github.com/tzaeschke/zoodb).
ORM: Object Relational Mapping. Persistencia en Objetos contra una Base de Datos Relacional. Conceptos e implementación. Java, Hibernate, JPA.
2. **NoSQL**: ¿Qué motivó su aparición?. Consistencia. Teorema de CAP y Conceptos Básicos de Arquitecturas Distribuídas. Escalar en Bases de Datos Relacionales y en Base de Datos NoSQL. Arquitecturas Master-Slave. Sharding.
3. **Familias de BDs NoSQL**: Conceptos sobre almacenamiento de tipo Clave-Valor (Redis), Documento (MongoDB), Familia de Columnas (Cassandra) y Grafos (Neo4J / Gremlin). Usos adecuados de cada uno. Comparación con usos adecuados de bases de datos relacionales.
## Running 
Se recomienda clonar, instalar e iniciar para ver las teóricas. Hay algunas animaciones que en los PDFs no se ven:
1. Clonar el proyecto
2. npm install
3. npm start
## Notas
1. La relación frecuenta-gusta-sirve de los ejericios del trabajo práctico sobre bases de datos de grafos fue obtenida del libro [Introducción a las Bases de Datos Relacionales (Mendelzon, Ale)](https://www.researchgate.net/publication/31710071_Introduccion_a_las_bases_de_datos_relacionales_A_Mendelzon_J_Ale). En este libro se requiere resolver los ejercicios con álgebra relacional. Aquí con el lenguaje gremlin. 
2. Los contenidos de este curso estan desarrollados utiliando el hermoso framework [Reveal.JS](http://revealjs.com).
