# 📘 Obligatorio 2 – Programación 2

## 🧩 Descripción del Proyecto

Continuando con el sistema desarrollado en el primer obligatorio, se solicita una segunda versión que incluya una aplicación web ASP.NET 8.0 MVC con autenticación por usuario y contraseña. El sistema debe mostrar funcionalidades específicas según el rol del usuario, y restringir el acceso a opciones no autorizadas.

## 🔐 Requisitos de Seguridad

- Acceso mediante login con email y contraseña.
- Visualización de opciones según el rol (Peón o Capataz).
- Restricción de acceso a funcionalidades no autorizadas, incluso mediante URL directa.

---

## 📌 Puntos Solicitados

### 🧠 Punto 1: Diagramas

- Diagrama de clases del dominio (formato Astah + documentación digital).
- Diagrama de casos de uso (formato Astah + documentación digital).

---

### 💻 Punto 2: Implementación en ASP.NET 8.0 MVC (Visual Studio 2022)

#### 👤 Usuario Anónimo

- Login con email y contraseña.
- Registro como Peón (email, contraseña, nombre, residencia).

#### 🧑‍🌾 Usuario Peón

- Acceder a sus datos personales.
- Registrar vacunación para cualquier animal.
- Ver tareas pendientes ordenadas por fecha (ascendente).
- Completar tarea con comentario de cierre.
- Logout.

#### 🧑‍💼 Usuario Capataz

- Registrar nuevo bovino.
- Asignar bovino a potrero.
- Ver listado de peones + detalle de tareas.
- Asignar tarea a peón.
- Ver potreros ordenados por capacidad y cantidad de animales.
- Filtrar animales por tipo y peso, mostrando datos relevantes.
- Logout.

---

### 🚀 Punto 3: Deploy

- Publicación del proyecto en [Somee](https://somee.com).

---

### 📄 Punto 4: Documentación PDF

- Portada con datos del equipo, docente y fotos.
- Diagramas de clases y casos de uso.
- Planilla de casos de prueba.
- Código fuente comentado (solo clases del dominio).
- Ajustes/mejoras respecto a la primera entrega.

---

## 🛠️ Consideraciones Técnicas

- Interfaz: Proyecto ASP.NET MVC.
- Lógica de negocio: Biblioteca de clases (.NET 8).
- Validaciones y mensajes de error adecuados.
- Precarga de datos para testing completo.
- Comentarios explicativos en el código.

---

## 📦 Entrega Final

Subir a gestión un único archivo comprimido que incluya:

- Solución completa en .NET 8 (MVC + bibliotecas).
- Documento PDF con la documentación.
- Archivos Astah con diagramas.

---

<p align="center">
      <img src="https://img.shields.io/badge/CSHARP-239120?style=for-the-badge&logo=csharp&logoColor=white">
      <br>
      <img src="https://img.shields.io/badge/ESTADO-FINALIZADO-brightgreen?logo=csharp&logoColor=white">
</p>
