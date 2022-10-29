
# ignite-desafio-node-documentando-com-Swagger

Projeto desenvolvido durante a trilha de Node do Ignite da Rocketseat. O objetivo deste desafio foi realizar a documentação das rotas de uma API através do Swagger, utilizando uma aplicação já funcional. 

Para isso, foi utilizada a aplicação desenvolvida no [desafio anterior](https://github.com/Whalesson-Ferreira/ignite-desafio-node-introducao-ao-SOLID), que segue padrões de código e princípios do SOLID, além de partir de um [template](https://github.com/rocketseat-education/ignite-template-introducao-ao-SOLID), que já vem com os testes configurados e os padrões de código definidos.

Essa aplicação realiza a listagem e cadastro de usuários, onde a listagem só pode ser feita caso o usuário seja admin, através das seguintes rotas:

## Rotas

- Cadastrar usuário
- Tornar usuário em admin
- Listar usuários
- Buscar usuário pelo id

## O que foi documentado

- Informações gerais da API, como nome e descrição
- Rotas
- Parâmetros de rotas
- Corpo da requisição
- Respostas de sucesso e erro
- Exemplos de corpo de requisição e retorno de rotas

## Stack utilizada

- [Nodejs](https://nodejs.org/en/docs/) com [TypeScript](https://www.typescriptlang.org/docs/)

## Ferramentas

- framework [express](https://expressjs.com/en/guide/routing.html) para trabalhar com rotas
- [uuid](https://github.com/uuidjs/uuid#readme) para criar um identificador único universal
- [ts-node-dev](https://github.com/wclr/ts-node-dev#readme) para compilar o código Typecript e reiniciar automaticamente quando os arquivos são modificados
- [eslint](https://eslint.org/) para identificar padrões de código em desacordo com as regras pré-estabelecidas
- [prettier](https://prettier.io/) para formatar o código de acordo com essas regras
- [swagger-ui-express](https://github.com/scottie1984/swagger-ui-express#readme) para documentar a API

## Instalação

Execute yarn para instalar as dependências:

```bash
  cd my-project
  yarn
```

Execute o projeto com yarn dev

```bash
  yarn dev
```

Acesse a url da documentação no navegador

  - [/api-docs/](http://localhost:3333/api-docs/)

## Aprendizados

O desenvolvimento deste projeto contribuiu para apresentar uma maneira de documentar a aplicação e reforçar a sua importância, já que uma documentação clara de uma API é essencial para quem irá consumi-la, fazendo com que rotas, parâmetros e respostas sejam conhecidos pelo desenvolvedor.

## Documentação

[NodeJs](https://nodejs.org/en/docs/) |
[TypeScript](https://www.typescriptlang.org/docs/) |
[Express](https://expressjs.com/en/guide/routing.html) |
[uuid](https://github.com/uuidjs/uuid#readme) |
[ts-node-dev](https://github.com/wclr/ts-node-dev#readme) |
[eslint](https://eslint.org/) |
[prettier](https://prettier.io/) |
[Template da aplicação](https://github.com/rocketseat-education/ignite-template-introducao-ao-SOLID) |
[desafio-anterior](https://github.com/Whalesson-Ferreira/ignite-desafio-node-introducao-ao-SOLID) |
[swagger-ui-express](https://github.com/scottie1984/swagger-ui-express#readme) |
[swagger-io](https://swagger.io/specification/)

## Autores

- [@Whalesson-Ferreira](https://github.com/Whalesson-Ferreira)
