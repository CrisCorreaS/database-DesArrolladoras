# database-DesArrolladoras
![Badge en Desarollo](https://img.shields.io/badge/STATUS-FINALIZADO-violet) <br/>
<br/>
Ejercicio de Laboratorio del Curso "Desarrollo Full-Stack (Nivel 3) ED.2022" del programa Samsung DesArrolladoras. Este repositorio contiene el archivo .sql necesario para crear la tabla "USUARIO" en la base de datos. Asegúrate de seguir las siguientes indicaciones para subir correctamente los archivos.

### Archivo .sql
El archivo que debes subir es el siguiente:

**usuario.sql:** Contiene la definición de la tabla "usuario" con los campos "id", "nombre", "apellido" y "email". El campo "id" es la Primary Key y se autoincrementa. Los campos "nombre", "apellido" y "email" son de tipo Varchar(20).

### SQL
Las dos queries SQL que utilicé fueron:

Para crear la tabla de usuario con sus cuatro columnas:
<p><b>CREATE TABLE &#96;usuario&#96; ( <br/>
    &#96;id&#96; int NOT NULL AUTO_INCREMENT,<br/>
    &#96;nombre&#96; varchar(20) NOT NULL,<br/>
    &#96;apellido&#96; varchar(20) NOT NULL,<br/>
    &#96;email&#96; varchar(20) NOT NULL<br/>
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;</b></p>
<br/>
Para poner dos registros en nuestra base de datos:
<p><b>INSERT INTO &#96;usuario&#96; (&#96;nombre&#96;, &#96;apellido&#96;, &#96;mail&#96;) VALUES <br/>
('Cristina', 'Correa', 'cristina.correa@gmail.com'),<br/>
('Carlos', 'Creo', 'carlos.creo@gmail.com');</b></p>

