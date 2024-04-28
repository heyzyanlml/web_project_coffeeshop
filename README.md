# Triple Espresso

## Descripción del proyecto y su funcionalidad.

Este es el proyecto final del Sprint 4 del Curso de Web Development de Tripleten. El objetivo de este proyecto que se realizó en cuatro etapas fue construir una página principal en la cuál:

- Podamos tener una sección que sirva para darle de manera rápida contexto e información al usuario acerca de la página (De qué se trata, horarios, ubicación), incluyendo una barra de navegación funcional que redirige a las secciones correspondientes.
- Una sección de Recetas, donde agregamos videos de recetas de métodos de café para recomendar al usuario para hacerlas él mismo.
- Una sección donde el usuario pueda reservar una mesa en la cafetería, por medio de un formulario. (el cuál por el momento, sólo funciona de forma visual)
- Y por último, un footer dónde mostremos información de la página web, como redes sociales, logo y autor de ésta.

## Tecnologías y técnicas utilizadas.

Durante esta unidad, seguimos prácticando y aprendiendo técnicas más avanzadas sobre HTML y CSS que podemos ver aplicadas en este proyecto. Algunas de estas fueron:

- **Profundización en estilos**: Márgenes, Fuentes, Flexbox, Posicionamiento, Pseudoclases, Pseudoelementos, Desbordamiento y más.
- **Profundización en la metodología BEM** para organizar el código, clases, elementos, modificadores, mezclas y en este sprint, también ya lo empezamos a incluir en la organización de nuestros directorios y archivos.
- **Separar los estilos de las secciones en archivos CSS diferentes** y vincularlos al archivo index.html, por medio de un solo archivo CSS.
- **Importacion de fuentes externas** utilizando Google Fonts.
- **Uso de la etiqueta <iframe>**: Para importar contenido de Youtube a una de las secciones de la página.
- **Creación de Formularios**: Así como las diferentes entradas de información que existen, botones, placeholders, etiquetas y algunas formas de darles diferentes estilos.

## Estructura y funcionalidad del proyecto.

En esta parte, detallaré cada una de las secciones del sitio, así como lo que apliqué y aprendí en cada una de ellas. A continuación más detalle de cada una.

### Sección Header

![Header](https://github.com/heyzyanlml/web_project_coffeeshop/assets/166194594/df451779-d291-4439-a77a-70bb3191304f)

1.  **Logo de la Empresa:** siendo uno de los elementos dentro del menú de navegación, debía mostrarse en la esquina superior izquierda, por lo que se utilizó `flex` para separar este elemento de los enlaces de navegación, y se agregó `position: relative`para poder posicionarlo en las coordenadas que nos marcaba el brief.

2.  **Menú de Navegación:** Cada elemento del menú está vinculado a su sección correspondiente por medio de la etiqueta `<a>` y su propiedad `href=#` y el id correspondiente. También se agregó un efecto con `:hover` para cambiar de color el enlace cuando el cursor estuviera pasara por encima de él.

3.  **Posicionamiento de títulos y descripciones e imágenes:** En esta parte, nos pusieron una dificultad que era que el título que debía estar en una sola etiqueta debia de tener diferente tipografía, lo cuál logramos con la etiqueta `<span>`. Así como también, seguir prácticando `flex-box` y `position.

4.  **Pie de página de Header:** Por medio de `flex-box` y modificadores de clases se logró alinear el contenido como lo pedía el brief, de tener horarios y ubicación dentro de la misma etiqueta y con alineación diferente.

### Sección Recipes

![Recipes](https://github.com/heyzyanlml/web_project_coffeeshop/assets/166194594/5026c930-b386-42ee-80e4-e1e3ff0a356c)

1. **Profundización en estilos de la página**, como agregar imágenes de background y diferentes estilos en torno a ello.

2. **Aprender a usar iframe:** Aprendimosy aplicarmos el agregar contenido embebido en un sitio, así cómo, el cómo darle estilos a esta etiqueta. Esta parte fue especialmente díficil para mí, ya que a la hora de hacer el `iframe` responsivo, mi contenido embebido se cortaba.

### Sección Reservation

![Reservation](https://github.com/heyzyanlml/web_project_coffeeshop/assets/166194594/9396c8c0-c91e-4caf-bd83-946304a132e1)

1. **Aprender a crear formularios:** Aprendimos de la etiqueta `<form>`, y los campos de entradas de información, lo cuál aplicamos en esta parte. Declaramos estos campos como requeridos, y aplicamos estilos y labels a cada uno de ellos.

2. **Creación y Estilos de un Botón**: Aprendimos los diferentes tipos de botones y usamos ese conocimiento para crear un botón de submit para nuestro formulario, así como también aplicarle un efecto `:hover` para cuando le pasaran el cursor por encima su opacidad cambie.

3. **Elaboración de casilla de verificación.** Se utilizó un `<input>` de tipo `type: checkbox`, además de aprender como encapsular el `<input>` dentro `<label>` nos puede ayudar a centrar la casilla de verificación con el texto de ésta.

4. **Darle estilos a los placeholders:** Aprendí a cómo darle estilos a los placeholders para que quedaran como en el brief, el cómo algunos navegadores no detectan los estilos de placeholders por si solos y necesitamos agregar ciertos prefijos para lograr que se apliquen en todos ellos.

### Sección Footer

![Footer](https://github.com/heyzyanlml/web_project_coffeeshop/assets/166194594/577298bf-9194-42cd-9001-5536cddb3f13)

1. **Posicionamiento del Logo:** Ocurre algo parecido que en el logo de la sección `header`, que debe estar en el mismo bloque que el contenido de las redes sociales, teniendo en cuenta el uso de `z-index` para estar por delante de la figura del círculo azul.

2. **Creación y Posicionamiento de una figura:** Es la primera vez que creé una figura a partir de un `<div>`, esto por medio de `border-radius: 50%;`. Además de posicionarlo cómo se pedía el cuál era importante, ya que afectaba a los demás elementos. También, cuidando que el desbordamiento de la figura se escondiera y ésta quedara detrás de el logo.

3. **Creación de la lista de redes sociales:** Seguí prácticando el uso de listas no ordenadas (`<ul>`) y elementos `<li>`. Así como el uso de `Flexbox` para lograr el acomodo que se pedía. En los links de las redes sociales también agregamos un efecto `:hover` al pasar el cursor por encima.

4. **Creación de un elemento copyright:** Para agregar el nombre del autor.
