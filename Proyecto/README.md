# REPOSITORIO DE ACTIVIDAD FINAL - PROYECTO

## OBJETIVO DEL PROYECTO
Lo que se esperaba para este proyecto es que en equipos, con los conocimientos aprendidos, realizar un juego.
Donde en nuestro caso realizamos un laberinto, con base en la libreria de Turtle

## DESARROLLO
En este laberinto se empezo por partes, primero con una lluvias de ideas, primero un tetris,
luego un sudoku, un juego de picarle al boton, pero finalmente optamos por un Laberinto.
De ahí nos pasamos a la elaboracion de este, primeramente, André Castillo elaboro uno, pero
sin Turtle, a lo cual yo, despues lo pase a que se pudiera ver con turtle, aunque el primer
boceto del programa de este no me convencio, así que decidi usar el ya se habia enseñado con
el pacman, y lo modifique y modificamos entre todos las medidas, para que estuviera bien en 
un laberinto de 25 x 25. Despues de todo esto y pasado el codigo base, empezamos con la
reparticion de trabajo, nos juntamos por llamada y nos fuimos pasando nuestros avances por 
whatsapp, aunque principalmente se estuvo en llamada, para poder resolver el mayor problema
que tuvimos, el movimiento del personaje. Ya una vez teniamos el juego jugable, solo fue 
añadirle detalles, como una pantalla de vicotria, unas llave, que pasaba cuando ganabas,
un randomizador de mapas (Que estos los hizo Marco Montoya) y correguir bugs que se tenian.

## FUNCIONAMIENTO
Este funciona con una matriz, bueno aunque realmente es una lista grande, donde el lugar donde se encuentre
cierto numero en la lista es como se dibujara en la pantalla Turtle, por ejemplo: tenemos que 0 es pared, 1
es camino, 2 es personaje, 3 es puerta y 4 llave. Dependiendo como se ponga en la lista es como se dibujara 
en un inicio el mapa (cada numero tiene su propio color). Para llegar a mover el personaje, lo que se hace
es basicamente buscarlo en la lista y para poder despues picarle a una tecla y decirle a la computadora que 
cambio la lista y ahora es de otra manera, y asi con todo, si se mueve el personaje se reescribe la lista y 
se vuelve a dibujar, obviamente se puso, que el 0 no se pudiera pasar, que si agarrabas la llave el lugar donde
esta estaba se pintara como el suelo y por cierto el tonto este movimiento de las teclas esta en un while TRUE
para que no se quede sin movimientos, cuando se llega a la meta o puerta esta despliega una nueva ventana, donde
se te felicita. Ya despues para el mapa al azar simplemente se utilizo un randomizador.

## COMPLICACIONES
Las complicaciones que tuvimos fueron:
*Principalmente el movimiento de este.
*Bug para cuando agarrabas la llave.
*Bug cuando saltaba la pantalla final.
*El tamaño de la pantalla en si.
*Crear el mapa.
Aunque en el que realmente si hubo problemas fue en el movimiento del personaje.
