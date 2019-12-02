## 5.6-apache

    docker run --name php56 -h php56 -d -p 8056:80 -e TZ=America/Sao_Paulo -v /var/www/html/:/var/www/html -w /var/www/html atuadevops/php-apache-antigos:5.6-apache

## 7.0-apache

    docker run --name php70 -h php70 -d -p 8070:80 -e TZ=America/Sao_Paulo -v /var/www/html/:/var/www/html -w /var/www/html atuadevops/php-apache-antigos:7.0-apache
