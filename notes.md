Build an AI-Powered Fullstack Next.js App, v3

* fullstack web app
* build a UI from a design spec
* build out and deploy an API
* setup continuos deployment with CI
* host the app with a custom domain

Tech stack:
- React, Node.js, Typescript, Postgres.

https://github.com/Hendrixer/fullstack-ai-nextjs

- CRUD
- auto-save
- authentication

Start:
npx create-next-app@latest mood
cd mood
npm run dev

auth:
https://clerk.com/
npm install @clerk/nextjs


db:
https://planetscale.com/

ORM:
https://www.prisma.io/


pscale auth login
pscale branch create *mood* dev
pscale connect mood dev --port 3309

 npm install @prisma/client
 npm install prisma --save-dev
 npx prisma init
 npx prisma db push