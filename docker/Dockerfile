#Imagen que voy a utilizar como base
FROM httpd

#Etiquetado
LABEL maintainer="xcarroza@gmail.com"
LABEL project="imagina"
LABEL org.opencontainers.image.source="https://github.com/calamarzo/imagina-project"

#Como metadato, indicamos que el contenedor utiliza el puerto 80
EXPOSE 80

#Modificaciones sobre la imagen que he utilizado como base, en este caso alpine
COPY content/ /usr/local/apache2/htdocs/
