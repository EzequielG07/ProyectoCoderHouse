# Proyecto CoderHouse - Desarrollo Web - Anima3dPrint
Bienvenido a mi primer repositorio del curso de desarrollo web en CoderHouse.
## Links
##### [Github pages](https://ezequielg07.github.io/ProyectoCoderHouse/)
##### [Netlify](https://62f15abcd23cb409416d5f2f--adorable-bombolone-d91301.netlify.app/)
## Introducción
Este proyecto consiste en un sitio web dedicado a la venta y diseño de productos impresos en tecnología 3D. Esta compuesto por 5 páginas: index, nosotros, proyectos, productos y contacto, además se agrego 1 página más llamada "error" que simula un error 404.
## Descripción de las páginas
- ### Index
La cara visible del sitio. Tiene distintas secciones que fueron realizadas y organizadas con flexbox y grid, las primeras secciones describen el sitio mediante texto e iconos y se detalla una ubicación ficticia mediante un iframe de Google Maps, la sección de videos esta realizada con carousel de BS y la sección de nuevos ingresos se agregaron cards de BS.
- ### Nosotros
Contiene un accordion de BS dividido en 3 items con información de la empresa y una sección que aporta información del equipo mediantes cards de BS. Se pueden notar que el texto del accordion tiene una ligera animación de opacidad y las cards del equipo tienen bordes con una animación que varia el color constantemente.
- ### Proyectos
Esta página principalmente describe las posibilidades que existen mediante tecnología 3D e incluye imágenes y párrafos que esta realizado mediante el sistema de grillas de BS para que sea responsive.
- ### Productos
Este parte del sitio es la que más imágenes incluye, esta divido en secciones mediante grid, donde las dos principales es la sección de filtros y la del catálogo. En la parte de filtros hay varios checkbox y botones realizados mediante BS que son dos switch, un dropdown y un offcanvas que cuando se despliega muestra opciones de pago divido en checkbox. En el parte del catálogo esta organizado mediante flexbox.
- ### Contacto
Incluye un formulario que esta elaborado mediante las opciones de formulario de BS y ajustado mediantes el sistema de grillas de BS para que sea responsive.
- ### Error
Es una página que simula un error 404 mediante una imágen y texto amigable relacionado con la temáica del proyecto. Se accede mediante el botón "BUSCAR" que se encuentra en el header de todas las páginas del sitio.
## Herramientas utilizadas
- **Bootstrap** (BS)*: Se puede ver como se utilizo bastante de esta herramienta a lo largo de todo el proyecto utilizando sus clases y sistema de grillas.
- **SASS**: muy útil para optimizar código, lo utilize para organizar las clases del proyecto en carpetas divididas:
- #### *base*
Incluye el archivo _reset que son las clases que resetean el box sizing, tamaño de fuentes y el background de toda la web.
- #### *components*
Incluye los archivos donde estan las clases que conforman el header, footer, varias en común y animaciones.
- #### *stylepages*
Esta carpeta se utilizo para dividir las clases de cada página en su propio archivo .scss.
- #### *utilities*
Aca es donde se utilizo con mas provecho SASS, utilizado los extends, declarando variables para colores y efectos, como las fuentes también decladas en el archivo de fonts. Se utilizaron mixins y maps donde se encuentran comentados como se las puede utilizar en el código.
## Archivos agregados
El repositorio incluye los wireframes y el presuesto solicitados en clase.
