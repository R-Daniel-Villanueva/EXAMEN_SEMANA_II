# EVALUACION SEMANA II
## PATRONES DE DISEÑO

### PROBLEMATICA: 
### Sistemas de Streaming (Spotify, Apple Music, Amazon Music, Youtube, Etc) buscan comprar una cancion, dependiendo si esta ya pagó o aun no. El sistema manejador de las canciones permite su descarga o no dependiendo de ese estado.
### Determina el Patron de diseño que sea el adecuado para implementarse en el programa y ¿Por qué? 




### El patron de diseño elegido es "OBSERVER", esto debido a que permite la implementacion de una clase observable (Clase que determina si existe un pago o no) y los observadores (Sistemas de Streaming).
### Para su implementación se penso en la independencia de los sistemas de Streaming y el echo de que dependen de un estado unico (existencia de pago) para la adquisición de la cancion. A si mismo se determino que es el patron de diseño adecuado porque la clase observable emite una alerta (Metodo de notificacion) a los sistemas de Streaming una vez que se haya efectuado el cambio de estado en la existencia de pago.


