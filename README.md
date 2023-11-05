## Getting Started

### This is the issue tracker project.

### Tech Stack:

1. Next.js
2. Prisma
3. axios
4. next-auth
5. Typescript
6. Zod, recharts, TailwindCSS

To get started, follow these steps:

1. Clone this repository to your local machine.
2. In the project folder, rename **.env.example** to **.env** (no period after).
3. Set **all** the environment variables according to the instructions I've included in the file. If you don't set them properly, the application is not going to work.
4. Run `npm install` to install the dependencies.
5. Run `npx prisma migrate dev` to generate your database tables.
6. Run `npm run dev` to start the web server.

---

- $ Run 'openssl rand -base64 32' to generate a secret.
