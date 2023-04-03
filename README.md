# BasesDatos
## 1) Introducción a bases de datos relacionales:
    1.1 Entidades y Atributos:
    1.1.1 Entidades: Es una cosa u objeto distinguible de otros objetos, este tiene un conjunto de propiedades o atributos que lo caracterizan.
    1.1.2 Atributos: Son las características o propiedades de una entidad.
    
    1.2 Relaciones:
    1.2.1 Cardinalidad 1 a 1.
    1.2.2 Cardinalidad 0 a 1.
    1.2.3 Cardinalidad 1 a N.
    1.2.4 Cardinalidad 0 a N.
    1.2.5 Cardinalidad N a N.

    1.3 Normalización de la base de datos:
    1FN: No debemos tener atributos repetidos 
    2FN: Se cumple 1FN y cada campo de la tabla debe depender de una clave única.
    3FN: Cumple 1FN y 2FN y los campos que no son clave no deben tener dependencias.
    4FN: Cumple 1FN, 2FN y 3FN y los campos multivaluados se identifican por una clave única.