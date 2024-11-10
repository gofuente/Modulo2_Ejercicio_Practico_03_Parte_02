
### Ejercicio 3 de Modulo 2 con bootstrap.

El objetivo es desarrollar una pagina web de hospital con  html 5 de acuerdo a los requisitos indicados en la tarea.
Esto contiene despues de utilizar bootstrap.


### Visualizar el proyecto.
Para visualizar el proyecto se puede hacer con visual studio code y ejecutarlo por ejemplo utilizando la extension Live Server.
#### Preparacion previa
Se necesita instalar bootstrap utilizando : npm install bootstrap  desde la raiz del proyecto.



### Estructura del proyecto.
Se compone de los archivos.
- index.html : la pagina de inicio de la clinica. (ruta : raiz)
- equipo_medico.html. la pagina que muestra al equipo medico de la clinica.  (ruta : raiz)
- contacto. La pagina que muestra un formulario para de contacto y una ubicación de la clinica.  (ruta : raiz)
- main.scss. Archivo a partir del cual se genera el archivo main.css que utiliza el proyecto. (ruta : styles)
- _variables.scss. Dispone de las variables utilizadas en otros archivos scss. (ruta : styles\abstract)
- _mixing.scss. Dispone de las funciones utilizadas en otros archivos scss. (ruta : styles\abstract)
- _bootstrap.scss. Dispone de los estilos de bootstrap. (ruta : styles\vendors)
- _buttons.scss. Dispone de los estilos para boton usado en contacto. (ruta : styles\components)
- _header.scss. Dispone de los estilos usado en el encabezado de todas las paginas. (ruta : styles\layout)
- _footer.scss. Dispone de los estilos usado en el pie de pagina de todas las paginas. (ruta : styles\layout)
- _home.scss. Dispone de los estilos usado en la pagina de index.html. (ruta : styles\pages)
- _equipo_medico.scss. Dispone de los estilos usado en la pagina equipo_medico. (ruta : style\pages)
- _contacto.scss. Dispone de los estilos usado en la pagina contacto.hmtl. (ruta : style\pages)
- *.png. Imagenes utilizas en el proyecto. (ruta : assets\img\*)

### Obtencion de imagenes.
Las imagenes se obtuvieron del sitio. https://www.clinicauniversitariabolivariana.org.co/clinica/es/home

### Responsividad.
Se utilizo  @media (max-width) con los siguientes puntos de ruptura : 480px, 768px y 1024px

### Organizacion de estilos.
Se utilizo patrón de organizacion 7-1 y metologia BEM.

### Uso de bootstrap.
## Componentes utilizados
Se utilizaron los siguientes componentes.
-- Forms. Se utilizo en formulario de contacto en archivo contacto.html. (ruta : raiz).
-- Accordion. Se utilizo en la sección de testimonios en archivo index.html. (ruta : raiz).
-- Card. Se utilizo en la sección de servicios en archivo index.html. (ruta : raiz).

## Cambios en bootstrap.
Se utilizo un cambio de variable para que el boton de bootstrap mantuviese el color original de la reserva de cita.
El cambio de variable se realizo en main.scss.
