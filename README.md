# NLW6-Backend-node

## :satellite: Technologies

<ul>
  <li>Node JS</li>
  <li>TypeScript</li>
  <li>Express</li>
  <li>SQLite</li>
  <li>Prisma</li>
  <li>Socket.io</li>
</ul>

First, install all dependencies:

```bash
npm install
# or
yarn
```

Secund, create migrate

```bash
yarn prisma migrate dev
```

Third, run the project

```bash
yarn dev-server
```

##Routes:

<p>POST - http://localhost:3333/authenticate     -> Authenticate</p>
<p>POST - http://localhost:3333/messages         -> Create new message</p>
<p>GET  - http://localhost:3333/messages/last3    -> List the last messages</p>
<p>GET  - http://localhost:3333/profile           -> Get profile data</p>
