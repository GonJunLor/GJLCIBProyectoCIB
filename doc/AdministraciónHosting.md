# ADMINISTRACIÓN HOSTING

- [ADMINISTRACIÓN HOSTING](#administración-hosting)
  - [**Conexión por sftp y ssh**](#conexión-por-sftp-y-ssh)
  - [**Crear un subdominio**](#crear-un-subdominio)

## <h2>**Conexión por sftp y ssh**</h2>

**<h3>SFTP</h3>**
Lo primero es tener los datos de conexión, por si no los tenemos vamos a *sitios web y dominios*, damos a *ftp* y en nuestro nombre  se abre una ventana donde podemos configurar el nombre de usuario y contraseña, además de ver que el acceso SSH es */bin/bash* y ver también nuestra ip.

Para conectarnos lo hacemos con [mobaXterm](ClienteDesarrollo.md#3-mobaxterm) igual que cuando nos conectamos a nuestro servidor solo que con los datos que hemos configurado.

**<h3>SSH</h3>**
Tenemos dos opciones, la primera es directamente desde plesk en *sitios web y dominios*, damos a *SSH Terminal*, se nos abre la consola de comando donde poder hacer lo que tengamos permisos.

La segunda opción es con un cliente como [mobaXterm](ClienteDesarrollo.md#3-mobaxterm) igual que cuando nos conectamos a nuestro servidor pero con los mismos datos de sftp.


## <h2>**Crear un subdominio**</h2>
Desde plesk en *sitios web y dominios* damos a *añadir subdominio*.

Se abre una ventana donde ponemos el nombre del subdominio, normalmente el del proyecto que queremos subir. Elegimos también un directorio para guadar dicho proyecto, en nuestro caso será el mismo que ya tenemos dentro de httpdocs. Muy importante asegurarse de que le nombre de la carpeta sea solo el del proyecto, ya que por defecto plesk pone el dominio entero a esta carpeta, por lo que tenemos que borrarlo antes de darle aceptar.