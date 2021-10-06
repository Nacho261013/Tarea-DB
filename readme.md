Tarea  -- Crear un repo y postearlo aca con los siguientes puntos

1º : Definicion de las relaciones y 5 ejemplos de c/u (uno a uno / uno a muchos / muchos a muchos)
2º : Investigar que es un SGBD (cuales son los mas famosos)
3º : En que se diferencian las relacionales y las no relacionales 


# 1:
> Una Base de Datos relacional se basa en modelos relacionales. Existen 3 tipos de relaciones.

## (uno a uno): 
> Ocurre cuando un registro de una tabla esta direccionado solamente a un registro de otra tabla. Por ejemplo:
     > Usuario <-> Direccion
     > Empresa <-> CUIT
     > Ciudadano <-> Telefono
     > Persona <-> Curriculum Vitae
     > Persona <-> Licencia

## (uno a muchos):
> Ocurre cuando un registro de una tabla esta relacionado a varios registros de otra tabla. Por Ejemplo:
    > Cliente <-> Tarjetas
    > Genero <-> Peliculas    
    > Ciudad <-> Turistas
    > Alumno <-> Curso
    > Profesor <-> Materia

 ## (muchos a muchos):
> Ocurre cuando relacionamos muchos registros de una trabla con muchos registros de otra trabla. Por ejemplo:
    > Clientes <-> Productos
    > Peliculas <-> Actores
    > Jugadores <-> Equipos
    > Estudiantes <-> Clases
    > Profesores <-> Grupos

# 2: 
##
> Un SGBD (Sistema Gestor de Base de Datos) es un conjunto de programas que nos permiten gestionar bases de datos. Es decir, realiza las funciones de modificar, extraer y almacenar información de una base de datos, además de poseer herramientas con funciones de eliminar, modificar, analizar, datos de estas.

##
Los  SGBD mas famosos son: 
 > MySQL
 > MariaDB
 > SQLite (biblioteca escrita en C que implementa un SGBD)
 > PostgreSQL
 > Microsoft SQL Server
 > Oracle.
   
# 3:
>Las bases de datos relacionales se basan en la organización de la información en partes pequeñas que se integran mediante identificadores; a diferencia de las bases de datos no relacionales que, como su nombre lo indica, no tienen un identificador que sirva para relacionar dos o más conjuntos de datos.
