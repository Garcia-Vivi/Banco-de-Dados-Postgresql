# Banco-de-Dados-Postgresql

## Desafio 01 

Crie um comando para criar um banco de dados PostgreSQL no ambiente do desenvolvedor de uma forma que cumpra os seguintes requisitos:

* O nome do banco de dados deve ser curso_docker
* O usuário de acesso ao banco deve ser docker_usr
* A senha do usuário deve ser docker_pwd

Coloque o comando que a equipe deve usar pra criar um banco de dados PostgreSQL.



## Tecnologias Utilizadas:

* Linux (Ubuntu 24.04.LTS)
* Docker
* PostgreSQL
 
  


 Para configurar corretamente o container, acessei o DockerHub.
 Pesquisei pela imagem do PostgreSQL. Acessei a documentação da imagem para pegar as variáves de ambiente.

No terminal, coloquei o comando.

```
docker container run -d -p 5432:5432 -e POSTGRES_PASSWORD="docker_pwd" -e POSTGRES_USER=docker_usr -e POSTGRES_DB=curso_docker library/postgres

```

Para confirmar que o que o container foi feito corretamente, dei o comando:

```
docker container ls

```

Que me mostrou o container em execução.














  



