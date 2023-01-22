# osi-geekshubs-fsd-val-20012023
Reto Consola

Nintendo Switch Oled modelada en CSS

La consola está maquetada de forma muy sencilla en tres contenedores que corresponden a cada uno de los joycons y la pantalla. He combinado el uso de flexbox junto al atributo position para colocar los botones y los joysticks en su lugar correspondiente.

Empecé creando los tres contenedores solo con el color de fondo y a partir de ahí primero hice los elementos del joycon izquierdo y luego los del derecho, dejándome ambos gatillos para el final para colocarlos con z-index. Soy consciente de que quizás habría sido más fácil colocar los botones de la cruceta y los principales dentro de un div para poder moverlos todos a la vez con mayor facilidad dentro del contenedor padre pero para cuando me di cuenta ya los había conseguido alinear bien por separado, así que preferí dejarlo así.

Había utilizado clases para hacer todo y cuando terminé me di cuenta de que salían muchísimas líneas de código, así que estuve agrupando los elementos comunes en clases y los elementos individuales en identificadores para que fuera más legible.