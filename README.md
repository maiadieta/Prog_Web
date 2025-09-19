PROGRAMACIÓN WEB

El sitio está compuesto por tres páginas principales (index.html, productos.html y contacto.html) y una hoja de estilos externa (estilos.css).
La estructura y los estilos aplicados responden a los principios básicos de HTML5 y CSS3, siguiendo buenas prácticas de organización, semántica y presentación.

1. Estructura en HTML
Se utilizó HTML5 para organizar el contenido de manera clara y semántica:

- Cada documento comienza con la declaración <!DOCTYPE html> y la etiqueta <html lang="es">, cumpliendo la regla de accesibilidad e indexación en buscadores .
- El contenido se organiza en encabezados jerárquicos (<h1>, <h2>, etc.) para dar orden lógico a la información. Ejemplo: en index.html, el <h1> destaca el título principal de la página.
- Se emplean párrafos (<p>) para la descripción de la empresa y los productos, garantizando que el texto sea legible.
- Se incluyen enlaces de navegación (<a>) entre páginas, lo que mejora la usabilidad. Por ejemplo:
        </nav/>
            <a href="index.html">Inicio</a>
            <a href="productos.html">Productos</a>
            <a href="contacto.html">Contacto</a>
        </nav/>
- En la página productos.html se aplicaron listas y tablas, siguiendo lo visto en los apuntes de HTML , para organizar datos de forma clara y accesible.
- En contacto.html, se usó un formulario (<form>) para permitir la interacción con el usuario (captura de nombre, correo y mensaje).
- Esta estructura respeta el concepto de separar contenido y estilo, dejando al HTML solo la función de marcar información.

2. Estilos con CSS

Se utilizó una hoja de estilo externa (estilos.css), lo cual sigue la buena práctica de mantener separado el contenido del diseño .
Los principales aspectos de diseño aplicados fueron:
- Colores y fondos: Se definieron colores de fondo en el <body> y colores específicos en los encabezados y enlaces, lo que mejora la identidad visual del sitio. Ejemplo:
          body {
          background-color: #f5f5f5;
          color: #333;
          }
- Tipografía: Se utilizó la propiedad font-family para mejorar la legibilidad de los textos.
           h1 {
           font-family: Arial, sans-serif;
           text-align: center;
           }

- Modelo de caja: Se aplicaron márgenes y paddings para dar espacio entre secciones, mejorando la estética y organización .
- Estilos de navegación: Los enlaces del menú cambian de color al pasar el mouse gracias a la pseudo-clase :hover, lo que aporta dinamismo:
       nav a:hover {
       color: red;
       }
- Diseño flexible: Se usó display: flex en la barra de navegación para distribuir los elementos de manera uniforme, tal como recomienda el apunte de CSS en la sección de Flexbox .

3. Accesibilidad y buenas prácticas

- Se incluyó el atributo alt en las imágenes, cumpliendo con las recomendaciones de accesibilidad .
- Los formularios en contacto.html utilizan etiquetas <label> asociadas a los campos, lo que facilita el uso con lectores de pantalla.
- El uso de una hoja de estilo externa facilita el mantenimiento y la escalabilidad del sitio
- Se evitó el uso de estilos inline, cumpliendo con la separación entre estructura (HTML) y presentación (CSS).

El diseño del sitio responde a los lineamientos básicos de desarrollo web:
- HTML se utilizó para estructurar el contenido de forma semántica, accesible y ordenada.
- CSS se aplicó para definir la presentación visual, logrando un diseño atractivo y fácil de navegar.


Se aplicaron ejemplos de listas, tablas, formularios, encabezados, enlaces y estilos vistos en los apuntes, demostrando la comprensión de la teoría en un proyecto práctico.
. 
