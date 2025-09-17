*** Guía Rápida de Clases de Bootstrap Usadas ***

    --- ESTRUCTURA Y LAYOUT ---
    .container: Centra el contenido y le da un ancho máximo para que no ocupe toda la pantalla en monitores grandes.
    .row: Crea una fila horizontal para organizar las columnas dentro de ella.
    .col-md-4: Crea una columna. En pantallas medianas ('md') o más grandes, ocupa 4 de 12 espacios. En pantallas más pequeñas, se apila verticalmente.
    .col-md-6: Similar al anterior, pero ocupa 6 de 12 espacios (la mitad del ancho).

    --- ESPACIADO (Márgenes y Paddings) ---
    La fórmula es: {propiedad}{lados}-{tamaño}
    - Propiedad: 'm' (margin) o 'p' (padding).
    - Lados: 't' (top), 'b' (bottom), 's' (start/izquierda), 'e' (end/derecha), 'x' (eje X), 'y' (eje Y). Si no pones lado, se aplica a los 4.
    - Tamaño: Un número del 0 al 5.
    Ejemplos:
    .my-4: Añade margen en el eje Y (arriba y abajo) de tamaño 4.
    .mt-5: Añade margen superior (margin-top) de tamaño 5.
    .p-4: Añade padding (relleno interior) en los 4 lados de tamaño 4.
    .py-3: Añade padding en el eje Y (arriba y abajo) de tamaño 3.
    .mb-0: Elimina el margen inferior (margin-bottom: 0).
    .g-4: Define un "gap" (espacio) de tamaño 4 entre las columnas de una fila.

    --- COLORES Y FONDO ---
    .bg-primary: Aplica un color de fondo principal (azul por defecto).
    .bg-light: Aplica un color de fondo gris claro.
    .text-white: Cambia el color del texto a blanco.

    --- TEXTO Y TIPOGRAFÍA ---
    .text-center: Centra el texto.
    .text-md-start / .text-md-end: Alinea el texto a la izquierda/derecha en pantallas medianas ('md') o más grandes.
    .display-4: Estilo para un título muy grande y destacado.
    .lead: Hace que un párrafo destaque, haciéndolo un poco más grande.

    --- COMPONENTES ---
    .card: Contenedor principal para una "tarjeta". Agrupa contenido visualmente con bordes y fondo.
    .card-body, .card-title, .card-text: Partes de una tarjeta para el cuerpo, título y texto.
    .rounded: Aplica bordes redondeados a un elemento.
    .h-100: Hace que el elemento ocupe el 100% de la altura de su contenedor padre (útil para que las tarjetas de una fila tengan la misma altura).
