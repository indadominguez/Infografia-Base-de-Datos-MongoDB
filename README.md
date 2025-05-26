# Infografia-Base-de-Datos-MongoDB

Para poder terminar el curso de manera adecuada y viendo todos los temas de la planificación, voy a realizar una Infografía sobre MongoDB y sus diferentes contenidos.

### Indice
Índice de contenidos

**1 Introducción a MongoDB**
  * 1.1 ¿Qué es MongoDB? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 5
  * 1.2 Características principales . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 5
  * 1.3 Comparación con bases de datos relacionales . . . . . . . . . . . . . . . . . . . . . . . 6



**2 Documentos y Colecciones**
* 2.1 Definición de Documento . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 6
* 2.2 Estructura de los Documentos (JSON/BSON) . . . . . . . . . . . . . . . . . . . . . . . 7
* 2.3 Definición de Colección . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 7
* 2.4 Diferencias entre Documentos y Filas en SQL . . . . . . . . . . . . . . . . . . . . . . . 8



**3 Bases de Datos en MongoDB**
* 3.1 Creación y Uso de Bases de Datos . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 8
* 3.1.1 1. Crear o Seleccionar una Base de Datos . . . . . . . . . . . . . . . . . . . . . 8
* 3.1.2 2. Listar Bases de Datos Existentes . . . . . . . . . . . . . . . . . . . . . . . . 9
* 3.1.3 3. Eliminar una Base de Datos . . . . . . . . . . . . . . . . . . . . . . . . . . . 9
* 3.2 Manejo de Bases de Datos en MongoDB . . . . . . . . . . . . . . . . . . . . . . . . . 10
* 3.2.1 1. Cambiar entre Bases de Datos . . . . . . . . . . . . . . . . . . . . . . . . . . 10
* 3.2.2 2. Información sobre la Base de Datos Actual . . . . . . . . . . . . . . . . . . 10
* 3.2.3 3. Copiar una Base de Datos . . . . . . . . . . . . . . . . . . . . . . . . . . . . 10
* 3.3 Buenas Prácticas al Trabajar con Bases de Datos . . . . . . . . . . . . . . . . . . . . . 11
* 3.4 Con esto concluimos la sección sobre Bases de Datos en MongoDB. . . . . . . . . . . 11



**4. CRUD en MongoDB** 
* 4.1 1. Crear (Create) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 11
* 4.1.1 Insertar un Documento: insertOne() . . . . . . . . . . . . . . . . . . . . . 11
* 4.1.2 Insertar Múltiples Documentos: insertMany() . . . . . . . . . . . . . . . . 12
* 4.2 2. Leer (Read) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 12
* 4.2.1 Consultar Todos los Documentos: find() . . . . . . . . . . . . . . . . . . . . 13
* 4.2.2 Consultar con Filtros: find({ filtro }) . . . . . . . . . . . . . . . . . . . 13
* 4.2.3 Proyección de Campos: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 13
* 4.3 3. Actualizar (Update) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 14
* 4.3.1 Actualizar un Documento: updateOne() . . . . . . . . . . . . . . . . . . . . 14
* 4.3.2 Actualizar Múltiples Documentos: updateMany() . . . . . . . . . . . . . . 14
* 4.4 4. Borrar (Delete) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 14
* 4.4.1 Borrar un Documento: deleteOne() . . . . . . . . . . . . . . . . . . . . . . 15
* 4.4.2 Borrar Múltiples Documentos: deleteMany() . . . . . . . . . . . . . . . . . 15



**5 Consultas en MongoDB** 
* 5.1 1. Consultas Básicas con find() . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15
* 5.1.1 Sintaxis General: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15
* 5.1.2 Ejemplo Básico: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15
* 5.2 2. Consultas con Filtros . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 16
* 5.2.1 Operadores de Comparación Comunes: . . . . . . . . . . . . . . . . . . . . . 16
* 5.2.2 Ejemplos de Consultas con Filtros: . . . . . . . . . . . . . . . . . . . . . . . . 16
* 5.3 3. Consultas con Proyecciones . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 16
* 5.3.1 Incluir o Excluir Campos: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 17
* 5.4 4. Consultas con Operadores Lógicos . . . . . . . . . . . . . . . . . . . . . . . . . . . 17
* 5.4.1 Operadores Lógicos Comunes: . . . . . . . . . . . . . . . . . . . . . . . . . . . 17
* 5.4.2 Ejemplos de Consultas con Operadores Lógicos: . . . . . . . . . . . . . . . . 17
* 5.5 5. Consultas con Operadores de Arreglos . . . . . . . . . . . . . . . . . . . . . . . . . 18
* 5.5.1 Operadores Comunes para Arreglos: . . . . . . . . . . . . . . . . . . . . . . . 18
* 5.5.2 Ejemplos de Consultas con Arreglos: . . . . . . . . . . . . . . . . . . . . . . . 18
* 5.6 6. Ordenar y Limitar Resultados . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 18
* 5.6.1 Ordenar Resultados: sort() . . . . . . . . . . . . . . . . . . . . . . . . . . . 18
* 5.6.2 Limitar el Número de Resultados: limit() . . . . . . . . . . . . . . . . . . . 19
* 5.7 Conclusión . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 19



**6 Índices en MongoDB** 
* 6.1 1. ¿Qué son los índices? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 19
* 6.1.1 Ventajas de usar índices: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 19
* 6.1.2 Desventajas o costos: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 20
* 6.2 2. Tipos de Índices en MongoDB . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 20
* 6.2.1 Índice Único . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 20
* 6.2.2 Índice Simple . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 20
* 6.2.3 Índice Compuesto . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 20
* 6.2.4 Índice de Texto . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 20
* 6.2.5 Índice Geoespacial . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 21
* 6.3 3. Crear, Ver y Eliminar Índices . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 21
* 6.3.1 Crear un Índice: createIndex() . . . . . . . . . . . . . . . . . . . . . . . . . 21
* 6.3.2 Ver Índices: getIndexes() . . . . . . . . . . . . . . . . . . . . . . . . . . . . 21
* 6.3.3 Eliminar un Índice: dropIndex() . . . . . . . . . . . . . . . . . . . . . . . . 22
* 6.4 4. Casos de Uso y Buenas Prácticas para Índices . . . . . . . . . . . . . . . . . . . . . 22
* 6.4.1 ¿Cuándo crear índices? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 22
* 6.4.2 Buenas Prácticas al Crear Índices: . . . . . . . . . . . . . . . . . . . . . . . . . 22
* 6.5 5. Uso de explain() para Optimización . . . . . . . . . . . . . . . . . . . . . . . . . 22
* 6.5.1 Sintaxis de explain(): . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 23
* 6.5.2 Ejemplo: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 23
* 6.6 Conclusión . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 23



