# Documentación del Laboratorio de Login en Laravel

## Universidad Tecnológica de Panamá
**Facultad de Ingeniería de Sistemas Computacionales**  
**Campus Víctor Levi Sasso**  
**Asignatura:** Desarrollo Web  
**Instructora del laboratorio:** Ing. Irina Fong  

---

## Introducción

El presente laboratorio tuvo como propósito desarrollar un primer acercamiento al framework Laravel, comprendiendo su estructura de trabajo y su organización bajo el patrón Modelo–Vista–Controlador (MVC). Durante la práctica se configuró el entorno de desarrollo, se preparó la conexión con la base de datos, se ejecutaron las migraciones necesarias y se implementó el módulo de autenticación con las vistas de login y registro.

Laravel permite organizar mejor una aplicación web mediante la separación de responsabilidades. Los modelos representan la lógica y la interacción con la base de datos, las vistas muestran la interfaz con la que interactúa el usuario, los controladores gestionan la lógica de las peticiones, y las rutas conectan las URL con la funcionalidad correspondiente. Esta arquitectura facilita el mantenimiento, la reutilización del código y una mejor organización del proyecto. Esta explicación se basa en la finalidad del laboratorio y en la instrucción de documentar las principales carpetas en torno a MVC. :contentReference[oaicite:1]{index=1} :contentReference[oaicite:2]{index=2}

---

## Objetivo del laboratorio

Implementar un sistema básico de autenticación en Laravel que permitiera el acceso a las vistas de login y registro, comprendiendo al mismo tiempo la estructura del framework y la función de sus componentes principales bajo el modelo MVC. Este objetivo se sustenta en la guía del laboratorio y en el documento de documentación del repositorio. :contentReference[oaicite:3]{index=3} :contentReference[oaicite:4]{index=4}

---

## Requisitos previos

Para la ejecución del laboratorio se utilizaron o se requerían los siguientes elementos:

- PHP versión 8.0 o superior
- Composer
- Laravel
- Entorno de desarrollo local como WAMP, XAMPP o Laragon
- Servidor web Apache o Nginx
- Base de datos MySQL o MariaDB
- Editor de código, preferiblemente Visual Studio Code
- NPM, para la instalación y compilación de dependencias del front-end
- Sistema operativo Windows

Estos requisitos fueron solicitados en el documento de documentación y además la guía indica que Laravel necesita un entorno como XAMPP o WAMP y Composer para descargar dependencias. :contentReference[oaicite:5]{index=5} :contentReference[oaicite:6]{index=6}

---

## Estructura principal del proyecto en Laravel

### app
Contiene la lógica principal de la aplicación, incluyendo controladores y otros componentes internos del sistema.

### routes
Contiene la definición de rutas que permiten enlazar las URL con la lógica del sistema.

### resources/views
Contiene las vistas del proyecto, es decir, las páginas que se muestran al usuario, como login y register.

### database
Incluye migraciones, seeders y otros archivos relacionados con la estructura de la base de datos.

### public
Es la carpeta pública desde la cual se sirve la aplicación en el navegador.

### config
Contiene los archivos de configuración general del proyecto.

La inclusión de esta explicación está pedida de forma explícita en el documento de documentación, donde se solicita una introducción que explique las carpetas principales en torno a MVC: controladores, rutas, vistas y modelos. :contentReference[oaicite:7]{index=7}

---

## Flujo de comandos utilizados

A continuación, se documenta el flujo principal utilizado durante el laboratorio, siguiendo la guía proporcionada:

```bash
laravel new AhorasiLaravel
If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
