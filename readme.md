---
# yaml-language-server: $schema=schemas\page.schema.json
Object type:
    - Page
Creation date: "2026-05-29T22:21:02Z"
Created by:
    - 'Richard '
Links:
    - files\image_1780101382811_0.png
    - files\image_1780101738992_0.png
    - files\image_1780101489891_0.png
    - files\image_1780101924946_0.png
    - files\image_1780102349819_0.png
    - files\image_1780102493305_0.png
    - files\image_1780102577438_0.png
    - files\image_1780099367287_0.png
    - files\image_1780094783123_0.png
    - files\image_1780094896667_0.png
    - files\image_1780099068087_0.png
    - files\image_1780099088657_0.png
    - files\image_1780099351214_0.png
    - files\image_1780103236655_0.png
    - files\image_1780103355732_0.png
    - files\image_1780103306147_0.png
    - files\image_1780103380707_0.png
    - files\image_1780103218281_0.png
    - files\image_1780103332026_0.png
Emoji: "\U0001F468‍\U0001F4BB"
id: bafyreicw5ys67hzx56iilt2rg5rv26k353ihaeuezj3kacz3asbs5vbvf4
---
# README   
- Integrantes del equipo.   
    - Seth Ricardo Millan Davalos   
    - Adrián Martinez Ortiz   
    - Carlos Alberto González Sosa   
    - Ricardo Hernández Urbina   
   
# Práctica de Testing End-to-End (E2E) con Maestro   
La aplicación seleccionada para esta práctica e**s AgendaPro**, una plataforma enfocada en la gestión de citas, clientes y servicios para negocios como clínicas, spas y centros de estética. Su objetivo principal es optimizar la administración de agendas y mejorar la experiencia de los usuarios mediante una interfaz intuitiva y funcionalidades de automatización.   
## Herramienta utilizada: Maestro   
Para la automatización de pruebas E2E se eligió **Maestro**, una herramienta que destaca por:   
- Su **interfaz gráfica amigable**, que facilita la creación y ejecución de pruebas sin necesidad de escribir código complejo.   
- Su **uso sencillo**, ideal para estudiantes y equipos que buscan implementar pruebas de manera rápida y eficiente.   
- Compatibilidad con aplicaciones web y móviles, lo que permite cubrir diferentes escenarios de prueba.   
   
## Instalación de maestro   
Para instalar Maestro debe de ir a su sitio web [https://maestro.dev/](https://maestro.dev/) . Debes bajar un poco y encontraras el siguiente apartado   
![image_1780101382811_0](files\image_1780101382811_0.png)    
Descarga el .exe e instala la app en la ubicación que desees. Al abrirlo te pedirá abrir o crear una carpeta en la que guardaras tus pruebas.   
![image_1780101738992_0](files\image_1780101738992_0.png)    
Al hacerlo te mostrara la siguiente pantalla.   
![image_1780101489891_0](files\image_1780101489891_0.png)    
En la barra derecha te mostrará los archivos de la carpeta "maestro", en ella hay un pequeño botón donde puedes crear un nuevo archivo. Ahí podrás elegir la extensión del archivo de prueba.   
![image_1780101924946_0](files\image_1780101924946_0.png)    
- yaml: donde defines los flujos E2E.   
- JavaScript: complementa los tests con lógica avanzada o reutilizable.   
- Text: solo es soporte documental, no interactúa con la ejecución.   
   
Dentro del modal podrás poner el nombre, la App ID (link de la pagina) y tags.   
Una vez creado el archivo te diriges al menú izquierdo donde podrás elegir el dispositivo donde harás la prueba (Android, IOS, web).   
![image_1780102349819_0](files\image_1780102349819_0.png)    
Para opciones más avanzadas puedes hacer clic en el engrane.   
![image_1780102493305_0](files\image_1780102493305_0.png)    
Para efectos de esta prueba escogeremos web. Se abrirá una preview del navegador en la que podrás ver que sucede en la prueba y te muestra donde se ubica el botón al que estas haciendo referencia.   
![image_1780102577438_0](files\image_1780102577438_0.png)    
Para iniciar un test debes de dar clic en el botón "Run Test". Al correr se mostrara así en la terminal.   
![image_1780099367287_0](files\image_1780099367287_0.png)    
   
## Flujos automatizados   
En esta sección se describen los **6 flujos significativos** que fueron automatizados dentro de AgendaPro:   
- Registro con datos inválidos   
    - Comprobamos que el registro compruebe que los datos que introducimos sean validos y que no nos permita dejar espacios en blanco, además de analizar que tan claro deja los errores (referente a si aparece algun texto en rojo o algun aviso flotante).   
    - Esta prueba pertenece a la categoría de "Validación de formularios y mensajes de error".   
- Cerrar e Iniciar Sesión   
    - Comprobar el inicio y cierre de sesión funcione correctamente.   
    - Esta prueba pertenece a la categoría de "Inicio y cierre de sesión".   
- Navegación entre los menús   
    - Esta prueba pertenece a la categoría de "Navegación entre módulos o pantallas".   
- Crear y eliminar un servicio   
    - Esta prueba pertenece a la categoría de "Creación, edición o eliminación de información" y "Procesos principales del sistema"   
- Crear y eliminar una cita   
    - Esta prueba pertenece a la categoría de "Creación, edición o eliminación de información" y "Procesos principales del sistema"   
- Crear y eliminar un cliente   
    - Esta prueba pertenece a la categoría de "Creación, edición o eliminación de información" y "Procesos principales del sistema"   
   
   
## Demostración de ejecución   
Se incluye evidencia de la ejecución de las pruebas E2E realizadas con Maestro:   
- Registro con datos invalidos   
    ![image_1780094783123_0](files\image_1780094783123_0.png)    
    ![image_1780094896667_0](files\image_1780094896667_0.png)    
- Cerrar e Iniciar sesión   
    ![image_1780099068087_0](files\image_1780099068087_0.png)    
    ![image_1780099088657_0](files\image_1780099088657_0.png)    
- Navegación entre los menús   
    ![image_1780099351214_0](files\image_1780099351214_0.png)    
    ![image_1780099367287_0](files\image_1780099367287_0.png)    
- Crear y eliminar un servicio   
    ![image_1780103236655_0](files\image_1780103236655_0.png)    
    ![image_1780103355732_0](files\image_1780103355732_0.png)    
- Crear y eliminar un cita   
    ![image_1780103306147_0](files\image_1780103306147_0.png)    
    ![image_1780103380707_0](files\image_1780103380707_0.png)    
- Crear y eliminar un cliente   
    ![image_1780103218281_0](files\image_1780103218281_0.png)    
    ![image_1780103332026_0](files\image_1780103332026_0.png)    
   
   