**7 Agregaciones en MongoDB** 
* 7.1 ¿Qué es el Aggregation Framework? . . . . . . . . . . . . . . . . . . . . . . . . . . . . 23
* 7.2 Etapas Comunes en el Aggregation Framework . . . . . . . . . . . . . . . . . . . . . 23
* 7.2.1 $match: Filtrar Documentos . . . . . . . . . . . . . . . . . . . . . . . . . . . . 24
* 7.2.2 $group: Agrupar Documentos . . . . . . . . . . . . . . . . . . . . . . . . . . . 24
* 7.2.3 $project: Seleccionar y Transformar Campos . . . . . . . . . . . . . . . . . . 24
* 7.2.4 $sort: Ordenar los Resultados . . . . . . . . . . . . . . . . . . . . . . . . . . . 24
* 7.2.5 $limit: Limitar el Número de Resultados . . . . . . . . . . . . . . . . . . . . . 25
* 7.2.6 $unwind: Descomponer Arreglos . . . . . . . . . . . . . . . . . . . . . . . . . 25
* 7.3 3. Combinando Etapas en un Pipeline . . . . . . . . . . . . . . . . . . . . . . . . . . 25
* 7.4 4. Expresiones de Agregación Comunes . . . . . . . . . . . . . . . . . . . . . . . . . 25
* 7.4.1 Operadores Matemáticos: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 26
* 7.4.2 Operadores de Comparación: . . . . . . . . . . . . . . . . . . . . . . . . . . . 26
* 7.4.3 Operadores de Arreglos: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 26
* 7.5 5. Uso de explain() para Optimización . . . . . . . . . . . . . . . . . . . . . . . . . 26
* 7.6 6. Agregaciones con MapReduce . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 27
* 7.7 Conclusión . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 27



**8 Replicación y Alta Disponibilidad en MongoDB** 
* 8.1 ¿Qué es la Replicación en MongoDB? . . . . . . . . . . . . . . . . . . . . . . . . . . . 27
* 8.2 2. Componentes de un Replica Set . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 28
* 8.2.1 1. Nodo Primario (Primary Node) . . . . . . . . . . . . . . . . . . . . . . . . . 28
* 8.2.2 2. Nodo Secundario (Secondary Node) . . . . . . . . . . . . . . . . . . . . . . 28
* 8.2.3 3. Árbitro (Arbiter) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 28
* 8.3 3. Configuración de un Replica Set . . . . . . . . . . . . . . . . . . . . . . . . . . . . 28
* 8.3.1 1. Iniciar MongoDB en Modo Replica Set . . . . . . . . . . . . . . . . . . . . 29
* 8.3.2 2. Iniciar el Replica Set . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 29
* 8.3.3 3. Ver el Estado del Replica Set . . . . . . . . . . . . . . . . . . . . . . . . . . 29
* 8.4 4. Proceso de Elección . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 30
* 8.4.1 Causas para una Elección: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 30
* 8.5 5. Escalabilidad de Lectura con Nodos Secundarios . . . . . . . . . . . . . . . . . . . 30
* 8.5.1 Permitir Lecturas en los Secundarios: . . . . . . . . . . . . . . . . . . . . . . . 30
* 8.6 6. Ventajas y Desventajas de la Replicación en MongoDB . . . . . . . . . . . . . . . 31
* 8.6.1 Ventajas: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 31
* 8.6.2 Desventajas: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 31
* 8.7 7. Consideraciones sobre la Consistencia . . . . . . . . . . . . . . . . . . . . . . . . . 31
* 8.8 Conclusión . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 31



**9. Sharding en MongoDB**
* 9.1 1. ¿Qué es el Sharding? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 32
* 9.2 2. Componentes del Sharding en MongoDB . . . . . . . . . . . . . . . . . . . . . . . 32
* 9.2.1 1. Shards . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 32
* 9.2.2 2. Router de Consultas (mongos) . . . . . . . . . . . . . . . . . . . . . . . . . 32
* 9.2.3 3. Config Servers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 32
* 9.2.4 3. Proceso de Sharding . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 33
* 9.2.5 4. Configuración del Sharding . . . . . . . . . . . . . . . . . . . . . . . . . . . 33
* 9.2.6 5. Tipos de Sharding en MongoDB . . . . . . . . . . . . . . . . . . . . . . . . 34
* 9.2.7 6. Balanceo de Fragmentos . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 34
* 9.2.8 7. Ventajas y Desventajas del Sharding . . . . . . . . . . . . . . . . . . . . . . 34
* 9.2.9 8. Escenarios para Usar Sharding . . . . . . . . . . . . . . . . . . . . . . . . . 35
* 9.3 Conclusión . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 35


   
**10 Seguridad en MongoDB** 
* 10.1 1. Autenticación en MongoDB . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 36
* 10.1.1 Tipos de Autenticación en MongoDB: . . . . . . . . . . . . . . . . . . . . . . . 36
* 10.2 2. Autorización en MongoDB . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 37
* 10.2.1 Tipos de Roles en MongoDB: . . . . . . . . . . . . . . . . . . . . . . . . . . . 37
* 10.3 3. Cifrado de Datos en MongoDB . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 38
* 10.3.1 1. Cifrado en tránsito (TLS/SSL) . . . . . . . . . . . . . . . . . . . . . . . . . . 38
* 10.3.2 2. Cifrado en reposo . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 38
* 10.4 4. Seguridad en la Red . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 38
* 10.4.1 1. Uso de Firewalls . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 39
* 10.4.2 2. Deshabilitar el Acceso Remoto a la Consola de Administración . . . . . . 39
* 10.4.3 3. Aislamiento de Redes (VPC) . . . . . . . . . . . . . . . . . . . . . . . . . . 39
* 10.5 5. Auditoría en MongoDB . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 39
* 10.6 6. Buenas Prácticas de Seguridad en MongoDB . . . . . . . . . . . . . . . . . . . . . 39
* 10.7 Conclusión . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 40



