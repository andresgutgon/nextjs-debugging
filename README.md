# Next debugging
This repo explore different types of nextjs apps and debugging the server with `NODE_OPTIONS='--inspect'`

1. `npm` Standalone NextJS app (Javascript)
2. `npm` Standalone NextJS app (Typescript)
3. `pnpm` Standalone NextJS app (Javascript)
4. `pnpm` Standalone NextJS app (Typescript)
5. `pnpm` workspace monorepo with a NextJS app (Javascript)
6. `pnpm` workspace monorepo with a NextJS app (Typescript)

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

