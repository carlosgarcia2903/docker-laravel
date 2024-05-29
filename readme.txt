# Install and Set Up Laravel with Docker Compose

Setting up Laravel in the local environment with Docker using the LEMP stack that includes: Nginx, MySQL, PHP, and phpMyAdmin.

## Why use Docker for Development

- [x] Consistent development environment for the entire team.
- [x] You don't need to install a bunch of language environments on your system.
- [x] You can use different versions of the same programming language.
- [x] Deployment is easy

## How to Install and Run the Project

git clone https://github.com/carlosgarcia2903/docker-laravel.git
docker-compose exec app composer install
Copy .env.example to .env
docker-compose build
docker compose up -d
You can see the project on 127.0.0.1:8080

install composer in docker.
