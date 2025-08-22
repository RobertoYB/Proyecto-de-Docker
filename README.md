# Proyecto-de-Docker
Tarea 1 de computo en la nube

Construir la imagen
docker build -t hola-nube

Correr el contenedor 
docker run -p 82:80 -t [nombre de la imagen]
el 82:80 es el puerto donde se encuentra ahora mismo la imagen y el nombre de la imagen en este caso sería hola-nube

Asegurarse que el Dockerfile no tenga nada después tipo .txt ya que por eso todo salia mal xd
