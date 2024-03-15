TRABAJO DE CACAO 

4 productos diferentes de cacao 
bombones, slider, ejecucion de JS

JS script explicación:

Obtener los elementos del DOM: Se seleccionan diferentes elementos HTML dentro del documento utilizando métodos como getElementById, querySelector, y querySelectorAll. Estos elementos son los botones de "Siguiente" y "Anterior", la lista de imágenes del carrusel, los elementos de miniaturas, y un elemento que muestra el tiempo de cambio de imágenes.

Configuración inicial: Se añade el primer elemento de las miniaturas al final de la lista de miniaturas. También se establecen algunas variables para controlar los intervalos de tiempo de cambio de imágenes.

Función para mostrar la siguiente o anterior imagen: La función showSlider recibe un parámetro type, que indica si se debe mostrar la siguiente imagen ('next') o la anterior ('prev'). Dentro de esta función, se reorganizan los elementos de la lista del carrusel y de las miniaturas según el tipo de acción (siguiente o anterior). Además, se añaden clases al elemento principal del carrusel para aplicar transiciones de animación. Se utiliza setTimeout para eliminar estas clases después de un cierto tiempo y así detener la animación. También se reinicia el temporizador para el cambio automático de imágenes.

Eventos click: Se asignan funciones a los botones de "Siguiente" y "Anterior" para llamar a la función showSlider con el tipo correspondiente.

Temporizador de cambio automático: Se utiliza setTimeout para ejecutar la acción de hacer clic en el botón "Siguiente" automáticamente después de un cierto tiempo (timeAutoNext). Este temporizador se reinicia cada vez que se hace clic en uno de los botones de navegación manual (next o prev).