**11 Anexo 1: Documentos y Colecciones vs. Tablas y Filas**
* 11.0.1 Comparación de estructuras: . . . . . . . . . . . . . . . . . . . . . . . . . . . . 40



**12 Anexo 2: Bases de Datos en MongoDB vs. SQL**



**13 Anexo 3: Operaciones CRUD en MongoDB vs. SQL** 
* 13.1 Crear (Insertar Datos) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 41
* 13.1.1 SQL: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 41
* 13.1.2 MongoDB: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 42
* 13.2 Leer (Consultar Datos) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 42
* 13.2.1 SQL: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 42
* 13.2.2 MongoDB: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 42
* 13.3 Actualizar . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 42
* 13.3.1 SQL: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 42
* 13.3.2 MongoDB: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 42
* 13.4 Borrar . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 42
* 13.4.1 SQL: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 42
* 13.4.2 MongoDB: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 43



**14 Anexo 4: Consultas en MongoDB vs. SQL** 
* 14.1 Consultas avanzadas con operadores lógicos . . . . . . . . . . . . . . . . . . . . . . . 43
* 14.1.1 SQL: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 43
* 14.1.2 MongoDB: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 43



**15 Anexo 5: Índices en MongoDB vs. SQL** 
* 15.1 Índices compuestos . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 44
* 15.1.1 SQL: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 44
* 15.1.2 MongoDB: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 44



**16 Anexo 6: Agregaciones en MongoDB vs. SQL** 
* 16.1 Agrupaciones (GROUP BY en SQL) . . . . . . . . . . . . . . . . . . . . . . . . . . . . 44
* 16.1.1 SQL: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 44
* 16.1.2 MongoDB: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 44
* 6.2 Filtrar y agrupar (HAVING en SQL) . . . . . . . . . . . . . . . . . . . . . . . . . . . . 44
* 16.2.1 SQL: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 44
* 16.2.2 MongoDB: . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 45
* 16.3 Conclusión del Anexo . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 45

---

# Introducción a MongoDB

## 1.1 ¿Qué es MongoDB?
MongoDB es una base de datos **NoSQL orientada a documentos** que utiliza el formato **BSON** (una versión binaria de JSON) para almacenar los datos. Está diseñada para manejar grandes volúmenes de datos de forma **flexible y escalable**, siendo ideal para aplicaciones web, sistemas de análisis y microservicios.

## 1.2 Características principales
1. **Modelo basado en documentos**: Usa JSON con estructuras jerárquicas y flexibles.
2. **No relacional**: No requiere esquemas fijos ni tablas.
3. **Escalabilidad horizontal**: Distribuye datos en varios servidores (sharding).
4. **Alta disponibilidad**: Replicación automática entre servidores.
5. **Consultas flexibles**: Filtros, proyecciones y operadores avanzados.
6. **Transacciones**: Soporte para transacciones multi-documento desde MongoDB 4.0.
7. **Agregaciones y MapReduce**: Potente sistema de procesamiento de datos.
8. **Compatibilidad con múltiples lenguajes**: Drivers para Python, Java, Node.js, etc.

## 1.3 Comparación con bases de datos relacionales

| Característica       | MongoDB                           | Base de Datos Relacional            |
|----------------------|------------------------------------|-------------------------------------|
| Modelo de datos      | Documentos (JSON/BSON)             | Tablas (filas y columnas)           |
| Esquema              | Flexible                           | Rígido                              |
| Escalabilidad        | Horizontal (sharding)              | Vertical (aumento de hardware)      |
| Consultas            | JSON (`find()`, agregaciones)      | SQL (`SELECT`, `JOIN`)              |
| Transacciones        | Multi-documento                    | Completas                           |
| Relaciones           | Embebidas o referencias            | JOINs explícitos                    |
| Rendimiento          | Optimizado para velocidad          | Optimizado para consistencia        |

---

# Documentos y Colecciones

## 2.1 Documento
Un **documento** es una estructura de pares **campo-valor**, similar a JSON, almacenada como BSON. Puede contener datos anidados como subdocumentos o arreglos.

### Ejemplo de documento:
```json
{
  "nombre": "Laptop",
  "precio": 999.99,
  "cantidad": 15,
  "categoria": "Electrónica",
  "especificaciones": {
    "procesador": "Intel i7",
    "ram": "16GB",
    "almacenamiento": "512GB SSD"
  }
}
```
## 2.2 Estructura de los Documentos (JSON/BSON)

MongoDB almacena los documentos en formato **BSON** (Binary JSON), una versión binaria de JSON que permite una mayor eficiencia en el almacenamiento y acceso a los datos. Aunque las consultas e inserciones se realizan en formato JSON, MongoDB internamente los convierte a BSON.

### Tipos de datos admitidos en BSON:
- **String**: Cadenas de texto.
- **Number**: Números enteros y flotantes.
- **Boolean**: `true` o `false`.
- **Array**: Listas de valores.
- **Document**: Subdocumentos anidados.
- **Null**: Valor nulo.
- **Date**: Fechas y horas.
- **ObjectId**: Identificador único generado automáticamente.


## 2.3 Definición de Colección

Una **colección** en MongoDB es un conjunto de documentos agrupados lógicamente. A diferencia de una tabla en una base de datos relacional, una colección **no requiere una estructura fija**, lo que permite gran flexibilidad.

