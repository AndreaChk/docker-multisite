#Usar imagen de Ngnix
FROM nginx:alpine

#Eliminar archivos por defecto de Nginx
RUN rm -rf /usr/share/nginx/html/*

# Copiar los archivos del sitio web al Contenedor
COPY . /usr/share/nginx/html/ 

#Exponer el puerto 80 del Contenedor
EXPOSE 80