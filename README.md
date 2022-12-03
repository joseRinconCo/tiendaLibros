# TiendaLibros


![unab](https://user-images.githubusercontent.com/85587286/205414621-a0d72eca-756b-4392-8587-9c74293365de.gif)
 
 

## Descripción Proyecto (Mundo del Proyecto) 

 

~~~~
Centro Cultural Lennon lleva más de 10 años fomentando el gusto por la lectura mediante la creación de comunidades o grupos que se reúnen periódicamente para comentar libros leídos en casa o en las salas de lectura con las que cuenta el centro, está diseñado para aprender y descubrir junto a tus amigos el maravilloso mundo de la lectura y compartir lindas experiencias. 

En las reuniones se comenta lo leído y el impacto que ha tenido en lector: temáticas, estilo, acción, personajes y, por supuesto, sentimientos o reflexiones evocados por el texto, no es una reunión para especialistas en crítica literaria ni para profesores de literatura sino para lectores comunes. 

Centro Cultural Lennon quiere integrar a sus asociados en el proceso previo a la selección de material candidato para lectura, mediante la creación de un catálogo virtual que les permita consultar las principales características de los libros sugeridos como material de lectura y análisis dentro de los grupos, realizar una votación y registrar una opinión orientada a justificar la razón por la cual una obra debería ser considerada en un futuro cercano como material de lectura y análisis. La selección final de material de lectura o libros candidatos se realizará previo acuerdo entre moderadores e integrantes de grupo entre los libros que hayan recibido la mejor puntuación y opiniones positivas. 

Es importante resaltar que Centro Cultural Lennon no realiza venta o distribución de libros, solamente lleva un registro de libros que históricamente han sido sugeridos por sus libreros y académicos, como material de lectura o algunas novedades sugeridas por las editoriales. El Centro Cultural se mantiene gracias a donaciones, talleres de escritura creativa, redacción y otras actividades. 

 ~~~~

## Objetivo General 

 ~~~~

Crear una aplicación que permita la administración de libros sugeridos como material de lectura y análisis dentro de los grupos, realizar una votación y registrar una opinión orientada a justificar la razón por la cual una obra debería ser considerada en un futuro cercano como material de lectura y análisis 

~~~~
 

## Objetivos Específicos 

 ~~~~

Promover la participación de los asociados en los procesos de clasificación del material literario con el que trabajarán los diferentes grupos de lectura. 

Crear un espacio de convivencia para reunirse e intercambiar opiniones e ir generando comunidad, aceptando y respetando otros puntos de vista. 

Compartir experiencias lectoras entre personas de edades muy diversas. 

Reflexionar sobre las obras leídas 

~~~~ 
 

## Requerimientos Funcionales 

 ~~~~

Se requiere una aplicación Web SPA (SINGLE PAGE APPLICACTION) para administrar un catálogo virtual de libros e información paramétrica, permitiendo a los usuarios registrados consultar información general de los libros bajo diferentes criterios, registrar su opinión y calificación sobre los libros del catálogo. 

La aplicación contara con un perfil Administrador y un perfil Usuario, algunas funcionalidades estarán disponibles para ambos, perfiles; pero la Administración del catalogo e información relacionada será de uso exclusivo del perfil administrador. 

Todas las opciones disponibles en la aplicación requerirán de autenticación previa. 

Opciones Generales:  

Autenticar usuario 

Cambio de contraseña 

Perfil Administrador: El administrador del sistema tendrá el privilegio de administrar (operaciones CRUD) la siguiente información: 

Administración de datos (CRUD) 

Categorías género: Nombre del Genero 

Autores: Nombres y apellidos del autor 

Catálogo de Libros 

Usuarios 

Consultas 

La aplicación contará con diferentes opciones de consulta de libros, dentro de las cuales se encuentran las siguientes: 

Listar catálogo de libros x categoría o genero 

Listar catálogo de libros x autor 

Listar catálogo de libros – Opción Índice 

Listar catálogo de libros x rango de precios (el precio registrado es el promedio en las librerías) 

Perfil Usuario Autenticado (Independiente de su perfil) 

Reseñar Libros y calificar libros: Previa autenticación, consulta y selección de un libro del catálogo, un usuario podrá registrar una opinión orientada a justificar la razón por la cual una obra debería ser considerada en un futuro cercano como material de lectura y análisis e indicar una puntuación basado en la siguiente escala: 

Excelente 

Bueno 

Regular 

Malo 

 

Un usuario solamente podrá indicar puntuación y registrar opinión una sola vez por cada libro, y una vez registrada no podrá modificarla (la primera opinión es). 

 
## Requerimientos NO Funcionales 

 

Look and feel. Descripción: El aspecto del aplicativo debe ser consistente en todas sus páginas, además de amigable e intuitivo hacia el usuario. 

Seguridad. descripción: El protocolo o librería usado, para manejar la seguridad en la sesión del usuario debe ser lo suficientemente confiable. 

## Tecnologías a Utilizar 

Backend: MongoDB, Spring Boot 

Frontend: ReactJS (HTML + CSS + JAVASCRIPT) 

Framework CSS: Bootstrap 

JWT 

Planificación SCRUM - JIRA 

Repositorio de Código Github 

~~~~
 
# Colaboradores


>> * [Github Diana Manrrique]()
>> * [Github Esteicy Manrrique]()
>> * [Github Elkin Guerrero](https://github.com/elkinguerrero007)
>> * [Github neyder Torres]()
>> * [Github Jose Rincon]()
