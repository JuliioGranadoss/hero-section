## Página con Video de Fondo

### Descripción
Este proyecto es una página web con un video de fondo relacionado con el "Drift". Presenta un mensaje de bienvenida y un botón para activar/desactivar el sonido del video.

### Estructura
- **HTML**: Contiene la estructura básica de la página con un video de fondo y contenido superpuesto.
- **CSS**: Estiliza la página y define el diseño del video y el contenido.
- **JavaScript**: Controla la funcionalidad del botón para activar/desactivar el sonido del video.

## Funcionamiento

### HTML (`index.html`)
La estructura HTML está compuesta por:
- Un contenedor principal (`<div class="video-container">`) que alberga tanto el video de fondo como el contenido superpuesto.
- Un elemento `<video>` que reproduce el video de fondo.
- Un div con la clase `content` que contiene el texto superpuesto.
- Un botón (`<button>`) que permite al usuario activar/desactivar el sonido del video.

### CSS (`estilos.css`)
El archivo CSS define estilos para los elementos HTML en la página:
- Establece el tamaño y la posición del video de fondo y del contenido superpuesto.
- Aplica efectos de estilo, como sombras de texto y efectos de transición en el botón.

### JavaScript (`<script>` en `index.html`)
Se utiliza JavaScript para controlar la funcionalidad del botón de activar/desactivar el sonido del video.
- Cuando el usuario hace clic en el botón, se activa/desactiva el atributo `muted` del elemento de video, lo que controla si el sonido del video está activado o desactivado.
