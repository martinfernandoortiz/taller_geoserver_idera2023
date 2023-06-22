<h2>Instalación en Windows vía docker</h2>

La documentación oficial está [aquí](https://docs.geoserver.org/latest/en/user/installation/docker.html)

En una terminal (cmd) escribir: ```docker pull docker.osgeo.org/geoserver:2.24.x ```

![alt_text](images/docker1.png "image_tooltip")


Para correr el contenedor: 

```docker run -it -p8080:8080 docker.osgeo.org/geoserver:2.24.x ```

Si queremos utilizar el contenedor con una carpeta para poner data (shapes, etc) debemos correr

```docker run -v C:\Users\martin\Documents\docker:/opt/geoserver_data -it -p8080:8080 docker.osgeo.org/geoserver:2.24.x```

en donde C:\Users\martin\Documents\docker es la carpeta donde irán los shapes o capas a subir

---

<h3> Comandos útiles: </h3>

* Estructura básica de comandos ```docker <comando> --help```
* Chequear versión```docker version``` 
* Chequear versión con menú de ayuda```docker version --help```
* Ver que imágenes tenemos ```docker images```
* Crear imagen```docker image build --help```
* Crear imagen con un tag y ubicación ```docker image build -t <tag/nombre que va a tener la imagen> <ubicacion Dockerfile>```
* Para chequear los contenedores corriendo ```docker container ps --help ```
* Para chequear todos los contenedores (corriendo o no) ```docker container ps -a```
* Si el docker ya fue creado ```docker container start --help```
```docker container start <ID del contenedor>```
* Para el contenedor ```docker container stop <id del contenedor>```
* Matar el contenedor ```docker container kill <id del contenedor>```
* Borrar contenedores parados  ```docker system prune```
* Borrar contenedores ```docker container rmi <id/tag de la imagen>```
