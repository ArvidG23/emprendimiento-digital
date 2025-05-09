# Proyecto Página Web de Skates

Este es un proyecto de página web personal en el que voy a ofrecer y vender skates. La página incluye diferentes planes con precios y servicios. Está diseñada con un enfoque atractivo y moderno, con la idea de proporcionar información detallada sobre los productos y planes disponibles.

## Requisitos del Proyecto

### 🔹 **1. Agregar imágenes en las tarjetas de precios**
Cada tarjeta de servicio (plan básico, estándar y premium) incluirá una imagen en la parte superior, mostrando una representación visual de los planes. Las imágenes se encuentran en la carpeta `img/` con los siguientes nombres:
- plan_basico.jpg
- plan_estandar.jpg
- plan_premium.jpg

### 🔹 **2. Incorporar botones de acción**
Cada tarjeta de servicio tendrá un botón de "Más Información" que redirigirá a una nueva página HTML en la carpeta `pages/`. El botón tendrá las siguientes características:
- Fondo de color.
- Hover para un efecto visual de cambio de color.
- Bordes redondeados para hacerlo más llamativo.

### 🔹 **3. Crear nuevas páginas para cada plan**
Cada plan tendrá su propia página con la siguiente estructura:
- **Encabezado `<h1>`** con el nombre del plan.
- Imagen ilustrativa del plan.
- Mínimo dos párrafos descriptivos explicando los beneficios del plan.
- Un enlace o botón para volver a la página `servicios.html`.

Las páginas a crear son:
- plan_basico.html
- plan_estandar.html
- plan_premium.html

### 🔹 **4. Implementar nuevos estilos CSS**
Se aplicarán los siguientes estilos a diferentes elementos de la página:
- **Botones:**
  - Fondo verde, texto blanco, bordes redondeados.
  - Efecto hover que cambia el color.
  - Transición suave entre los diferentes estados de los botones.

- **Imágenes en las tarjetas:**
  - Ocupan todo el ancho de la tarjeta.
  - Altura fija de 150px aproximadamente.
  - Asegurarse de que las imágenes se ajusten sin deformarse (utilizando `object-fit: cover`).

- **Diseño de nuevas páginas de planes:**
  - Un contenedor centrado, con un ancho máximo de 800px.
  - Fondo blanco con bordes redondeados y una sombra sutil (`box-shadow`).
  - Textos centrados para mayor claridad.

- **Diseño Responsivo:**
  - Las tarjetas se apilarán verticalmente en pantallas con un ancho menor a 768px.

### 🔹 **Otros diseños:**
- Fijar el footer en la parte inferior de la página, de modo que siempre esté visible en el borde inferior del navegador.
- Personalizar los colores y otros estilos para hacer el diseño más acorde a mi gusto personal.
  
## Estructura del Proyecto:

- **index.html** – Página principal de presentación.
- **servicios.html** – Página que muestra los servicios disponibles y los planes.
- **nosotros.html** – Página con información sobre el proyecto y quién está detrás.
- **css/** – Carpeta con los estilos (archivo `estilos.css`).
- **img/** – Carpeta con las imágenes de los planes y otras gráficas.
- **pages/** – Carpeta con las páginas para los planes específicos:
  - plan_basico.html
  - plan_estandar.html
  - plan_premium.html
- **README.md** – Descripción general del proyecto.

Este proyecto tiene como objetivo ser una plataforma simple y efectiva para la venta de skates y planes asociados, con un diseño atractivo y fácil de navegar.