### Ejemplo de colección `productos`:
```json
[
  {
    "nombre": "Laptop",
    "precio": 999.99,
    "cantidad": 10,
    "categoria": "Electrónica"
  },
  {
    "nombre": "Mouse",
    "precio": 19.99,
    "cantidad": 50,
    "categoria": "Accesorios"
  },
  {
    "nombre": "Teclado",
    "precio": 49.99,
    "cantidad": 30,
    "categoria": "Accesorios"
  }
]
```

## 2.4 Diferencias entre Documentos y Filas en SQL

### Documentos en MongoDB:
- Estructura **flexible** que puede variar entre documentos.
- Permiten **datos anidados** (subdocumentos y arrays).
- Se almacenan como **BSON** (Binary JSON).
- Cada documento es **independiente** y puede tener su propia estructura.

### Filas en SQL:
- Estructura **fija** definida por un **esquema preestablecido**.
- **No permite** anidamiento de datos.
- Almacenadas como **filas** dentro de una tabla con columnas definidas.
- Todos los registros deben seguir el mismo formato.

### Comparación:

| Característica       | Documento en MongoDB               | Fila en SQL                         |
|----------------------|-------------------------------------|-------------------------------------|
| Esquema              | Flexible                            | Fijo (predefinido)                  |
| Datos anidados       | Permitido                           | No permitido                        |
| Almacenamiento       | BSON (Binary JSON)                  | Filas en tablas relacionales        |
| Modificación         | Afecta solo al documento modificado | Requiere alterar la estructura total|

MongoDB ofrece mayor flexibilidad para aplicaciones que necesitan trabajar con estructuras de datos dinámicas o cambiantes.

---

## 3. Bases de Datos en MongoDB

En MongoDB, las **bases de datos** son contenedores lógicos que agrupan **colecciones de documentos**. Una instancia de MongoDB puede manejar múltiples bases de datos, cada una con sus propias colecciones y documentos.

Esto permite organizar los datos de forma modular, ideal para aplicaciones con múltiples dominios o servicios.


### 3.1 Creación y Uso de Bases de Datos

A diferencia de las bases de datos relacionales, **MongoDB no requiere definir un esquema previamente** para crear una base de datos.

- **Creación implícita**: MongoDB **crea automáticamente una base de datos** cuando se inserta el primer documento en una colección de dicha base de datos.
- **Comando para seleccionar base de datos**:
  
  ```javascript
  use nombre_base_datos
  ```
### 3.2 Manejo de Bases de Datos en MongoDB

MongoDB organiza las bases de datos y colecciones de forma **flexible**, facilitando la gestión de datos en diferentes niveles. A continuación se presentan algunos comandos y aspectos clave para el manejo de bases de datos:

### 3.3 Buenas Prácticas al Trabajar con Bases de Datos

1. **Nombres de Bases de Datos**:
   - Utiliza **nombres descriptivos** y fáciles de entender.
   - Pueden incluir **letras**, **números** y **guiones bajos** (`_`), pero **no deben contener espacios** ni comenzar con números.
   - **Ejemplos válidos**: `clientes`, `ventas_2024`.

2. **Optimización de la Estructura**:
   - Aunque MongoDB permite una estructura flexible, es recomendable mantener **coherencia lógica** entre documentos.
   - Esto facilita las **consultas**, la **indexación** y el **mantenimiento** a largo plazo.

3. **Tamaño de la Base de Datos**:
   - Monitoriza regularmente el tamaño de tus bases de datos con:
     ```javascript
     db.stats()
     ```
   - Si detectas un crecimiento anormal, investiga qué colecciones están ocupando más espacio para **optimizar el almacenamiento**.


### 3.4 Conclusión

Con esto concluimos la sección sobre **Bases de Datos en MongoDB**. Hemos visto cómo se crean, gestionan y optimizan las bases de datos dentro de este sistema NoSQL, así como buenas prácticas para un uso eficiente y mantenible.

---

## 4. CRUD en MongoDB

En MongoDB, el concepto de **CRUD** representa las operaciones fundamentales que se pueden realizar sobre los datos:

- **C**reate (Crear)
- **R**ead (Leer)
- **U**pdate (Actualizar)
- **D**elete (Eliminar)

Estas operaciones permiten gestionar los documentos dentro de una colección. A continuación, se detalla cómo realizar cada una de ellas.


### 4.1 Crear (Create)

La operación de **crear** se refiere a insertar nuevos documentos en una colección.

MongoDB proporciona dos métodos principales:

#### 1. `insertOne()`
Inserta un único documento en una colección.

#### 2. `insertMany()`


### 4.2 Leer (Read)

La operación de **Leer** permite consultar y recuperar documentos almacenados en una colección.

El método más utilizado en MongoDB para realizar consultas es **`find()`**, el cual permite aplicar **filtros** y **proyecciones**.


### 4.3 Actualizar (Update)

La operación de **Actualizar** permite modificar documentos ya existentes en una colección.

MongoDB proporciona dos métodos principales para actualizar documentos:


### 4.4 Borrar (Delete)

La operación de **Borrar** elimina uno o más documentos de una colección.

MongoDB ofrece dos métodos principales para esta operación:

---

# 5 Consultas en MongoDB (Resumen)

MongoDB permite hacer consultas para filtrar y estructurar datos usando el método `find()` y otros operadores.

## 5.1 Consultas Básicas con `find()`

- `db.coleccion.find({filtro}, {proyección})`
- Sin filtro `{}`, devuelve todos los documentos.
- Sin proyección, devuelve todos los campos.

**Ejemplo:**

```js
db.productos.find()
```
## 5.2 Consultas con Filtros

Los filtros en MongoDB permiten buscar documentos que coincidan con criterios específicos. Los filtros se pasan como el primer argumento de `find()`.

### 5.2.1 Operadores de Comparación Comunes:

- `$eq`: Igual a.
- `$ne`: Diferente de.
- `$gt`: Mayor que.
- `$gte`: Mayor o igual que.
- `$lt`: Menor que.
- `$lte`: Menor o igual que.
- `$in`: En un conjunto de valores.
- `$nin`: No en un conjunto de valores.

