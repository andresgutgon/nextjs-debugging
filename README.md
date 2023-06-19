# Next debugging
This repo explore different types of nextjs apps and debugging the server with `NODE_OPTIONS='--inspect'`

1. `npm` Standalone NextJS app pages (Javascript) [code here](./npm-standalone-nextjs-pages-javascript)
2. `npm` Standalone NextJS app pages (Typescript)
3. `npm` Standalone NextJS app app-directory (Javascript)
4. `npm` Standalone NextJS app app-directory (Typescript)
5. `pnpm` Standalone NextJS app pages (Javascript)
6. `pnpm` Standalone NextJS app pages (Typescript)
7. `pnpm` Standalone NextJS app app-directory (Javascript)
8. `pnpm` Standalone NextJS app app-directory (Typescript)
9. `pnpm` Monorepo with turborepo NextJS app app-directory (Typescript)

## Next documentation on debugging
Their docs about [debugging are here](https://nextjs.org/docs/pages/building-your-application/configuring/debugging)
`package.json`
```json
{
  "scripts": {
    "dev": "NODE_OPTIONS='--inspect' next dev"
  }
}
```
Once the server starts, open a new tab in Chrome and visit `chrome://inspect`, where you should see your Next.js application inside the Remote Target section. Click inspect under your application to open a separate DevTools window, then go to the Sources tab.

