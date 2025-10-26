**Pràctica 2: Servir múltiples dominis**
# **Virtual hosting amb nginx**
Copiamos dos veces el fichero de por defecto.

![](img01.png)

Antes de configurar los ficheros, crearemos los enlaces directos.

![](img02.png)

Ahora descargaremos las dos páginas que indicaremos que enfoquen allí.

![](img03.png)

Movemos los ficheros en la carpeta /var/www/.

![](img04.png)

A continuación modificaremos el fichero de configuración de la página1.

![](img05.jpeg)

Ahora añadiremos en el fichero /etc/hosts del equipo principal.

![](img06.png)

Y ahora comprobamos en el navegador.

![](img07.png)

Ahora modificamos el fichero de la página2.

![](img08.jpeg)

Ahora modificamos el fichero /etc/hosts.

![](img09.png)

Y comprobamos en el navegador.

![](img10.jpeg)
