# Puntos de la documentación

A continuación se enumeran los puntos
que debe tener la documentación del 2do Parcial.

## Parte I. Fundamentación teórica

### 1. Ingeniería de Software Asistida por Computadora
### 2. Desarrollo de Software Basado en Componentes
### 3. Arquitectura del Software

### 4. Ingeniería Humana

Hablar sobre el desarrollo de software amigable, fácil de usar, UX (experiencia de usuario).

El objetivo es desarrollar software para que lo puedan usar seres humanos.

### 5. IA aplicada al desarrollo de software
### 6. Scrum
### 7. Modelo C4
### 8. UML
### 9. Aplicaciones móviles
### 10. Flutter

## Parte II. Registro del proceso de desarrollo

Documentar el proceso de desarrollo aplicando Scrum,
siguiendo los puntos de la guía que nos da el docente en la Plataforma,
y que se puede consultar abriendo el siguiente enlace:

<a href="https://presencial.uagrm.edu.bo/pluginfile.php/4029333/mod_resource/content/3/EnfoqueScrumSmainn.pdf" target="_blank">https://presencial.uagrm.edu.bo/pluginfile.php/4029333/mod_resource/content/3/EnfoqueScrumSmainn.pdf</a>

Para modelar la arquitectura del software usar los 
<a href="https://c4model.com/diagrams#static-structure-diagrams" target="_blank">
diagramas del modelo C4
</a>
.

Usar UML para todos los demás modelos.

Durante el proceso de desarrollo se debe hacer al menos estos cuatro modelos:

1. **Modelo de arquitectura.**
    * Para modelar la arquitectura del software se debe usar el <a href="https://c4model.com/introduction#maps-of-your-code" target="_blank">modelo C4</a>.
    * En el modelo C4, el modelo de la arquitectura del software se expresa mediante <a href="https://c4model.com/diagrams/system-context" target="_blank">diagramas de contexto</a>, de <a href="https://c4model.com/diagrams/container" target="_blank">contenedores</a>, de <a href="https://c4model.com/diagrams/component">componentes</a> y de <a href="https://c4model.com/diagrams/code" target="_blank">código</a>.
2. **Modelo de datos.**
    * El modelo de datos no es más que el modelo de la base de datos.
    * El modelo de la base de datos es el mismo que se realiza en Base de Datos I.
    * Hacer el modelo de la base de datos es hacer los siguientes tres modelos:
        * **Modelo conceptual**, expresado como un diagrama de clases.
        * **Modelo lógico**, expresado como tablas resultado de mapear las clases del modelo conceptual a tablas del modelo relacional de la base datos. Estas tablas muestran el nombre de la tabla, sus atributos y cuáles atributos son llaves primarias (_primary keys_) y cuáles son llaves foráneas (_foreign keys_).
        * **Modelo físico**, expresado como el código SQL necesario para crear la base de datos en el gestor de base de datos del software. *IMPORTANTE*: Para el 2do Parcial el docente exige utilizar un gestor de bases de datos como PostgreSQL o superior. No usar MySQL.
3. **Modelo de procesos.** 
    * No es necesario modelar todos los procesos del software.
    * Modelar únicamente los procesos que tienen una lógica no trivial.
    * Por ejemplo, no es necesario modelar la lógica para hacer operaciones tipo CRUD (create, read, update, delete) sobre la base de datos.
    * Para modelar los procesos se pueden usar diagramas UML, como: <a href="https://github.com/imalitavakoli/learn-uml2?tab=readme-ov-file#sequence-diagram" target="_blank">diagramas de secuencia</a>, de <a href="https://github.com/imalitavakoli/learn-uml2?tab=readme-ov-file#state-machine-diagram" target="_blank">estados</a>, de <a href="https://github.com/imalitavakoli/learn-uml2?tab=readme-ov-file#timing-diagram" target="_blank">tiempo</a>, etc.
4. **Modelo de interfaces.**
    * Es el modelo de las interfaces de usuario.
    * Pueden expresarse como bocetos, prototipos o _mockups_ realizados
      usando herramientas como Figma o [draw.io](./../tecnología/para-el-análisis-y-diseño/drawio/).

## Parte III. Manual de usuario

