# MyLaravelStack
a Docker Stack for Laravel with apache

# How to use
- create or import your laravel project into the www folder and delete the dummy index.php.
- just run docker-compose up (-d to run it in background).
- if Laravel throw a unable to read error, run "chmod -R 777 /var/www/html/the_name_of_your_app/storage". (aparently only needed for linux).

# What's inside
 - PHP latest
 - MYSQL:latest
 - PHPMYADMIN:latest
 - COMPOSER:latest
 - NPM:latest


