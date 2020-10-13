# entornoLAMPVagrant

#### Archivos adjuntos.

   -Vagrantfile -> Contiene la configuración de la máquina que vamos a levantar.
 
   -.provision -> Contiene todos los archivos de configuración de herramientas y servicios que vamos a provisionar en nuestra máquina.

#### Procedimiento.

Descargar Vagrant desde su página oficial -> https://www.vagrantup.com/downloads

Una vez descargado e instalado, copiamos los archivos de este repositorio en el directorio donde vamos a levantar nuestra máquina.

Abrimos un terminal en el mismo directorio y ejecutar el siguiente comando para levantar nuestra máquina:

```
vagrant up
```

Con este comando lo que hará es descargar la imagen indicada en el archivo de configuración *Vagrantfile* , configurar la máquina y provisionarla de todo lo necesario para tener un entorno LAMP.

Se puede cambiar también otros parámetros en el archivo de configuración *Vagrantfile* como la memoria RAM y núcleos a utilizar de nuestra máquina anfitriona.

***TENER EN CUENTA!! En el archivo de configuración de Vagrant viene con la redirección de puertos al 2345.***

Para acceder al servidor web desde nuestro navegador y ver que ya está funcionando solo tenemos que poner:

```
http://localhost:2345
```
