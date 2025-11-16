
# 🌐 webserv

## 🚀 Acerca del proyecto / About the Project

**Español:**
Webserv es nuestra implementación personal de un **servidor web desde cero** como parte de la escuela 42. Este proyecto nos permitió adentrarnos en los **fundamentos de HTTP/1.1, la gestión de conexiones concurrentes y la arquitectura de servidores web**. Construir un servidor propio no solo fortalece la comprensión técnica, sino que también ofrece una visión directa de la **ciberseguridad en la comunicación cliente-servidor**.

**English:**
Webserv is our personal implementation of a **web server from scratch**, developed at 42 school. This project gave us hands-on experience with **HTTP/1.1 fundamentals, concurrent connection handling, and web server architecture**. Building your own server not only strengthens technical skills but also provides direct insight into **cybersecurity in client-server communication**.

---

## ✨ Características / Key Features

| Español                                               | English                                           |
| ----------------------------------------------------- | ------------------------------------------------- |
| Soporte completo de HTTP/1.1: GET, POST, DELETE       | Full HTTP/1.1 support: GET, POST, DELETE          |
| Manejo de archivos estáticos y rutas personalizadas   | Handling of static files and custom routing       |
| Redirecciones y códigos de error HTTP                 | HTTP redirects and error codes                    |
| Ejecución de CGI para contenido dinámico              | CGI execution for dynamic content                 |
| Gestión segura y eficiente de conexiones concurrentes | Safe and efficient concurrent connection handling |

---

## 🔧 Tecnologías / Technologies

* Lenguaje: **C**
* Librerías estándar de **POSIX**
* Programación con **sockets**, **fork**, **poll/select**
* Gestión de concurrencia y recursos de red

---

## 🛡️ Relevancia técnica y en ciberseguridad / Technical and Cybersecurity Relevance

**Español:**
Este proyecto no es solo un ejercicio académico: permite **comprender vulnerabilidades comunes en servidores web**, como gestión incorrecta de conexiones, inyecciones HTTP o errores en CGI. Además, sienta bases sólidas para trabajar en **servicios en la nube y arquitectura de aplicaciones distribuidas**.

**English:**
This project is more than an academic exercise: it provides insight into **common web server vulnerabilities**, such as improper connection handling, HTTP injection, or CGI errors. It also lays a solid foundation for working with **cloud services and distributed application architectures**.

---

## 📂 Estructura del proyecto / Project Structure

```
webserv/
├── src/           # Código fuente en C
├── include/       # Archivos de cabecera
├── conf/          # Archivos de configuración de ejemplo
├── logs/          # Logs del servidor
└── README.md
```

---
