# 📚 Challenge Literalura

Aplicación desarrollada en **Java con Spring Boot** que consume una API de libros para buscar, almacenar y consultar información sobre libros y autores en una base de datos.

Este proyecto fue desarrollado como parte del **Challenge Literalura de Alura Latam**.

---

## 🚀 Tecnologías utilizadas

* ☕ Java
* 🌱 Spring Boot
* 🗄️ PostgreSQL
* 🔗 API Gutendex
* 📦 Maven
* 🧩 JPA / Hibernate
* 📊 JSON (Gson / Jackson)

---

## 📖 Funcionalidades

La aplicación permite:

* 🔍 Buscar libros por título usando una API externa
* 💾 Guardar libros en una base de datos
* 👨‍💻 Listar libros registrados
* ✍️ Listar autores registrados
* 📅 Buscar autores vivos en determinado año
* 🌎 Listar libros por idioma

---

## 🗄️ Estructura del proyecto

```
src
 ├── main
 │   ├── java
 │   │   └── com.aluracursos.literalura
 │   │        ├── main
 │   │        ├── model
 │   │        ├── repository
 │   │        └── service
 │   └── resources
 │        └── application.properties
```

---

## ⚙️ Configuración del proyecto

1. Clonar el repositorio

```bash
git clone https://github.com/JuanSilv19/Challenge-Literalura.git
```

2. Configurar la base de datos en `application.properties`

Ejemplo:

```
spring.datasource.url=jdbc:postgresql://localhost:5432/literalura
spring.datasource.username=tu_usuario
spring.datasource.password=tu_password
```

3. Ejecutar el proyecto desde el IDE.

---

## 📌 API utilizada

La aplicación consume la API pública:

Gutendex API
https://gutendex.com/

Esta API proporciona información sobre libros del **Proyecto Gutenberg**.

---

## 👨‍💻 Autor

Proyecto desarrollado por:

**Juan Cárdenas**

Estudiante de **Ingeniería de Sistemas** interesado en:

* Ciberseguridad
* Desarrollo backend
* Tecnología y software

---

## ⭐ Contribuciones

Si deseas mejorar el proyecto puedes:

* Hacer un **fork**
* Crear una **rama**
* Enviar un **pull request**

---

## 📜 Licencia

Este proyecto es de uso educativo.
