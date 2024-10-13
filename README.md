# Manu Martínez - Portfolio

## Descripción

Este proyecto es una página de **portfolio** personal diseñada para destacar mis habilidades y experiencia como desarrollador en formación y editor de vídeo. La página incluye una introducción, una sección de habilidades, proyectos anteriores y una página de contacto.

El uso de **ChatGPT** ha sido crucial en el desarrollo del menú **hamburguesa**, también de los **comentarios** de cada una de las funcionalidades, lo que me ha permitdo no perderme en el proyecto conforme este crecía, así como en la creación de este mismo README.

## Tabla de Contenidos

- [Estructura del Proyecto](#estructura-del-proyecto)
- [Características Principales](#características-principales)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instrucciones de Instalación](#instrucciones-de-instalación)
- [Uso del Proyecto](#uso-del-proyecto)
- [Contribución](#contribución)
- [Contacto](#contacto)

---

## Estructura del Proyecto

El proyecto se compone de las siguientes páginas y archivos de estilo:

1. **index.html**: Página principal con una introducción sobre mí y una sección de habilidades.
2. **contact.html**: Página de contacto donde los usuarios pueden enviarme un formulario.
3. **projects.html**: Página con una galería de proyectos en los que he trabajado.
4. **normalize.css**: Normaliza los estilos predeterminados en todos los navegadores.
5. **vars.css**: Contiene las variables de CSS que unifican los colores y las fuentes.
6. **common.css**: Estilos comunes a todas las páginas.
7. **burger.css**: Estilos específicos para el menú hamburguesa, importante para la versión móvil.
8. **footer.css**: Estilos para el pie de página.
9. **banner.css**: Define los estilos para la sección de banner o portada de la página principal, incluyendo el texto de bienvenida y las imágenes destacadas. Utiliza imágenes de fondo y técnicas de posicionamiento para asegurar una presentación visualmente atractiva.  
10. **components.css**: Contiene los estilos para los componentes reutilizables de la página, como botones, tarjetas y contenedores de contenido. Estos estilos aseguran la coherencia visual entre todas las secciones.
11. **contact.css**: Estilos específicos para el formulario de contacto en la página de contacto. Incluye la disposición de los campos de entrada, mensajes de error y la presentación general del formulario.
12. **footer.css**: Define el estilo del pie de página en todas las páginas, incluyendo la disposición de los iconos de redes sociales, enlaces importantes y la sección de derechos de autor.
13. **header.css**: Contiene los estilos del encabezado de todas las páginas. Incluye el logotipo, el menú de navegación principal y el estilo del menú hamburguesa en la versión móvil.
14. **info.css**: Estilos específicos para las secciones informativas sobre mí, como la biografía y las descripciones de las habilidades en la página principal.
15. **projects.css**: Define los estilos de la galería de proyectos, estableciendo el diseño de las tarjetas de proyecto, los efectos al pasar el ratón sobre ellas, y la disposición general de la galería.
16. **skills.css**: Estilos específicos para la sección de habilidades. Incluye el diseño de la lista de habilidades, los iconos de tecnologías, y la presentación de barras de progreso que muestran el nivel de experiencia en cada habilidad. La elección de mantener las líneas en vertical aún en la versión desktop es intencional en pro de la armonía con el fondo.


## Características Principales

### 1. **Menú Hamburguesa**

- El menú hamburguesa permite una navegación sencilla en dispositivos móviles. Al hacer clic en el icono, se despliega el menú con opciones de navegación.
- **ChatGPT** fue fundamental para entender cómo implementar el menú correctamente.
  
### 2. **Formulario de Contacto**

- Incluye validaciones básicas de campos como **nombre**, **apellido** y **número de teléfono**.
- La sección "How did you find me?" está diseñada verticalmente para ajustarse mejor al diseño general.

### 3. **Sección de Proyectos**

- Se utiliza una galería visual donde cada proyecto tiene una imagen representativa y un breve título descriptivo.
- Un video de introducción también está presente para mostrar mis trabajos como editor.

### 4. **Footer**

- El footer incluye enlaces a mis redes sociales: GitHub, LinkedIn e Instagram, con iconos personalizados.
- Todo el contenido dentro del footer tiene estilos personalizados que respetan los colores definidos en `vars.css`.

## Tecnologías Utilizadas

- **HTML5**: Para la estructura del contenido.
- **CSS3**: Para el diseño, con uso de variables y flexbox.
- **Normalize.css**: Para la estandarización del estilo en navegadores.

## Para un correcto funcionamiento en Pages
- Para el correcto funcionamiento de del repositorio en GitHub pages tuve que cambiar la ubicación del proyecto en local eliminando la carpeta "z-practica" haciendo que la carpeta principal sea del mismo nombre que el root que establecía GitHub(practica-html)
- Por algún motivo, Github no reconocía las imágenes que empezaban con "_" por lo que cambié el nombre de todas las imágenes quitando el guión bajo.


## Instrucciones de Instalación

1. Clona el repositorio:

```bash
git clone https://github.com/Manu-MMN/portfolio.git
