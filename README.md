# spider_Dam
Sala de cine. <br>
POO ejercicio de clase, enunciado de Alejandro Sánchez, ¡gracias!. <br>
Montamos un CINE de una SALA, nuestra SALA se organiza en filas y columnas de BUTACAS (45 butacas organnizadas en 5 filas y 9 columnas). Nuestra aplicación, mediante un MENÚ PRINCIPAL, debe permitirnos las siguientes acciones:

	0. Salir (siempre que se termine una opción se vuelve al menú principal).
	1. Ver sala.
	2. Comprar entrada.
	3. Reservar.
	5. Anular la reserva.
	6. Resumen (contabilidad + estadísticas + número de filas ocupadas por completo).
a) Ver el estado de la sala: gráfico de la sala.

b) Buscar butacas libres, nos mostrará cuales son las que están libres.

c) Comprar una entrada, preguntando al cliente qué butaca quiere (fila y columna) únicamente si la butaca está libre.

d) Reservar butacas para el cliente.

e) Anular una reserva o una compra de una butaca.

f) Concocer la recaudación del cine.

g) Estadísticas de la sala (nº de ocupados, nº de reservas, nº de libres y sus respectivos %).

Se pide, aparte del programa, los test utilizando Gradle, compilar un JAR e implementar emojis y colores

ESPECIFICACIONES
· Cuando se muestre el cine, el escenario será un cuadrado, cada barra será un corchete ([]), cada fila será una letra (A, B, C, D...) y cada columna un número (1, 2, 3, 4, 5...).

· Si la butaca está libre, la pintamos de verde (el fondo) y la rellenaremos con un emoticono.

· Si la butaca está reservada, el fondo será naranja.

· Si está ocupada, utilizaremos el fondo rojo.

· Si seleccionamos una butaca y ésta está libre, solo pasará a estar ocupada cuando la compra se haga efectiva (TODAS LAS ENTRADAS VALDRÁN 6€ Y SOLO SE PODRÁ COMPRAR 1).

· Es obligatorio ir sumando a la recaudación el dinero de la compra o restarlo si esta es anulada.

· La reserva de la butaca debe ser confirmada en algún momento (o anulada).

Clase Sala:
	- Recaudación
	- Butaca[][] butacas (toString() -> colores.
	
Clase Butaca: 
	- Fila (A.....F)
	- Columna (1....9)
	- Estado (Enum (LIBRE, RESERVADA, OCUPADA)
