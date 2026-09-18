# Brian Escalante | Desarrollador Web

Desarrollador web enfocado en la creación de sitios web, landing pages y aplicaciones web responsive.

Trabajo tanto en la parte visual como en la funcionalidad de los proyectos, utilizando tecnologías frontend y backend, bases de datos, autenticación de usuarios y paneles administrativos.

---

## 🏠 Plataforma Web de Bienes Raíces

Aplicación web completa para la publicación, consulta y administración de propiedades inmobiliarias.

El proyecto cuenta con una interfaz pública para los visitantes y un sistema administrativo privado para gestionar propiedades y vendedores. Fue desarrollado utilizando arquitectura MVC, PHP 8 y MySQL, integrando operaciones CRUD y autenticación de usuarios.

### Características principales

- Página principal responsive
- Catálogo de propiedades
- Propiedades destacadas
- Información detallada de inmuebles
- Sección Nosotros
- Blog
- Testimoniales
- Formulario de contacto
- Inicio y cierre de sesión
- Autenticación de usuarios
- Panel de administración
- Registro de propiedades
- Actualización y eliminación de propiedades
- Gestión de vendedores
- Carga y actualización de imágenes
- Persistencia de información mediante MySQL
- Arquitectura MVC

### Tecnologías utilizadas

**PHP 8 · MySQL · JavaScript · HTML5 · SCSS · MVC**

---

## 📸 Recorrido del proyecto

### 🏡 1. Página principal

Página de inicio del sitio inmobiliario, con presentación visual de la plataforma y acceso a las principales secciones.

![Página principal de Bienes Raíces](bienes_raices%20%288%29.png)

---

### 🏘️ 2. Propiedades destacadas

Sección de la página principal donde se muestran algunas de las propiedades disponibles con imagen, precio y características principales.

![Propiedades destacadas](bienes_raices%20%2812%29.png)

---

### 🔎 3. Catálogo de propiedades

Vista completa de las propiedades disponibles. Cada inmueble presenta fotografía, descripción, precio, habitaciones, baños y estacionamientos.

![Catálogo de propiedades](bienes_raices%20%281%29.png)

---

### 👥 4. Nosotros

Sección informativa del sitio que presenta información de la empresa y características de sus servicios.

![Sección Nosotros](bienes_raices%20%287%29.png)

---

### 📰 5. Blog

Página destinada a la publicación de artículos relacionados con bienes raíces, propiedades y decoración.

![Blog de Bienes Raíces](bienes_raices%20%286%29.png)

---

### 💬 6. Blog, contacto y testimoniales

Sección complementaria de la página principal que integra artículos recientes, llamada a la acción y testimonios de clientes.

![Blog y testimoniales](bienes_raices%20%2813%29.png)

---

### 📩 7. Formulario de contacto

Formulario que permite al visitante solicitar información, seleccionar una propiedad y proporcionar su presupuesto.

![Formulario de contacto](bienes_raices%20%289%29.png)

---

# 🔐 Sistema administrativo

Además del sitio público, el proyecto cuenta con un sistema privado para la administración de propiedades y vendedores.

### 🔑 8. Inicio de sesión

Acceso al área administrativa mediante correo electrónico y contraseña.

![Inicio de sesión](bienes_raices%20%283%29.png)

---

### ⚙️ 9. Panel de administración

Panel desde el cual el administrador puede consultar las propiedades y vendedores registrados, además de crear, actualizar o eliminar información.

![Panel de administración](bienes_raices%20%2810%29.png)

---

### ➕ 10. Registro de propiedades

Formulario para agregar nuevas propiedades al sistema, incluyendo título, precio, imagen, descripción, habitaciones, baños, estacionamiento y vendedor asociado.

![Crear propiedad](bienes_raices%20%282%29.png)

---

### ✏️ 11. Actualización de propiedades

El administrador puede modificar los datos de una propiedad existente y guardar los cambios directamente en la base de datos.

![Actualizar propiedad](bienes_raices%20%2811%29.png)

---

### 👤 12. Registro de vendedores

El sistema permite registrar vendedores y asociarlos posteriormente con las propiedades.

![Registrar vendedor](bienes_raices%20%285%29.png)

---

### 🔄 13. Actualización de vendedores

Los datos de los vendedores registrados también pueden modificarse desde el área administrativa.

