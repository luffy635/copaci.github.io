# 🏛️ Sistema de Gestión Ciudadana - COPACI Granjas Guadalupe

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)

Proyecto web interactivo diseñado para el **Consejo de Participación Ciudadana (COPACI) de Granjas Guadalupe**. La plataforma permite a los ciudadanos realizar trámites y reportes vecinales, a la administración dar seguimiento a los folios y a los desarrolladores monitorear la persistencia de datos.

---

## 🚀 Características Principales

* **Estructura Semántica en HTML5:** Uso estricto de etiquetas semánticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`) para cumplir con estándares de accesibilidad y SEO.
* **Diseño Institucional Responsivo con CSS3:** Estilos externos centralizados en `style1.css` con paleta institucional y compatibilidad en múltiples dispositivos[cite: 1].
* **Control de Acceso Multi-Interfaz (3 Roles):**
  * 👤 **Vista Usuario:** Envío de solicitudes y consultas comunitarias.
  * 🏛️ **Vista Administrador COPACI:** Gestión de solicitudes y actualización de estatus (*Pendiente*, *En proceso*, *Resuelto*).
  * 💻 **Vista Desarrollador:** Consola técnica con métricas del sistema y vista de datos crudos en formato JSON.
* **Persistencia de Datos Local:** Uso de `localStorage` para almacenar los reportes de manera local sin necesidad de servidores externos.

---

## 🔑 Credenciales de Acceso

| Rol | Usuario | Contraseña |
| :--- | :--- | :--- |
| 👤 **Usuario** | `usuario` | `user123` |
| 🏛️ **Administrador COPACI** | `admin` | `copaci123` |
| 💻 **Desarrollador** | `dev` | `dev123` |

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Maquetación semántica estructurada[cite: 1].
* **CSS3:** Hojas de estilo externas, Flexbox, y diseño interactivo[cite: 1].
* **JavaScript (Vanilla JS):** Manipulación del DOM, control de eventos, validación de credenciales y manejo del `localStorage`.

---

## 📂 Estructura del Proyecto

```text
.
├── index.html                       # Documento principal con la estructura HTML5 y lógica JS
├── style1.css                       # Hoja de estilos externa CSS3
├── logo-nuevo-Copaci-1080x625.jpeg  # Logotipo oficial
└── images (1).jpg                   # Imagen ilustrativa para la tarjeta de trámites