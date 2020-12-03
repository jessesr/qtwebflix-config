# qtwebflix-config
Ficheros de Configuracion para ser usados por qtWebFlix para poder ver series y peliculas desde Netflix, HBO, AmazonPrime y Disney+ sobre linux manjaro

En esta ruta se encuentran los instaladores (via git) de QTWebFlix
https://github.com/gort818/qtwebflix

La secuencia de ejecucion para cada una de los configuraciones es la siguiente

0. appXXXX --> lanzador (acceso directo)

1. |-> XXXX-qtwf.run -> script que copia los ficheros de configuracion respectivos: providers-XXXX.conf y save_state-XXXX.conf y ejecuta el programa cargando la configuracion previamente copiada. En mi caso tengo una ruta fija y modicarla segun corresponda

2. |-> XXXX.jpg o ico --> imagen del icono a 

En mi caso funciona muy bien. Disney, HBO, Netflix y AmazonPrime

He tenido problemas con Netflix, se soluciona añadiendo --useragent "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/87.0.4280.66 Safari/537.36" al script netflix-qtwf.run en la linea que se invoca a /usr/bin/qtwebflix
