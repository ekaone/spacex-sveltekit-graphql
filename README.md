[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Fleerob%2Fsveltekit-graphql&project-name=sveltekit-vercel&repository-name=sveltekit-vercel&demo-title=SvelteKit%20%2B%20Vercel&demo-description=SvelteKit%20app%20fetching%20data%20from%20the%20SpaceX%20GraphQL%20API.&demo-url=https%3A%2F%2Fsveltekit-gql.vercel.app%2F&demo-image=https%3A%2F%2Fsveltekit-gql.vercel.app%2Ftwitter.png)

# SvelteKit + GraphQL

Example project using SvelteKit with the [SpaceX GraphQL API](https://api.spacex.land/graphql/), deployed to [Vercel](https://vercel.com).

## Developing

Once you've created a project and installed dependencies with `npm install`, start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

This uses the [Vercel Adapter](https://github.com/sveltejs/kit/tree/master/packages/adapter-vercel) for SvelteKit.

```bash
npm run build
```
