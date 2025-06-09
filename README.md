Claro, aquí tienes el contenido completo del README.md en un solo bloque listo para copiar y pegar:


---

🧠 Código del Proyecto Web Personal – Módulo 2

Este proyecto está desarrollado usando HTML semántico y CSS moderno. Es un sitio web personal donde presento mi información, trabajos previos y un formulario de contacto. A continuación se describe cómo está estructurado y cómo funciona el código.


---

📁 Estructura del proyecto

proyecto/
│
├── index.html              ← Página de inicio
├── presentation.html       ← Presentación personal
├── portfolio.html          ← Portafolio con tres proyectos
├── contact.html            ← Formulario de contacto
├── style.css               ← Estilos generales y responsivos
└── imagenes/               ← Imágenes usadas en el sitio
    ├── yo.jpeg
    ├── imghoja.png
    ├── 7 paginas.png
    └── S1.png


---

📄 Descripción de archivos HTML

index.html

Página principal del sitio.

Usa etiquetas semánticas: <header>, <nav>, <main>, <footer>.

Contiene enlaces internos a las secciones: presentación, portafolio y contacto.

Explica brevemente qué se encuentra en cada página.


presentation.html

Presentación personal con foto y descripción de habilidades, estudios y gustos.

Incluye una imagen animada mediante @keyframes floating.

Usa estructura semántica y clases para aplicar estilos.


portfolio.html

Muestra tres proyectos personales usando un layout Grid responsive.

Cada proyecto está contenido en un .box, con imagen, título, descripción y botón de enlace externo.

Efectos hover en tarjetas y botones con transiciones CSS.


contact.html

Formulario completo: nombre, email, asunto y mensaje.

Validación HTML5 (required, type=email).

Estilizado con campos organizados dentro de un <fieldset>.



---

🎨 Estilos en style.css

1. 🎯 Variables CSS

Se usan variables para mantener consistencia de colores:

:root {
  --orange: #f58b01;
  --black: #000000;
  --white: #ffffff;
  --grey: grey;
}

2. 📐 Layouts con Flexbox y Grid

.nav_bar usa display: grid para menú responsive.

.container__projects usa grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)) para que se adapte automáticamente.


3. ✨ Transiciones y animaciones

Botones y enlaces tienen transiciones suaves con transition y :hover.

Animación flotante en la imagen de presentación:


@keyframes floating {
  from { transform: translateY(0); }
  to { transform: translateY(10px); }
}

4. 🧭 Responsividad

Grid adaptable para proyectos.

Unidades relativas (em, %, vh, vw) en tamaños y espaciado.

minmax y auto-fit aseguran que los elementos se acomoden a cualquier resolución.

El diseño funciona correctamente en:

Móviles (≤480px)

Tabletas (≥768px)

Escritorio (≥1024px)




---

🖱️ Interactividad

Transiciones en botones y li:hover para navegación.

Botones con efectos hover que hacen rotación y sombreado.

Las tarjetas del portafolio cambian visualmente al pasar el cursor.



---

📌 Buenas prácticas aplicadas

Separación de estructura (HTML) y estilos (CSS).

Uso de etiquetas semánticas.

Código limpio, indentado y organizado por secciones.

Uso de variables CSS para colores.

alt descriptivos en imágenes.

Responsive sin librerías externas, usando solo CSS puro.



---

🧑‍💻 Autor

Cristian Chaverra Colorado
Proyecto final para el Módulo 2 – Desarrollo Web
Formación en Riwi
GitHub


---

🗂️ Licencia

Este código está disponible para fines educativos. Puedes reutilizarlo dando crédito al autor.


---

¿Deseas también una versión en PDF o en inglés?

