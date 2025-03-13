Página de Error 404 Personalizada

Este proyecto proporciona una página de error 404 con un diseño atractivo y animado, ideal para mejorar la experiencia del usuario cuando accede a una URL no válida dentro de un sitio web.

📝 Descripción

La página de error 404 incluye:

Un diseño responsivo y atractivo.

Un fondo animado para una mejor experiencia visual.

Un mensaje claro indicando que la página no está disponible.

Un botón para regresar a la página de inicio.

📂 Estructura del Proyecto

El proyecto incluye los siguientes archivos:

index.html → Estructura HTML de la página 404.

style.css → Estilos CSS para la apariencia y diseño de la página.

🚀 Instalación y Uso

Para utilizar esta página en tu sitio web:

Descargar o Clonar el Repositorio:

git clone https://github.com/tu_usuario/tu_repositorio.git

Colocar los archivos en tu servidor:

Asegúrate de colocar 404.html y style.css en la ubicación correcta dentro de tu sitio web.

Configurar el servidor para redirigir errores 404:

Si usas Apache, agrega esto en tu archivo .htaccess:

ErrorDocument 404 /404.html

Si usas Nginx, puedes configurar tu archivo de configuración:

error_page 404 /404.html;

🎨 Personalización

Puedes modificar el archivo style.css para cambiar colores, fuentes y otros estilos visuales según la identidad de tu sitio web.

Para cambiar la imagen de fondo, edita esta línea en style.css:

background-image: url('URL_DE_TU_IMAGEN');

Para modificar el mensaje de error, edita el contenido de index.html dentro de la clase .contant_box_404.
https://cristianalas.github.io/404-page-not-found/
