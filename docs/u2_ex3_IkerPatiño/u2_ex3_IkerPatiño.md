**Pràctica 3: Certificat SSL/TLS**
# **Creación Certificado**
Crearemos el certificado autofirmado.

![](img1.png)

Luego nos dirá que pongamos unos datos.

![](img2.png)
# **Automatizar creación del certificado autofirmado**
Automatizamos creando un script.

![](img3.png)
# **Consultar certificado**
Consultar información del sujeto del certificado.

![](img4.png)

Consultar la fecha de caducidad del certificado.

![](img5.png)
# **Configurar un Block SSL/TSL en Nginx**
**Configurar el Bloc SSL** Configuramos el sitio seguro ssl.

![](img6.png)

**Creamos el sitio seguro** Creamos el siguiente directorio.

![](img7.png)

Creamos el documento de inicio.

![](img8.png)

Aplicamos cambios y reiniciamos el servicio.

![](img9.png)

**Verificamos el correcto funcionamiento** Desde un cliente accedemos por IP.

![](img10.jpeg)

Vemos que nos salta una alerta de advertencia, en *Avanzado* aceptamos el riesgo.

![](img11.png)

Ahora volvemos a entrar con el nombre de la página.

![](img12.jpeg)

Volvemos a realizar el proceso para acceder.

![](img13.png)

**Block de redirección de HTTP a HTTPS.**

En el bloque de por defecto *default* y añadimos las siguientes líneas.

![](img14.png)

Reiniciamos el servicio y entramos en el navegador pero con el enlace con http.

![](img15.png)

Y al buscar, vemos que nos redirigió a https.

![](img16.png)
