**Practica 1: Instalación de un**

**servidor LEMP**
# **Instalación del servidor de base de datos**
Instalamos la base de datos.

![](img1.png)

Ejecutamos la configuración segura inicial.

![](img2.png)

Creamos una base de datos y un usuario nuevo.

![](img3.png)

![](img4.png)
# **Instalación de Nginx i PHP**
Instalamos los paquetes necesarios.

![](img5.png)
# **Verificación del funcionamiento de nginx**
Tenemos que modificar el archivo de configuración.

![](img6.png)

Accedemos desde el navegador, a la pagina web de inicio del servidor

![](img7.png)
# **Verificación del funcionamiento de PHP**
Creamos un fichero dentro del directorio /var/www/html.

![](img8.png)

Comprobamos que los ficheros servidos por Apache son propiedad de www-data:www-data. Accedemos al navegador y vemos la configuración php instalado.

![](img9.png)
# **Acceso con nombre (resolución de nombres)**
Editamos el archivo /etc/hosts y añadimos la dirección IP y el nombre.

![](img10.png)

Ahora visitamos otra vez la página web.
![](img11.png)
