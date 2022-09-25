# Ignite - Node - Desafio 01

[![en](/fatcow/16/flag_usa.png) English](./README.md)
<br>
[![pt-br](/fatcow/16/flag_brazil.png) Portuguese (Brazil)](./README.pt-br.md)

Primeiro desafio do curso Ignite, Trilha Node.js da Rocketseat. Acrescentei
o presente README e ESLint. O objetivo é passar em todos os testes
automatizados conforme instruções dadas no curso. Vou resumir somente
com a lista de rotas usando a sintaxe do HTTPie em linha de comando:

```s
http POST :3333/users name="John Doe" username="johndoe"
http GET :3333/todos username:johndoe
http POST :3333/todos username:johndoe title="test todo" deadline="2022-09-25"
http PUT :3333/todos/:id username:johndoe title="test todo" deadline="2022-09-25"
http PATCH :3333/todos/:id/done
http DELETE :3333/todos/:id
```

## Começando

Comece instalando as dependências do projeto:

```
yarn install
```

Em seguida rode o servidor de desenvolvimento:

```
yarn dev
```

Agora é só usar as rotas conforme documentado acima.
