## Passo a passo para rodar o projeto:

- Clone o repositório
- Acesse a pasta do projeto e rode docker-compose up -d
- Acesse o container docker-compose exec curso_x bash
- Rode o comando composer install
- Gere a key do projeto Laravel php artisan key:generate
- Rode o comando php artisan migrate
- Rode o comando php artisan jwt:secret
- Digite Exit para Sair do container
- Rode npm install

## Acesse o Projeto

Acesse a URL http://localhost:8989 e divirta-se
