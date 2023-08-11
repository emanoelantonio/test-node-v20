# Legacy Project

Este é um projeto de back-end em Nodejs, originalmente feito pelo [Erick Wendel](https://github.com/ErickWendel), para um Aulão sobre testes automatizados sem frameworks no Nodejs na versão >=20. Você pode encontrar o template [Aqui](https://github.com/ErickWendel/aulao-tajs-template/tree/main).
## Proposta do Erick Wendel
A proposta aqui é como criar testes Unitários e E2E numa aplicação legado. Então nos primeiros commits farei o que ele fez, para só depois iniciar a minha parte.

## Rodando

Restaure as dependencias e execute o projeto:
```sh
npm ci --silent
npm start
```

Seu programa estará rodando em [http://localhost:3000](http://localhost:3000)

Depois que a API estiver rodando você pode executar o script que vai disparar requests, obter o token e exibir a resposta da API.

Para isso execute
```sh
./run-api-requests.sh
```
A resposta deve parecer-se com:

```sh
Token capturado: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyIjoiZXJpY2t3ZW5kZWwiLCJtZXNzYWdlIjoiaGV5IGR1dXVkZSEiLCJpYXQiOjE2OTE2OTM4MjF9.VmPc9yY4tTXYQaILbY6JXK8IrmKKK0Z4hveVgRUIV9Y

Resposta da rota privada: {"result":"Hey welcome!"}
```