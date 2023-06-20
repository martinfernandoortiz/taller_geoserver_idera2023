<h2>Instalación en GNU-Linux</h2>


<h3>Vía Docker</h3>


Si usas alguna distribución GNU-Linux te sugerimos que optes por la instalación vía docker; de esta forma no vas a tener problemas de dependencias ni nada de eso. Solo necesitas tener instalado docker y docker compose y permisos de administrador.

La documentación oficial está [aquí](https://docs.geoserver.org/latest/en/user/installation/docker.html)

En una terminal (ctrl+ alt + t) escribir: ```docker pull docker.osgeo.org/geoserver:2.24.x ```

Img: Docker1

Para correr el contenedor: 

```docker run -it -p8080:8080 docker.osgeo.org/geoserver:2.24.x ```

Si queremos utilizar el contenedor con una carpeta para poner data (shapes, etc) debemos correr

```sudo docker run --mount type=bind,src=/home/martin/Documents/docker,target=/opt/geoserver_data -it -p8080:8080 docker.osgeo.org/geoserver:2.24.x ```

en donde /home/martin/Documents/docker es la carpeta donde irán los shapes

Si el docker ya fue creado

```sudo docker container start```

La interfaz de geoserver se ejecuta a través de un navegador. Escribir: 


```
http://localhost:8080/geoserver
```


El usuario y contraseña predeterminado son: u: admin p: geoserver


![alt_text](images/image1.png "image_tooltip")
