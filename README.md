# Proyecto CoderHouse - Desarrollo Web - Anima3dPrint
Bienvenido a mi primer repositorio del curso de desarrollo web en CoderHouse.
## Links
##### [Github pages](https://ezequielg07.github.io/ProyectoCoderHouse/)
##### [Netlify](https://62f15abcd23cb409416d5f2f--adorable-bombolone-d91301.netlify.app/)
## Introducción
Este proyecto consiste en un sitio web dedicado a la venta y diseño de productos impresos en tecnología 3D. Está compuesto por 5 páginas: index, nosotros, proyectos, productos y contacto, además se agregó 1 página más llamada "error" que simula un error 404.
## Descripción de las páginas
Todas las páginas del sitio (exceptuando la página de error) poseen un diseño en común, con un background gradiente, el header está compuesto por un logo vectorizado (.SVG) el cual te linkea al "Index" de la web y se le agrego una ligera animación como detalle, el botón "BUSCAR" te deriva a la página de error, el menú incorporado es totalmente responsive y te deriva a las distintas páginas de la web. Por último, se configuro un slider automático con 4 imágenes que van pasando de la primera a la última y viceversa.
En el footer de toda la web hay una breve información ficticia a modo de ejemplo junto con un aviso de derechos reservados y mi nombre como diseñador de la web.
- ### Index
La cara visible del sitio. Tiene distintas secciones que fueron realizadas y organizadas con flexbox y grid, las primeras secciones describen el sitio mediante texto e iconos y se detalla una ubicación ficticia mediante un iframe de Google Maps, la sección de videos esta realizada con carousel de BS y la sección de nuevos ingresos se agregaron cards de BS.
- ### Nosotros
Contiene un accordion de BS dividido en 3 ítems con información de la empresa y una sección que aporta información del equipo mediante cards de BS. Se pueden notar que el texto del accordion tiene una ligera animación de opacidad y las cards del equipo tienen bordes con una animación que varía el color constantemente.
- ### Proyectos
Esta página principalmente describe las posibilidades que existen mediante tecnología 3D e incluye imágenes y párrafos que esta realizado mediante el sistema de grillas de BS para que sea responsive.
- ### Productos
Este parte del sitio es la que más imágenes incluye, esta divido en secciones mediante grid, donde las dos principales es la sección de filtros y la del catálogo. En la parte de filtros hay varios checkbox y botones realizados mediante BS que son dos switch, un dropdown y un offcanvas que cuando se despliega muestra opciones de pago divido en checkbox. En el parte del catálogo está organizado mediante flexbox.
- ### Contacto
Incluye un formulario que está elaborado mediante las opciones de formulario de BS y ajustado mediante el sistema de grillas de BS para que sea responsive.
- ### Error
Es una página que simula un error 404 mediante una imagen y texto amigable relacionado con la temática del proyecto, esta página tiene un diseño similar a las demás a excepción que se le retiro el slider automático y se realizó un cambio en el diseño del logo y la animación haciendo alusión a una falla, este último también esta vectorizado. Se accede mediante el botón "BUSCAR" que se encuentra en el header de todas las páginas del sitio.
## Herramientas utilizadas
- **Bootstrap** (BS)*: Se puede ver como se utilizó bastante de esta herramienta a lo largo de todo el proyecto utilizando sus clases y sistema de grillas.
- **SASS**: muy útil para optimizar código, lo utilicé para organizar las clases del proyecto en carpetas divididas:
- #### *base*
Incluye el archivo _reset que son las clases que resetean el box sizing, tamaño de fuentes y el background de toda la web.
- #### *components*
Incluye los archivos donde están las clases que conforman el header, footer, varias en común y animaciones.
- #### *stylepages*
Esta carpeta se utilizó para dividir las clases de cada página en su propio archivo .scss.
- #### *utilities*
Acá es donde se utilizó con más provecho SASS, utilizado los extends, declarando variables para colores y efectos, como las fuentes también declaradas en el archivo de fonts. Se utilizaron mixins y maps, es estos últimos se encuentran comentario de como se les puede utilizar en el código.
## Archivos agregados
El repositorio incluye los wireframes y el presupuesto solicitados en clase.

