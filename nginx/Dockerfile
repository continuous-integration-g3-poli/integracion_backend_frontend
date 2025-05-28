# Imagen base de Nginx
FROM nginx:stable-alpine

# Copiar archivo de configuración nginx
COPY default.conf /etc/nginx/conf.d/default.conf

# Copiar el frontend construido desde la imagen PHP (Laravel)
COPY --from=drios8331/fronted:latest /var/www/html /var/www/html
