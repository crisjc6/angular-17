# angular-17

# !Bienvenido a Angular 17 Parte 1

En este curso, te sumergirás en el mundo de **Angular** para dominar la creación de aplicaciones web dinámicas. Aprenderás a construir proyectos del mundo real utilizando **Angular**, la última versión de esta potente herramienta. **Angular** te permite desarrollar aplicaciones web escalables, que se adaptan dinámicamente al contenido según las interacciones del usuario. Prepárate para llevar tus habilidades de desarrollo web al siguiente nivel con [Angular 17](enlace-al-curso).

## Introducción
### ¿Qué es Angular?

[img-angular]

**Angular** es una plataforma de desarrollo y framework. Una plataforma de desarrollo proporciona una gama de herramientas integradas para ayudar a escribir, previsualizar y desplegar tus proyectos. Un framework es una estructura sobre la que puedes construir y personalizar, lo que nos permite codificar mucho más rápido y enfocarte de inmediato en lo que hace única a tu aplicación.

Según Geek for Geeks, "un framework es una estructura para el proceso de desarrollo con la ayuda de un framework, puedes evitar escribir todo desde cero".

Tres grandes beneficios de Angular son:

- **Versatilidad**: Puedes construir cualquier cosa, desde aplicaciones simples hasta sistemas más grandes y complejos. Angular proporciona la flexibilidad necesaria para adaptarse a diferentes escalas de proyectos.

- **Eficiencia en el desarrollo**: Gracias a sus herramientas integradas y su arquitectura bien pensada, puedes desarrollar más rápido y con menos errores. Angular simplifica tareas comunes y promueve las mejores prácticas de desarrollo.

- **Comunidad y soporte**: Angular se mantiene activamente con actualizaciones regulares y tiene una gran comunidad de desarrolladores. Además, al ser creado por Google, cuenta con un respaldo sólido. Es utilizado por miles de marcas exitosas, desde Xbox hasta HBO y BMW, lo que demuestra su confiabilidad y capacidad para manejar proyectos de gran envergadura.
### Configuración
[img]('node, npm cli')

Para instalar en tu sistema local, primero necesitas tener Node.js y npm instalados. Luego, para trabajar con Angular, es necesario instalar Angular CLI (Interfaz de Línea de Comandos de Angular), que se utiliza para realizar diversas operaciones, como crear y ejecutar aplicaciones, probar y desplegar.

Para instalar Angular CLI, ejecuta el siguiente comando dentro de tu terminal (ya sea cmd en Windows o consola bash en sistemas Unix):

```bash
npm install -g @angular/cli
```
**Crear una nueva aplicación**
Para crear una nueva aplicación necesitamos usar el comando `ng new noteMaster` esto creara todos los archivos y carpetas para nuestra aplicación angular.

Para ejecutar nuestro proyecto necesitamos navegar hasta la carpeta del proyecto y ejecutar `ng serve --open`

```bash
cd noteMaster
ng serve --open
```
### Estructura de archivos
Los proyectos en angular estan compuestos por varios archivos en esta sección vamos a explorar la estructura de los archivos de una proyecto angular

![Estructura angular](/assets/estructura-ng.jpeg)

Los archivos fuente residen en el subdirectorio `src/.`
* `index.html` es el HTML principal de la aplicación
* `main.ts` es el punto de entrada de tu aplicación y se ejecuta cuando se lanza tu aplicación
* `styles.css` es el archivo CSS principal, que incluye los estilos para tu aplicación

![Estructura app angular](/assets/estructura-app-ng.jpeg)
La carpeta `app` incluye como archivos principales a: 
    `app.component.ts` y `app.component.html`
Representan el **Componente Raiz** de nuestro proyectos.
### Proyecto: creación
Adelante abre el proyecto y explora la estructura del proyecto en el que trabajaremos en este curso.
Asi mismo podrias crear tu propio proyecto, en el siguiente módulo agregaras funcionalidad continua...

## Básicos de Angular Parte 2
### Componentes
### Templates
### Data binding
### Eventos
### Directivas
### Proyecto: Listado de notas


## Formularios en Angular Parte 3 (Forms)
### Formularios basados en [(ngModule)]
### Validaciones
### Formularios Reactivos 
### Proyecto: Agregar notas

## Enrutamiento y navegación Parte 4 (routing)
### Configuración routing
### Navegación angular
### Proyecto: Abrir nota
### Notas finales