### 5.2.2 Ejemplos de Consultas con Filtros:

1. Consultar documentos con un valor específico (`$eq`):

```js
db.productos.find({ "categoria": "Electrónica" })
```

## 5.3 Consultas con Proyecciones

La proyección en MongoDB se utiliza para definir qué campos se incluirán o excluirán en los resultados. Es el segundo argumento del método `find()`.

### 5.3.1 Incluir o Excluir Campos:

1. Incluir campos específicos (1 significa incluir):

```js
db.productos.find({}, { "nombre": 1, "precio": 1 })
```

## 5.4 Consultas con Operadores Lógicos

MongoDB también permite combinar filtros con operadores lógicos como `$and`, `$or`, `$not`, y `$nor`.

### 5.4.1 Operadores Lógicos Comunes:
- `$and`: Coincidencia de todas las condiciones.
- `$or`: Coincidencia de alguna condición.
- `$not`: Negar una condición.
- `$nor`: Coincidencia de ninguna condición.

### 5.4.2 Ejemplos de Consultas con Operadores Lógicos:

1. Consultar documentos que cumplan dos condiciones (`$and`):

```js
db.productos.find({
  $and: [
    { "categoria": "Electrónica" },
    { "precio": { $gt: 500 } }
  ]
})
```

## 5.5 Consultas con Operadores de Arreglos

MongoDB permite realizar búsquedas sobre campos que contienen arreglos utilizando operadores específicos como `$all`, `$size`, `$elemMatch`, entre otros.

### 5.5.1 Operadores Comunes para Arreglos:
- `$all`: Coincidencia de todos los valores en un arreglo.
- `$size`: Coincidencia por el tamaño del arreglo.
- `$elemMatch`: Coincidencia de al menos un elemento que cumpla con múltiples condiciones.

### 5.5.2 Ejemplos de Consultas con Arreglos:

1. Consultar documentos con un campo que contenga un arreglo y tenga un tamaño específico (`$size`):

Supongamos que un documento tiene un campo `etiquetas` que es un arreglo de palabras clave. Podemos buscar documentos que tengan exactamente tres etiquetas.

```js
db.productos.find({ "etiquetas": { $size: 3 } })
```

## 5.6 Ordenar y Limitar Resultados

MongoDB permite ordenar los resultados de una consulta y limitar el número de documentos devueltos.

### 5.6.1 Ordenar Resultados: `sort()`

El método `sort()` ordena los resultados de la consulta según el campo especificado. Se usa `1` para orden ascendente y `-1` para descendente.

**Ejemplo:** Ordenar los productos por precio de forma descendente.

```js
db.productos.find().sort({ "precio": -1 })
```

## 5.7 Conclusión

Las consultas en MongoDB ofrecen una enorme flexibilidad, permitiendo filtrar, proyectar, ordenar y limitar los resultados. MongoDB también admite una amplia gama de operadores lógicos, de comparación y de arreglos para realizar búsquedas complejas y específicas. El uso adecuado de estos operadores y métodos te permitirá gestionar grandes volúmenes de datos de manera eficiente y precisa.

---

# 6 Índices en MongoDB

Los índices en MongoDB son estructuras de datos especiales que almacenan una parte de los datos de una colección de una manera que permite que las consultas sean mucho más rápidas. Sin índices, MongoDB debe realizar un escaneo completo de la colección (examinar cada documento) para seleccionar los documentos que coincidan con la consulta. Los índices mejoran el rendimiento de las consultas, pero también tienen algunos costos asociados, como el uso de espacio adicional y tiempo de procesamiento para mantenerlos actualizados.

## 6.1 1. ¿Qué son los índices?

Un índice en MongoDB es similar a un índice en un libro: permite acceder a la información de manera rápida sin tener que revisar todos los documentos de una colección. MongoDB crea automáticamente un índice en el campo `_id` de cada colección, que es el identificador único de cada documento.

### 6.1.1 Ventajas de usar índices:

- **Aceleración de consultas:** Las consultas que utilizan índices se ejecutan más rápido porque MongoDB puede buscar en una estructura de índice en lugar de revisar todos los documentos.
- **Optimización de operaciones de lectura:** Las consultas que requieren ordenar o filtrar datos pueden beneficiarse significativamente de los índices.

### 6.1.2 Desventajas o costos:

- **Sobrecarga en inserciones:** Mantener los índices actualizados agrega una pequeña sobrecarga en las operaciones de escritura (insertar, actualizar, eliminar).
- **Uso de almacenamiento adicional:** Los índices ocupan espacio adicional en el disco.

# 6 Índices en MongoDB

Los índices en MongoDB son estructuras que mejoran la velocidad de las consultas al evitar escaneos completos de la colección. Sin embargo, su uso implica más espacio y algo de carga en las escrituras.

## 6.1 ¿Qué son los índices?

Un índice es como el índice de un libro: permite encontrar datos rápido. MongoDB crea por defecto un índice único en el campo `_id`.

### Ventajas:
- Consulta más rápida.
- Mejor rendimiento en ordenación y filtros.

### Desventajas:
- Sobrecarga en inserciones, actualizaciones y eliminaciones.
- Consumo extra de espacio en disco.

## 6.2 Tipos de índices comunes

- **Índice único:** No permite valores duplicados (`{ unique: true }`).
- **Índice simple:** Índice en un solo campo para acelerar búsquedas.
- **Índice compuesto:** Índice en varios campos para consultas que filtran por varios campos a la vez.
- **Índice de texto:** Permite búsquedas de texto completo en campos específicos.
- **Índice geoespacial:** Para consultas sobre datos con ubicación geográfica.

## 6.3 Crear, ver y eliminar índices

- Crear: `db.collection.createIndex({ campo: 1 })`
- Ver: `db.collection.getIndexes()`
- Eliminar: `db.collection.dropIndex({ campo: 1 })`

## 6.4 Buenas prácticas

