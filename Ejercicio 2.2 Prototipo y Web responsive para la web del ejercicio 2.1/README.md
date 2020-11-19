## Ejercicio 2.2 Prototipo y Web responsive para la web del ejercicio 2.1
Basada en la web del ejercicio anterior se pide realizar prototipos y webs responsive para la versión móvil del ejercicio 2.1 , adaptada para pantallas de tablets y PC.

Para ello debes crear, un sketch en papel (se entregarán fotos), un wireframe navegable realizado en Axure (se entregará mediante archivo y enlace) y una web HTML y CSS (se entregarán los archivos mediante enlace a GitHub), siguiendo las siguientes directrices:

- sketch: dibujo del esquema de bloques y ubicaciones de contenido que conformarán la web en sus distintas versiones.

- wireframe: una maqueta navegable con más fidelidad y detalle en cuanto a contenidos que el sketch reflejando las visualizaciones en diferentes versiones usando masters (para cabecera y footer, al menos) y repeaters (para listado de Módulos y tareas, al menos).

- Web en HTML y CSS, basada en los prototipos anteriores (ya está hecha la versión móvil en el ejercicio 2.1) en versiones tablet (usar posicionamiento flex) y PC (usar posicionamiento grid) a las cuales, se añadirán más contenidos (imágenes, decoraciones en bordes, fondos, estados, efectos de transiciones, animaciones, transformaciones y otros elementos HTML y CSS a tu elección). No se usará Bootstrap.

La entrega de este ejercicio se realizará mediante un enlace a un repositorio de GitHub.
<br>

### Elementos añadidos al html 
- Enlaces externos al css con uso de media queries en los links en las líneas 18,19,20.
- 3 img en el header, líneas 44 a 48.
- División .sobreMi en bloque1 y bloque2 líneas 63 y 72.
- Cambio de h2 por h3 y añado class para añadirle efecto visual a los títulos línea 130.
- Cambio de .fot1 por otro contenedor del footer con una animación líneas 271 a 276.

### Dispositivo de moviles en css small
- He tenido que hacer unas cuantas modificaciones en el css para añadirle estilos nuevos, para que se vea acorde a las animaciones añadidas en los otros archivos css, además del uso de flex, solamente en aquellas animaciones que son necesarias para su correcta visualización.
- También he tenido que modificar algunas clases css e id debido a los cambios que he realizado en el html.
### Dispositivo de tablet uso de Flex en css tablet
- Uso de display:flex líneas (19,39,110,145,233,293,338).
- flex-wrap líneas (20,111,234).
- justify-content líneas (40,146,294,339).
- align-items líneas (41,147,295,340).
- align-self línea 51.
- order líneas (116,122,138).

### Dispositivo de PC uso de Grid en css pc
- Display:grid líneas (22,46,86,128,263,381).
- grid-template-areas líneas (23,).
- grid-area líneas (30,38,83).
- grid-template-columns líneas (47,87,129,264,382).
- uso de repeat línea (47,87).
- grid-colum-gap líneas (88,266).
- grid-row-gap línea 267.
- justify-self líneas (89,147,172).
- align-items líneas (90,132,384).
- grid-template-rows líneas (130,265).
- justify-items líneas (131,268,383).
- grid-colum líneas (137,143,170).
- grid-row líneas (138,144,171).

### Uso de Animaciones, transiciones y transformaciones en los 3 tipos de dispositivos
- Animación sobre h3 de la web index
- Transición sobre boton ftp de web index 
- Transición y transformación sobre tarjetas  de proyectos de web index
- Transición sobre boton de proyectos en las tarjetas de web index
- Transformación y transición sobre mi nombre en el footer