
Banca|
----------------- |----------------
 Responsabilidades:  |  
*Repartir mano inicial |  
*Repartir carta adicional | 
*Mostrar toda o parte de una mano| 
*Calcular el valor de una mano|
*Calcular el numero de cartas de una mano|
*Determinar el ganador |
*Empezar una nueva mano|
Colaboraciones:|
*Baraja|
*Jugador|
*Mano|
*Carta|

***
***
###Segunda Clase
Class: Jugador |
----------------- |----------------
 Responsabilidades:  |  
*Pedir que se le reparta una carta a su mano |
*Mostrar su mano|
*Calcular el valor de su mano|
*Determinar el numero de cartas en su mano|
Colaboraciones:|
*Banca|
*Mano|


***
***

###Tercera Clase
Class: Baraja|
----------------- |----------------
 Responsabilidades:  |  
*Poder repartir la siguiente carta|
*Reportar cuantas cartas quedan en la baraja|
Colaboraciones:|
*Banca|
*Carta|

***
***
###Cuarta Clase
Class: Carta|
----------------- |----------------
 Responsabilidades:  |  
*Saber su valor y debe ser capaz de reportarlo|
*Todas las cartas deben de ser parte de una baraja|
Colaboraciones:|
*Baraja|
*Mano|

***
***
###Quinta Clase
Class: Mano|
----------------- |----------------
 Responsabilidades:  |  
*Saber el numero de cartas que lo forman|
*Saber la suma total de las cartas|
Colaboraciones:|
*Banca|
*Jugador|
*Carta|


***
***

#**BANCA**
----------------- |----------------
##*RESPONSABILIDADES*|
*repartir mano inicial	|
*repartir carta adicional	|
*mostrar todo o parte de una mano	|
*calcular valor de una mano|
*calcular número de cartas de una mano|
*determinar al ganador	|
*comenzar un nuevo juego|
*administrar apuestas	|
----------------- |----------------
##*COLABORADORES*|
*jugador|
*baraja|
*mano|
*carta|
***
#**JUGADOR**
----------------- |----------------
##*RESPONSABILIDADES*|
*pedir cartas	|
*mostrar mano |	
*calcular valor de una mano|	
*calcular número de cartas de una mano	|
*responder a la banca	|
*apostar	|
----------------- |----------------
##*COLABORADORES*|
*banca|
*mano|
*carta|
***
#**CARTA**
----------------- |----------------
#*RESPONSABILIDADES*|
*saber su valor	|
*si es figura dar valor de 10|
*si es as puede responder a uno u once|
----------------- |----------------
*COLABORADORES*|
*mano|
*baraja|
***
##**BARAJA**|
----------------- |----------------
#*RESPONSABILIDADES*|
*repartir siguiente carta	|
*calcular cartas restantes 	|
----------------- |----------------
*COLABORADORES*|
*banca
*carta
----------------- |----------------
##**MANO**|
----------------- |----------------
#*RESPONSABILIDADES*|
*si es mayor a 21 pierde	|
*si es igual a 21 puede ganar|
*si es una figura mas un as es un blackjack y no pierde	|
*si se acerca a 21 mas que la banca gana	|
----------------- |----------------
*COLABORADORES*|
*jugador|
*banca|
----------------- |----------------
