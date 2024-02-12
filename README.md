# NLW - Expert NodeJS

Esta aplicação foi desenvolvida durante o NLW Expert na trilha de NodeJS, evento criado pela @RocketSeat, tendo como mentor o Diego Fernandes.

Trata-se de uma aplicação de votação em tempo real, durante as aulas foi levantado diversos conceitos interessantes que até então não tinha tido a oportunidade de colocar em prática e entender melhor como funciona algumas tecnologias.

As tecnologias utilizadas estão listadas abaixo:

## Techs

- NodeJS
- TypeScript
- Docker:
  - Docker compose: Docker Compose serve como Receita, pois está descrito as aplicações utilizadas, seja ela de terceirou ou não.
    image - utilizada como 'receita' pois contém os comandos para instalação do postgres em qualquer linux zerado.
    ports - redirecionamento de portas
    volumes - salvamento de arquivos dentro de um container na máquina.
    `docker ps`
    `docker compose up -d`
- PostgreSQL
- Redis

### Formas de conexão com banco de dados

- Driver nativo
- ORMs (Object Relational Mapper)
