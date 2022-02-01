# Simple Laravel starter with Docker

1. Build the containers
   1. `docker-compose up -d --build`
2. Install Laravel
   1. `docker-compose run --rm composer install`
3. Install node packages
   1. `docker-compose run --rm npm install`
4. Access the site at `site.local`