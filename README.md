# lamp-docker
Simple docker container for LAMP stack project: php, mariadb, phpmyadmin

## install
- cd myproject
- git clone git@github.com:BlackShabat/lamp-docker.git docker
- cd docker
- docker-compose up -d
- cd ../

You can create demo index.php in the root of myproject folder with <?php phpinfo(); ?> content for testing

- access to app with http://localhost/
- access to phpmyadmin with http://localhost:8080/
