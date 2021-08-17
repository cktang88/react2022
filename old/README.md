## react2021

This repository is a playground where I test various bleeding-edge React libraries. The base setup is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/zeit/next.js/tree/canary/packages/create-next-app) with TypeScript, and comes with React Fast Refresh.

### CSS

- chakra UI with [disabling focus borders](https://github.com/chakra-ui/chakra-ui/discussions/1921)
- ~~Theme UI~~
- tailwindCSS + plugins

### Fetching data

- `vercel/swr`
- `coinbase/rest-hooks`
- `react-query`
- Comparisons:
  - [data-fetching lib comparison](https://dev.to/justinramel/react-data-fetching-20ij)
  - [npm comparison](https://npmcompare.com/compare/react-query,rest-hooks,swr)
- React suspense!

### Auth

- Firebase
- Auth0 - with [Swizec/useAuth](https://github.com/Swizec/useAuth)
- [Next-auth.js](https://github.com/nextauthjs/next-auth)

### Forms

- react-final-form
- react-hook-form

### Tables

- [react-table v7](https://github.com/tannerlinsley/react-table/releases/tag/v7.0.0) (does no rendering)
- ~~`gridjs` (library-independent, simple+lightweight) - no great support for syntax highlighting react components~~

### State
- [Zustand](https://github.com/react-spring/zustand)
- [Jotai](https://github.com/pmndrs/jotai)
- [Valtio](https://github.com/pmndrs/valtio)
- ~~[Recoil](https://github.com/facebookexperimental/Recoil) - experimental~~

## Dev

```bash
yarn #install
yarn dev # start dev server
```

Open http://localhost:3000

### TODO:

- migrate to Snowpack v2 https://www.snowpack.dev/#migrating-an-existing-app ?
