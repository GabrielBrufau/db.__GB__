# SQL
```bash
UPDATE clause   {UPDATE country
SET clause      {SET population = (population + 1)=>EXPRESSION
WHERE clause    {WHERE (name = USA)=>PREDICATE
```
# DDL(data definition language)
es un lenguaje que nos ayuda a crear la estructura de una base de datos 
# tres grandes comandos de DDL
```sql
CREATE? nos ayuda a crear base de datos, tabla, vista, indice, etc.
         DATABASE
         TABLE->son las entidades
         VIEWS->para hacer las views se usa el selec ya que al tener normalizada una
                base de tados se hace dificil ver los datos por eso usamos las views
Alter //? nos ayuda a allterar o modificar algunas de estas entidades.
Drop //? nos ayuda a borrar MUCHO CUIDADO CON DROP!!
```
# code
```sql
CREATE DATABASE nombredelabasededatos
CREATE TABLE nombretabla {
  persona_id int,
  last_name varchar(255),
  first_name varchar(255),
  address varchar(255),
  city varchar(255)
};
USE DATABASE nombredelabasededatos
CREATE VIEWS v_nombre_vista AS SELECT nombredeloquevamosaseleccionar  FROM dedondelovamosaseleccionar WHERE condicion=algunacondicion


```