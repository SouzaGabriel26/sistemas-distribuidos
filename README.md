# Projeto Docker com PHP, MySQL e PhpMyAdmin

Este projeto utiliza Docker e Docker Compose para orquestrar os contêineres de uma aplicação PHP com um banco de dados MySQL e uma interface de administração via PhpMyAdmin.

## Como rodar os contêineres

1. Certifique-se de ter o [Docker](https://www.docker.com/get-started) e o [Docker Compose](https://docs.docker.com/compose/install/) instalados em sua máquina.

2. Para **iniciar os contêineres**, use o comando:

   ```bash
   docker compose -f ./php/docker-compose.yml up -d
   ```

3. Para **para os contêineres**, use o comando:
 
  ```bash
  docker compose -f ./php/docker-compose.yml down
  ```

## Interagir com o sistema
- CRUD php: `http://localhost:80`
- phpMyAdmin: `http://localhost:8000`
- Portainer: `http://localhost:9000`


## Video explicativo
- https://www.youtube.com/watch?v=qmw4rD53A-w&t=2s
