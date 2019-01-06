This is a basic LAMP stack environment built using Docker Compose. It consists following:

PHP
Apache
MySQL
phpMyAdmin
As of now, we have 3 different branches for different PHP versions. Use appropriate branch as per your php version need:

5.6.x
7.1.x
7.2.x

Installation
Clone this repository on your local computer and checkout the appropriate branch e.g. 7.1.x. Run the docker-compose up -d.

git clone https://github.com/gulnurullah/docker-lamp-redis.git
cd docker-lamp-redis/
docker-compose up -d
Your LAMP stack is now ready!! You can access it via http://localhost:8000.
