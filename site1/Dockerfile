FROM nginx:alpine

# Limpiar el HTML por defecto
RUN rm -rf /usr/share/nginx/html/*

# Copiar todo el contenido del sitio
COPY . /usr/share/nginx/html/

# Permisos correctos para archivos estáticos
RUN chmod -R 755 /usr/share/nginx/html && \
    chown -R nginx:nginx /usr/share/nginx/html

# Exponer puerto 80
EXPOSE 80
