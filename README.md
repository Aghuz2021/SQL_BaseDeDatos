# LDD:lenguaje de definición dedatos.
El Lenguaje de Definición de Datos (LDD) es un componente fundamental de los sistemas de gestión de bases de datos (DBMS). Se utiliza para definir y modificar la estructura de una base de datos, es decir, para crear, modificar y eliminar los objetos de la base de datos, como tablas, índices, vistas, procedimientos almacenados, restricciones, etc.

El LDD proporciona un conjunto de comandos y sintaxis que permiten a los usuarios y administradores de bases de datos definir la estructura y las características de los datos que serán almacenados en la base de datos. Algunos de los comandos típicos que se encuentran en un LDD incluyen:
CREATE: Se utiliza para crear nuevos objetos de base de datos, como tablas, vistas, índices, etc.
ALTER: Permite realizar cambios en la estructura existente de la base de datos, como agregar, modificar o eliminar columnas de una tabla.
DROP: Se utiliza para eliminar objetos de la base de datos, como tablas, vistas, índices, etc.
TRUNCATE: Elimina todos los datos de una tabla, pero mantiene la estructura de la tabla intacta.
COMMENT: Permite agregar comentarios o descripciones a objetos de la base de datos para documentación y clarificación.
El LDD es esencial para la administración eficiente de bases de datos, ya que proporciona los medios para definir la estructura de los datos de manera precisa y coherente, garantizando la integridad y consistencia de la información almacenada en la base de datos.

# LMD:lenguaje de manipulación de datos.
El Lenguaje de Manipulación de Datos (LMD) es un conjunto de comandos y funciones que se utilizan para manipular los datos almacenados en una base de datos. A diferencia del Lenguaje de Definición de Datos (LDD), que se utiliza para definir la estructura de la base de datos, el LMD se enfoca en realizar operaciones como inserción, modificación, eliminación y consulta de datos dentro de la base de datos.

# La cláusula SELECT en SQL

```sql
SELECT nombre, apellido
FROM clientes
```
# La cláusula where
```sql
SELECT nombre, apellido
FROM clientes
where nombre = ""
```
# La operación renombramiento
- As (Alias) 
#  Operaciones con cadenas de caracteres
- Operador like
- upper()
- lower()
- Operador similar to
# Orden en la presentación de las tuplas
- Order by
# Operaciones sobre conjuntos
-  union 
- intersect 
- except
#  Funciones de agregación
- avg  (Media)   
- min (min)
- Máx (Maximo)
- sum (Suma)
- count (Recuento)
- Having 

# Valores nulos
- is null
- is not null