- Crear índices solo en campos usados frecuentemente en consultas.
- Usar índices compuestos si se filtra por varios campos.
- Evitar índices redundantes.
- Monitorizar con `explain()` para entender el uso de índices.

## 6.5 Uso de explain()

`explain("executionStats")` muestra cómo se ejecuta una consulta y si usa índices, ayudando a optimizar el rendimiento.

Ejemplo:

```js
db.productos.find({ precio: { $gt: 500 } }).explain("executionStats")
```

## 6.6 Conclusión

Los índices en MongoDB son fundamentales para mejorar el rendimiento de las consultas, sobre todo con grandes volúmenes de datos. Sin embargo, su uso debe planificarse bien, ya que aumentan el costo en las operaciones de escritura y consumen más espacio. Por eso, es clave monitorear las consultas con `explain()` y crear solo los índices necesarios para mantener el sistema eficiente.

---

# 7 Agregaciones en MongoDB

Las agregaciones permiten realizar operaciones complejas como sumas, promedios, agrupaciones y filtrados directamente en la base de datos, sin procesar los datos después en la aplicación. MongoDB usa pipelines (tuberías) que encadenan etapas para transformar documentos.

## 7.1 ¿Qué es el Aggregation Framework?

Es el sistema principal para consultas complejas, similar a `GROUP BY` en SQL, pero más flexible.

```js
db.coleccion.aggregate([ { etapa1 }, { etapa2 }, ... ])

db.productos.aggregate([{ $match: { precio: { $gt: 500 } } }])

db.productos.aggregate([
  { $group: { _id: "$categoria", precioPromedio: { $avg: "$precio" } } }
])

db.productos.aggregate([
  { $project: { nombre: 1, precio: 1, precioConIVA: { $multiply: ["$precio", 1.21] } } }
])

db.productos.aggregate([
  { $match: { precio: { $gt: 100 } } },
  { $group: { _id: "$categoria", precioPromedio: { $avg: "$precio" } } },
  { $sort: { precioPromedio: -1 } }
])

db.productos.aggregate([
  { $group: { _id: "$categoria", totalProductos: { $sum: 1 } } }
])

db.productos.mapReduce(
  function() { emit(this.categoria, 1); },
  function(key, values) { return Array.sum(values); },
  { out: "productos_totales_por_categoria" }
)
```

## 7.7 Conclusión
El **Aggregation Framework** es una herramienta potente para análisis y transformación de datos en MongoDB. Permite combinar múltiples etapas para realizar operaciones complejas con flexibilidad y eficiencia. El uso de explain() ayuda a optimizar las consultas y asegurar buen rendimiento.

Copiar
Editar

---

# 8. Replicación y Alta Disponibilidad en MongoDB

La replicación en MongoDB es el proceso que permite mantener múltiples copias de los datos en diferentes servidores para garantizar la alta disponibilidad y tolerancia a fallos. Así, si un servidor falla, otros pueden seguir atendiendo las solicitudes sin pérdida de datos.

## 8.1 ¿Qué es la replicación en MongoDB?

- Consiste en sincronizar datos entre varios servidores.
- Se usa un **Replica Set**: un grupo de instancias MongoDB con los mismos datos.
- Un Replica Set tiene:
  - **Nodo primario (Primary):** recibe todas las escrituras.
  - **Nodos secundarios (Secondary):** copian datos del primario.
  - **Nodo árbitro (Arbiter):** no guarda datos, pero vota para elegir primario en caso de fallo.
  
### Ventajas:
- Alta disponibilidad: si falla el primario, un secundario se promueve a primario.
- Escalabilidad de lectura: las lecturas pueden distribuirse entre secundarios.
- Tolerancia a fallos: el sistema sigue operativo aunque algún servidor caiga.

## 8.2 Componentes del Replica Set

- **Nodo primario:** único con capacidad de escritura.
- **Nodos secundarios:** replican datos y pueden recibir lecturas.
- **Árbitro:** solo vota en elecciones para evitar empates, no afecta rendimiento.

## 8.3 Configuración del Replica Set

- Se inician las instancias de MongoDB en modo Replica Set.
- Se configura el Replica Set con los nodos que formarán parte.
- Se verifica el estado del Replica Set para comprobar los roles de cada nodo.

## 8.4 Proceso de elección

- Si el nodo primario falla o es degradado, los secundarios votan para elegir un nuevo primario.
- Se necesita mayoría (quorum) para que haya primario.
- Si no se consigue mayoría, el Replica Set queda sin primario hasta restaurar quorum.

## 8.5 Escalabilidad de lectura con nodos secundarios

- Por defecto, solo el primario sirve lecturas para mantener consistencia fuerte.
- Se puede configurar para leer preferentemente de secundarios.
- Esto mejora la disponibilidad y la velocidad, pero puede dar datos ligeramente desactualizados.

## 8.6 Ventajas y desventajas de la replicación

### Ventajas:
- Alta disponibilidad.
- Mejor distribución de carga de lectura.
- Recuperación ante fallos.

### Desventajas:
- Sobrecarga en escrituras para mantener sincronización.
- Posible inconsistencia temporal (consistencia eventual) al leer secundarios.

## 8.7 Consideraciones sobre la consistencia

- **Consistencia fuerte:** lectura solo en primario.
- **Consistencia eventual:** lectura en secundarios puede devolver datos desactualizados momentáneamente.

## 8.8 Conclusión

La replicación con Replica Sets es clave para garantizar que MongoDB sea altamente disponible y tolerante a fallos, asegurando que los datos estén siempre accesibles. Permite además escalar las lecturas distribuyendo la carga. Sin embargo, implica desafíos en la consistencia y carga de escritura.

---

# 9. Sharding en MongoDB

El sharding es una técnica de escalabilidad horizontal que MongoDB utiliza para distribuir grandes conjuntos de datos y cargas de trabajo entre múltiples servidores. Esto permite manejar bases de datos de gran tamaño y mejorar el rendimiento, fragmentando los datos en partes llamadas shards. Cada shard almacena una parte de los datos, y MongoDB gestiona la distribución eficiente de las consultas y escrituras entre ellos.

