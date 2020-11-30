<img src="../imagenes/MI-LICENCIA88x31.png" style="float: left; margin-right: 10px;" />

# 5.- Despliegue del contenedor
## Despliegue de un contenedor httpd con una paǵina personalizada y mapeaa por el puerto 8082.

**Home > Containers > + Add container**

![añadircontenedor](../imagenes/add.png)

**Creamos el contenedor**

Con esta configuración estamos creando un contenedor denominado *mi-web* partiendo de la imagen *httpd* de DockerHub, exponiendo este contenedor a través del puerto *8082*. Además estamos enlazado un directorio entre el host y el contenedor desde */root/ejemploWeb* (Donde estará mi web) a */usr/local/apache2/htdocs/* que es donde el servidor apache buscará la web a mostrar

![añadircontenedor2](../imagenes/runMaquina.png)

*Contenido del directorio enlzado*

![pasos previos](../imagenes/pasosPrevios.png)
## Contenedor lanzado

![vista portainer](../imagenes/lanzado.png)
![vista navegador](../imagenes/pruebaWeb.png)
________________________________________
*[Volver al indice...](../README.md)*