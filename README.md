# [Next.js](https://nextjs.org/)

- create-next-app - [Github](https://github.com/vercel/next.js/tree/canary/packages/create-next-app), [Article in Docs](https://nextjs.org/docs/api-reference/create-next-app)
- Official Next.js examples - [Github](https://github.com/vercel/next.js/tree/canary/examples)
- Example : api-router - [Github](https://github.com/vercel/next.js/tree/canary/examples/api-routes), [Article in Docs](https://nextjs.org/docs/api-routes/introduction)
- Example : with-expo-typescript - [Github](https://github.com/vercel/next.js/tree/canary/examples/with-expo-typescript). 
- To create a `nextjs ready apps`, follow below examples commands - 

```bash
# For yarn users-
yarn create next-app my-next-app # Where my-next-app would be name of project.
yarn create next-app --example api-routes api-router-app
yarn create next-app --example with-expo-typescript with-expo-typescript-app

# For npm users-
npx create-next-app my-next-app # It uses yarn by default to install dependencies. LOL 🍉
npx create-next-app --example api-routes api-router-app
npx create-next-app --example with-expo-typescript with-expo-typescript-app
```

- Create Next App Cli - [Docs](https://nextjs.org/docs/api-reference/create-next-app)

# Commmon Commands - Sahil Rajput

`nd` - To run dev server i.e., `npm run dev` or `yarn dev` (`next dev`)

Now, you can browse your server(with **webpack-fast-refresh enabled**) at [http://localhost:3000](http://localhost:3000) 

`ns` - To serve producton build via `npm start`  or `yarn start` (`next start`).  (Note: Make the production build first via below command.)

`nr build` - To make a produciton build via `npm  run build` or `yarn ` (`next build`) 

`nr build:export` - To make a static build of the app in `out` directory.  (`next build && next export`)

***

## Other Details

##### Tip: You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

- [Next.js Docs](https://nextjs.org/docs)
- [Next.js - Getting Started](https://nextjs.org/docs/getting-started), [#Manual Setup](https://nextjs.org/docs#manual-setup)
- [Basic Features - Pages](https://nextjs.org/docs/basic-features/pages)
- [Built-In CSS support - Docs](https://nextjs.org/docs/basic-features/built-in-css-support)
- [Getting Started - Next.js Docs](https://nextjs.org/docs/getting-started)
- [Learn Next.js - Next.js Docs](https://nextjs.org/learn)
- [Static Html Export - Article - Next.js Docs](https://nextjs.org/docs/advanced-features/static-html-export)
- [Deploy your Next.js app to Vercel Platform](https://vercel.com/import?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) (from the creators of Next.js)
- [Next.js deployment documentation - Next.js Docs](https://nextjs.org/docs/deployment) - Nextjs Deployment Documentation

## next cli - [Docs](https://nextjs.org/docs/api-reference/cli)

```bash
$ next -h
Usage
  $ next <command>

Available commands
  build, start, export, dev, telemetry

Options
  --version, -v   Version number
  --help, -h      Displays this message

For more information run a command with the --help flag
  $ next build --help
```

