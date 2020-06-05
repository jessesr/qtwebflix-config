# qtwebflix-config
Ficheros de Configuracion para ser usados por qtWebFlix para poder ver series y peliculas desde Netflix, HBO, AmazonPrime y Disney+ sobre linux manjaro

En esta ruta se encuentran los instaladores (via git) de QTWebFlix
https://github.com/gort818/qtwebflix

La secuencia de ejecucion para cada una de los configuraciones es la siguiente

appXXXX --> lanzador (acceso directo)
|-> XXXX-qtwf.run -> script que copia los ficheros de configuracion respectivos: providers-XXXX.conf y save_state-XXXX.conf y ejecuta el programa cargando la configuracion previamente copiada. En mi caso tengo una ruta fija y modicarla segun corresponda
|-> XXXX.jpg o ico --> imagen del icono a 

En mi caso funciona muy bien. Disney, HBO, Netflix y AmazonPrime
