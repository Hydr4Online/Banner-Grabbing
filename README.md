# Banner-Grabbing
Un sctipt en python para detectar la version del servicio ftp por el puerto 21

<h1> ¿Que es el banner grabbing? </h1>

el banner grabbin para una mejor comprension implica detectar y recopilar información sobre las versiones y servicios 
en ejecución que corren por detras de un sistema remoto sobre un puerto en especifico donde el script "BannerG.py" cumple esa funcionalidad un
ejemplo de una herramienta muy famosa que hace este tipo de escanneo con banner grabbing es nmap.

El script establece coneccion con el puerto 21 --> envia una solicitud al servidor --> Se recibe la solicitud con la version y servicio del puerto 

<h2> ¿Como usar el script? </h2>

para el uso de "BannerG.py" se debe usar los dos argumentos declarados los cuales son -t o --target que cumplen la misma
funcion sobre el puerto el cual es el 21 pero puede ser cambiado a intereses propios aqui un ejemplo sobre como ejecutar
el script 

- python3 Banner.py --target 10.10.10.10
- python3 Banner.py -t 10.10.10.10
