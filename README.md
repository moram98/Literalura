# Proyecto Literalura

## Descripción General

Literalura es una aplicación desarrollada en Java que permite gestionar información sobre libros y autores, con integración de datos obtenidos desde la API de Gutendex. La aplicación proporciona un sistema para registrar, listar y consultar libros y autores, así como realizar búsquedas específicas según diferentes criterios.

##   Características Principales

1. Búsqueda de libros por título utilizando datos de la API de Gutendex.

1. Listado de libros registrados ordenados por autor.

1. Listado de autores registrados ordenados alfabéticamente.

1. Búsqueda de autores vivos en un año determinado.

1. Listado de libros por idioma.

1. Top 10 de libros más descargados en la base de datos local.

## Tecnologías Utilizadas

- Java 17

- Spring Boot

- Hibernate

- PostgreSQL

- Gutendex API

****Clase Principal que contiene la lógica de interacción con el usuario y funcionalidades principales.****

### Funcionalidades Detalladas

#### 1. Búsqueda de libros por título

Los usuarios pueden buscar libros mediante un título. Si el libro no está registrado en la base de datos, se consulta a la API de Gutendex y se registra el autor y el libro.

#### 2. Listar libros registrados

Muestra todos los libros almacenados en la base de datos local ordenados por el nombre del autor.

#### 3. Listar autores registrados

Lista todos los autores registrados en la base de datos, ordenados alfabéticamente.

#### 4. Autores vivos en un año determinado

Permite consultar qué autores estaban vivos en un año específico ingresado por el usuario.

#### 5. Listar libros por idioma

Los usuarios pueden filtrar los libros por idioma, como Español, Inglés, Francés o Portugués.

#### 6. Top 10 libros más descargados

Genera un listado con los 10 libros más descargados registrados en la base de datos.
