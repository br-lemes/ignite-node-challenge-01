# Ignite - Node - Challenge 01

[![en](/fatcow/16/flag_usa.png) English](./README.md)
<br>
[![pt-br](/fatcow/16/flag_brazil.png) Portuguese (Brazil)](./README.pt-br.md)

First challenge for the Rocketseat's course Ignite, Node.js Trail. I added
the present README and ESLint. The goal is to pass all automated tests as
instructed in the course. I'll just summarize with the list of routes using
HTTPie command line syntax:

```s
http POST :3333/users name="John Doe" username="johndoe"
http GET :3333/todos username:johndoe
http POST :3333/todos username:johndoe title="test todo" deadline="2022-09-25"
http PUT :3333/todos/:id username:johndoe title="test todo" deadline="2022-09-25"
http PATCH :3333/todos/:id/done
http DELETE :3333/todos/:id
```

## Getting Started

Start by installing the project dependencies:

```
yarn install
```

Then run the development server:

```
yarn dev
```

Now just use the routes as documented above.
