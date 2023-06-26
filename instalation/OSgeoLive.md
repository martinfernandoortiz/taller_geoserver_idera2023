<h2>Que es OSGeoLive?</h2>  
OSGeoLive es un DVD de arranque autónomo, unidad USB o máquina Virtual basada en Lubuntu, que permite probar una gran variedad de software geoespacial de código abierto sin necesidad de instalar algo particular. Se compone enteramente de software libre, lo que le permite ser libremente distribuido, duplicado y compartido.
Para conocer más acerca de éste proyecto ingresa aquí: https://live.osgeo.org/es/

Dentro de todos los programas que componen a OSGeoLive se encuentra Geoserver. Podemos utilizar esta distribución tanto desde una maquina virtual como tambien desde un usb de arranque. Para cualquiera de las dos opciones vamos a descargar el archivo desde https://live.osgeo.org/es/download.html.

Podes consultar la documentación oficial
* [Cómo empezar con OSGeoLive](https://live.osgeo.org/es/quickstart/osgeolive_quickstart.html)
* [Instalar OSGeoLive en el Disco Duro](https://live.osgeo.org/es/quickstart/osgeolive_install_quickstart.html)
* [Ejecución en una máquina virtual](https://live.osgeo.org/es/quickstart/virtualization_quickstart.html)
* [Crear una unidad flash USB de arranque OSGeoLive](https://live.osgeo.org/es/quickstart/usb_quickstart.html)

---

<h3>Desde una máquina virtual</h3>
Para este ejemplo, necesitamos instalar una máquina virtual descarga Oracle Virtual Box desde 

[acá](https://www.oracle.com/virtualization/technologies/vm/downloads/virtualbox-downloads.html)
y descargar el archivo de OsGeoLive en formato vm (
[consulta acá](https://live.osgeo.org/es/quickstart/virtualization_quickstart.html) )

[![Instalación y Configuración](https://img.youtube.com/vi/1LFuuLXX0Jk/0.jpg)](https://www.youtube.com/watch?v=1LFuuLXX0Jk)

---

<h3>Desde un USB de arranque</h3>
Necesitas cualquier programa para generar un usb de arranca (booteable). 

[Etcher Balena](https://etcher.balena.io/)  es un programa multiplataforma (tanto para Windows cómo para GNU Linux )

1. Seleccionas el archivo iso descargado de https://live.osgeo.org/es/
2. Seleccionas el Pendrive
3. Tocas flash
4. Reinicias y tenes que seleccionar desde el BIOS que bootee primero el USB

Si en algún momento necesitas volver a restaurar tu usb, seguí éstos pasos : https://www.pendrivelinux.com/restoring-your-usb-key-partition/#DiskPart_Has_Encountered_an_Error
---

<h3>Cómo arrancar Geoserver?</h3>

[![Instalación y Configuración](https://img.youtube.com/vi/WKR0BBTQrf8/0.jpg)](https://www.youtube.com/watch?v=WKR0BBTQrf8)
