# create-svelte with tailwind and daisyUI additions

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Getting started
Set up the prisma env
```bash
cat .env
```
```bash
DATABASE_URL="file:./dev.db" # Change to whatever your postgres db is
```

## Developing
```bash
npm i

npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open

# Prisma commands
npx prisma migrate dev --name init
npm prisma studio
```

## Building

To create a production version of your app:

```bash
npm run build
npm serve # ? need to double check
```

You can preview the production build with `npm run preview`.