![Actualizar vendedor](bienes_raices%20%284%29.png)

---

## 🧩 Funcionalidad del sistema

La plataforma integra frontend y backend dentro de una arquitectura MVC. Las propiedades y vendedores son almacenados en una base de datos MySQL y pueden ser administrados mediante operaciones CRUD.

El área administrativa permite controlar el contenido del sitio sin modificar directamente el código, incluyendo altas, consultas, actualizaciones y eliminación de registros.

Este proyecto demuestra el desarrollo de una aplicación web completa, desde la interfaz pública hasta la lógica del servidor, autenticación, administración y persistencia de datos.

---

## 💈 Sistema de Barbería y Gestión de Citas

Aplicación web desarrollada para la administración de usuarios y gestión de citas de una barbería.

El sistema cuenta con registro de usuarios, autenticación mediante correo electrónico y contraseña, recuperación de contraseña y confirmación de cuentas mediante correo electrónico.

La aplicación fue desarrollada utilizando arquitectura MVC, PHP 8 y MySQL, separando la lógica de negocio, las vistas y el acceso a los datos.

### Características principales

- Creación y registro de usuarios
- Inicio y cierre de sesión
- Autenticación mediante correo electrónico y contraseña
- Contraseñas almacenadas de forma segura mediante hash
- Confirmación de cuentas mediante correo electrónico
- Generación de tokens de confirmación
- Recuperación y restablecimiento de contraseña
- Envío de instrucciones mediante correo electrónico
- Validación de formularios
- Sistema de alertas y mensajes
- Base de datos MySQL
- Arquitectura MVC
- Diseño responsive

### Tecnologías utilizadas

**PHP 8 · MySQL · HTML5 · SCSS · JavaScript · MVC · Composer · PHPMailer**

---

## 📸 Sistema de usuarios

### 🔐 1. Inicio de sesión

Pantalla principal de autenticación. Los usuarios registrados pueden acceder al sistema utilizando su correo electrónico y contraseña.

Desde esta misma interfaz se proporciona acceso al registro de una nueva cuenta y al sistema de recuperación de contraseña.

![Inicio de sesión - Barbería](barberia%20%281%29.png)

---

### 👤 2. Creación de cuenta

Formulario de registro para crear una nueva cuenta proporcionando nombre, apellido, teléfono, correo electrónico y contraseña.

Una vez realizado el registro, el sistema genera la información necesaria para el proceso de confirmación de la cuenta mediante correo electrónico.

![Crear cuenta - Barbería](barberia%20%283%29.png)

---

### 🔑 3. Recuperación de contraseña

Sistema de recuperación de contraseña mediante correo electrónico.

El usuario introduce el correo asociado a su cuenta y el sistema puede enviar las instrucciones necesarias para continuar con el proceso de restablecimiento de contraseña.

![Recuperar contraseña - Barbería](barberia%20%282%29.png)

---

## 📧 Autenticación y correo electrónico

El sistema utiliza **PHPMailer** para gestionar el envío de correos electrónicos relacionados con la autenticación de usuarios.

Durante el registro se genera un token asociado al usuario para realizar la confirmación de la cuenta. El sistema también utiliza tokens para controlar el proceso de recuperación y restablecimiento de contraseña.

Las plantillas enviadas por correo electrónico utilizan HTML para presentar la información al usuario de forma estructurada.

---

## 🧩 Arquitectura del proyecto

La aplicación utiliza una arquitectura **MVC (Modelo - Vista - Controlador)** para mantener organizada la lógica del sistema.

Los usuarios son almacenados en una base de datos **MySQL**, mientras que PHP gestiona procesos como autenticación, validación, creación de cuentas, confirmación mediante token y recuperación de contraseñas.

Esta estructura permite separar la interfaz, la lógica de negocio y el acceso a los datos, facilitando el mantenimiento y crecimiento de la aplicación.

---

## 🛠️ Tecnologías y herramientas

- HTML5
- CSS3 / SCSS
- JavaScript
- PHP 8
- MySQL
- MVC
- WordPress
- Git
- GitHub
- Composer
- PHPMailer
- Gulp
- Diseño Responsive

---

## 📩 Contacto

Disponible para proyectos de desarrollo web, landing pages, sitios empresariales y aplicaciones web.
