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
