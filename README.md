## Sistema de recomendación Googlemaps API

![](https://s.aolcdn.com/hss/storage/midas/4f372c03fde02b460bd43f8b9a2d1ebb/206422544/google+maps.jpeg)

En este proyecto construiremos un sistema de recomendación del tipo *Content based* , alimentado con los datos de google maps a traves de su API. 

El proyecto lo dividimos en dos etapas.

###  Obtención y  preparación de los datos:
En esta nos encargaremos de obtener los datos atraves de las *request* a la API y haremos un *preprocesamiento* de los datos de manera que esten listos para que sean consumidos por nuestro sistema de recomendación.
###  Construcción sistema de recomendación: 
En este nos encargaremos de construir nuestro *Content base recommendation System* , que use las puntuaciones de un usuario asignada a sitios visitados previamente, para que con base en ellas arroje una lista de sugerencias de sitios con un contenido similar , los cuales podrian ser de interés dentro de un radio establecido de acuerdo a la ubicación del usuario.
