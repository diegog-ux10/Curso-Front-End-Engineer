> MODULO 01 - VISION GENERAL
> UNIDAD 02 - VISION GENERAL DE LA INTERNET

# ¿Cómo funcionan los navegadores?

Hasta ahora hemos visto cómo se maneja una sola solicitud y respuesta entre un cliente y un servidor. Pero la mayoría de las veces, nuestros dispositivos no hacen una sola solicitud. Cada vez que cargamos una página web, nuestro dispositivo envía una solicitud por cada archivo que compone esa página. Entonces, incluso cuando solo estamos cargando una página web, esa página puede realizar múltiples solicitudes para recuperar diferentes piezas de contenido, como imágenes.

Entonces, ¿cómo funciona este proceso cuando hacemos varias solicitudes simultáneamente?

Todos los siguientes pasos suceden en una fracción de segundo:

1. Cuando un usuario ingresa una URL y presiona enter, el servidor procesa la solicitud y envía el archivo HTML al cliente. Los archivos HTML contienen el contenido de un sitio web y también contienen enlaces para cualquier activo o código adicional que se necesite para mostrar el sitio correctamente.

2. El navegador comenzará a buscar elementos en el archivo HTML y comenzará a realizar solicitudes HTTP adicionales para cualquier otro recurso externo utilizado por el archivo HTML. Esto a menudo incluye:

    - Una o más hojas de estilo CSS. CSS significa hojas de estilo en cascada; CSS crea el estilo y el diseño de una página web. El navegador solicitará la hoja de estilo CSS y, cuando el servidor la devuelva, el navegador analiza el CSS y comienza a aplicar los estilos visuales al contenido del sitio.

    - El ciclo de solicitud y respuesta también envía activos del sitio web, como imágenes y videos, desde el servidor al navegador. Si estos archivos son grandes, incluso puede haber un retraso notable antes de que el navegador los procese.
    
    - Uno o más archivos JavaScript. JavaScript hace que la página web sea interactiva. Este lenguaje de programación funciona como el “comportamiento” de la página web. Una página web que no usa JavaScript se conoce como una página web estática.

En la mayoría de los navegadores modernos, estas solicitudes adicionales se realizan en paralelo. Esto significa que estas solicitudes se inician al mismo tiempo y el navegador no espera a recibir un recurso antes de solicitar el siguiente recurso.

Por lo general, todos los recursos se muestran lo antes posible. El HTML se mostrará incluso si el navegador no ha recibido algunos de los otros recursos.

¡Voila! El usuario ahora puede interactuar con el sitio web que solicitó ver. Todo este proceso generalmente ocurre en aproximadamente un segundo o menos, según la velocidad de la conexión del usuario, el tamaño del sitio web e incluso la distancia física entre el navegador y el servidor.

###### Ejercicios

[La animación]() muestra los diferentes idiomas que trabajan juntos para mostrar una página web. Cuando esté listo, pase al siguiente ejercicio.