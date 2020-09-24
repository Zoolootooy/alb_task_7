# How to start
`docker-compose up -d`

If you go to `localhost:10080/` you will see the index page with phpinfo.

# Ports
- MySQL: 13306
- Redis: 16379
- NGINX: 10080, 10443
- app: 9000

# MySQL
- v.:5.7.31
- user: root
- pass: root
- config file is located at `mysql/my.cnf`

# Redis
- v.6.0.8-alpine
- no pass

# App
- PHP v. 7.3-fpm
- config file is located at `php/local.ini`

# Webserver
- v. nginx:alpine
- root folder is `/var/www/public`
- config file is located at `nginx/conf.d/app.conf`