## 9.1 ¿Qué es el Sharding?

- Es el proceso de dividir los datos en fragmentos o shards.
- Cada shard es una base de datos MongoDB completa que contiene un subconjunto de los datos.
- Juntos, los shards forman una base de datos lógica única.
- MongoDB decide en qué shard almacenar cada documento según una clave de fragmentación (shard key).

### Ventajas del Sharding:
- **Escalabilidad horizontal:** distribuye datos y operaciones entre varios servidores, permitiendo manejar grandes volúmenes de datos y mejorar el rendimiento.
- **Carga equilibrada:** evita que un solo servidor procese todas las consultas y operaciones.
- **Alta disponibilidad:** los shards pueden replicarse usando Replica Sets, garantizando disponibilidad ante fallos.

## 9.2 Componentes del Sharding en MongoDB

### 9.2.1 Shards
- Cada shard contiene una parte del conjunto de datos.
- Normalmente, los shards están configurados como Replica Sets para alta disponibilidad y redundancia.

### 9.2.2 Router de Consultas (mongos)
- Componente que recibe las solicitudes de los clientes y las distribuye a los shards adecuados.
- Determina qué shard contiene los datos solicitados y dirige las operaciones a ese shard.

### 9.2.3 Config Servers
- Instancias que almacenan metadatos sobre la estructura del clúster.
- Guardan información sobre la asignación de fragmentos y configuración del sharding.
- Ayudan a coordinar las operaciones del clúster.

## 9.2.4 Proceso de Sharding

- Se habilita el sharding en una colección especificando una clave de fragmentación (shard key).
- MongoDB divide los datos en rangos basados en esa clave y los asigna a los diferentes shards.

### Shard Key (Clave de Fragmentación)

- Campo o conjunto de campos usados para distribuir los datos entre shards.
- Elegir una buena shard key es fundamental para el rendimiento.
- Características de una buena shard key:
  - **Cardinalidad alta:** muchos valores únicos para distribuir uniformemente los datos.
  - **Distribución uniforme:** evita que unos pocos shards manejen la mayoría de los datos o consultas.
  - **Consultas comunes:** relacionada con los campos más usados en las consultas para optimizar eficiencia.

## Conclusión
El sharding en MongoDB es una técnica poderosa para escalar horizontalmente bases de datos que manejan grandes volúmenes de datos o tráfico. Al distribuir los datos entre múltiples shards, MongoDB permite que la base de datos crezca y maneje más operaciones de manera eficiente. 

Sin embargo, configurar un clúster sharded requiere planificación cuidadosa, especialmente en la elección de la shard key, para garantizar un rendimiento óptimo y una carga equilibrada entre los servidores.

---

# 10 Seguridad en MongoDB

La seguridad en MongoDB es fundamental para proteger los datos de acceso no autorizado, ataques y otras amenazas potenciales. MongoDB ofrece varias características de seguridad, que incluyen autenticación, autorización, cifrado de datos, auditoría y medidas de seguridad en red. Estas características permiten asegurar tanto el acceso a los datos como su integridad.

## 10.1 Autenticación en MongoDB

La autenticación es el proceso de verificar la identidad de un usuario antes de que pueda acceder a la base de datos. MongoDB proporciona varios métodos de autenticación para garantizar que solo los usuarios autorizados puedan acceder al sistema.

### 10.1.1 Tipos de Autenticación en MongoDB

- **Autenticación basada en roles (SCRAM - Salted Challenge Response Authentication Mechanism):**  
  Es el método de autenticación más común en MongoDB y está habilitado por defecto. MongoDB utiliza SCRAM-SHA-1 o SCRAM-SHA-256 para autenticar usuarios.

## 10.2 Autorización en MongoDB

La autorización en MongoDB se refiere al proceso de verificar qué acciones puede realizar un usuario autenticado. MongoDB usa un sistema basado en roles para controlar los permisos de los usuarios, lo que significa que cada usuario tiene uno o más roles que definen las operaciones que puede realizar en la base de datos.

### 10.2.1 Tipos de Roles en MongoDB

1. **Roles predefinidos:**  
MongoDB incluye varios roles predefinidos para diferentes niveles de acceso:  
- **userAdmin:** Permite crear y gestionar usuarios.  
- **dbAdmin:** Permite realizar tareas administrativas, como crear índices, obtener estadísticas de la base de datos y manejar configuraciones.  
- **read:** Permite solo operaciones de lectura en una base de datos.  
- **readWrite:** Permite operaciones de lectura y escritura en una base de datos.

2. **Roles por bases de datos específicas:**  
Los roles pueden aplicarse a bases de datos específicas. Por ejemplo, un usuario puede tener acceso de solo lectura a una base de datos y acceso completo a otra.

### 10.3 Cifrado de Datos en MongoDB

MongoDB ofrece varias opciones de cifrado para garantizar que los datos estén protegidos tanto en tránsito como en reposo.

- **Cifrado en tránsito (TLS/SSL):** Protege los datos mientras se transfieren entre clientes y servidores MongoDB mediante cifrado de todas las comunicaciones.
- **Cifrado en reposo:** Asegura que los datos estén cifrados mientras se almacenan en disco, disponible principalmente en la versión Enterprise de MongoDB.

### 10.4 Seguridad en la Red

Es fundamental proteger el acceso a los servidores MongoDB mediante medidas de seguridad en la red, tales como:

- Uso de firewalls para restringir el acceso a los puertos de MongoDB, permitiendo solo conexiones autorizadas.
- Deshabilitar el acceso remoto a la consola de administración para evitar accesos no autorizados.
- Aislamiento de redes en entornos en la nube mediante Virtual Private Cloud (VPC) y uso de VPN o túneles seguros para limitar el acceso público y proteger la base de datos.

### 10.5 Auditoría en MongoDB

