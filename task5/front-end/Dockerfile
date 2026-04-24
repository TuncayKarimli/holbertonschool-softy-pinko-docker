FROM nginx:latest

# Copy front-end files to the specified path
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy the Nginx config to the default configuration directory
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