MongoDB Enterprise incluye características de auditoría que permiten registrar y rastrear todas las acciones de los usuarios en la base de datos. Esto es crucial para cumplir con regulaciones de seguridad y privacidad como GDPR o HIPAA. La auditoría permite registrar eventos como operaciones de lectura y escritura, creación y eliminación de bases de datos, y modificaciones en la configuración de usuarios y roles.

### 10.6 Buenas Prácticas de Seguridad en MongoDB

1. Habilitar siempre autenticación y autorización.
2. Usar TLS/SSL para asegurar las comunicaciones.
3. Aislar la red mediante firewalls y VPC.
4. Configurar roles con permisos mínimos necesarios.
5. Realizar auditorías periódicas para detectar accesos no autorizados.

### 10.7 Conclusión

La seguridad en MongoDB es esencial para proteger los datos y asegurar que solo los usuarios autorizados puedan acceder a ellos. Con una combinación de autenticación robusta, control de acceso basado en roles, cifrado de datos y medidas de seguridad en la red, MongoDB proporciona un entorno seguro para bases de datos críticas. Además, la auditoría permite mantener el control y detectar actividades sospechosas.

---

## 11 Anexo 1: Documentos y Colecciones vs. Tablas y Filas (Ampliación de la Sección 2)

En bases de datos relacionales, los datos se almacenan en tablas, y cada fila en una tabla es un registro único. En MongoDB, los datos se almacenan en colecciones, y cada documento en una colección es similar a una fila en una tabla.

| Característica                | MongoDB (Documentos y Colecciones) | SQL (Tablas y Filas)            |
|------------------------------|-----------------------------------|--------------------------------|
| **Esquema**                  | No es necesario definir un esquema| Esquema rígido definido por tablas |
| **Documentos/Filas**          | Documentos pueden tener diferentes campos | Todas las filas tienen la misma estructura |
| **Datos anidados**            | Soporta subdocumentos y arreglos  | Se utiliza normalización o relaciones |
| **Consultas**                 | Filtrado con `find()` y operadores JSON | Consultas con `SELECT`, `WHERE`, `JOIN` |

---

## 12 Anexo 2: Bases de Datos en MongoDB vs. SQL (Ampliación de la Sección 1)

En MongoDB, las bases de datos son contenedores lógicos que agrupan colecciones, al igual que en SQL, donde las bases de datos agrupan tablas. Sin embargo, la principal diferencia está en la flexibilidad de MongoDB en cuanto a la estructura de los datos.

| Operación               | MongoDB                                     | SQL                              |
|------------------------|--------------------------------------------|---------------------------------|
| Crear base de datos     | `use nombre_base_datos`                     | `CREATE DATABASE nombre_base_datos` |
| Crear tabla/colección   | La colección se crea automáticamente       | `CREATE TABLE nombre_tabla (...)`|
| Eliminar base de datos  | `db.dropDatabase()`                         | `DROP DATABASE nombre_base_datos`|
| Eliminar tabla/colección| `db.nombre_coleccion.drop()`                | `DROP TABLE nombre_tabla`        |

En MongoDB, no es necesario predefinir una colección antes de insertar datos. La base de datos y la colección se crean automáticamente cuando se insertan documentos.

---

## 13 Anexo 3: Operaciones CRUD en MongoDB vs. SQL (Ampliación de la Sección 4)

Las operaciones CRUD (Crear, Leer, Actualizar, Borrar) son fundamentales tanto en MongoDB como en SQL, pero la forma en que se ejecutan difiere debido a las diferencias en el modelo de datos.

### 13.1 Crear (Insertar Datos)
- En SQL, se utiliza el comando `INSERT INTO` y los nombres de las columnas deben coincidir con el esquema de la tabla.
- En MongoDB, no es necesario predefinir las columnas.

### 13.2 Leer (Consultar Datos)
- En MongoDB, se utilizan operadores JSON para filtrar los documentos, como `$gt` (mayor que).
- SQL utiliza cláusulas como `WHERE` para filtrar las filas de una tabla.

### 13.3 Actualizar
- Tanto en SQL como en MongoDB, se pueden actualizar registros específicos.
- En MongoDB se utiliza `$set` para modificar campos específicos.

### 13.4 Borrar
- Las operaciones de eliminación son similares, con la diferencia de que MongoDB usa métodos específicos como `deleteOne()` o `deleteMany()`.

---

## 14 Anexo 4: Consultas en MongoDB vs. SQL (Ampliación de la Sección 5)

Las consultas en MongoDB se basan en operadores JSON, mientras que en SQL se utilizan cláusulas como `SELECT`, `WHERE` y `JOIN`.

- En MongoDB, los operadores de comparación como `$gt` (mayor que) o `$lt` (menor que) son equivalentes a las cláusulas `>` y `<` de SQL.

---

## 15 Anexo 5: Índices en MongoDB vs. SQL (Ampliación de la Sección 6)

Los índices mejoran el rendimiento de las consultas tanto en SQL como en MongoDB, aunque su implementación y sintaxis son diferentes.

- En SQL, los índices se crean explícitamente para mejorar el rendimiento de las consultas en columnas específicas.
- En MongoDB, se pueden crear índices en cualquier campo, y se pueden utilizar en consultas con operadores JSON.

---

## 16 Anexo 6: Agregaciones en MongoDB vs. SQL (Ampliación de la Sección 7)

MongoDB y SQL tienen mecanismos para realizar operaciones de agregación, como sumar, promediar, contar y agrupar datos. En SQL, esto se hace con `GROUP BY`, mientras que en MongoDB se utiliza el Aggregation Framework.

### 16.1 Agrupaciones (GROUP BY en SQL)

#### 16.1.1 SQL:
```sql
SELECT categoria, AVG(precio) FROM productos GROUP BY categoria;
```

### 16.3 Conclusión del Anexo

MongoDB ofrece mayor flexibilidad gracias a su modelo de documentos y manejo de datos no estructurados, mientras que SQL tiene un esquema rígido y optimizado para transacciones estructuradas. Sin embargo, conceptos fundamentales como índices, consultas y agregaciones son similares y fáciles de trasladar entre ambos sistemas.









