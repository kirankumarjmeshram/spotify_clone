# create-svelte

## CSS Library used:

https://github.com/sindresorhus/modern-normalize

```
$ npm install modern-normalize

npm i -D sass

npm i svelte-preprocess
```

Sass functions and mixins to use media queries rules. :
https://github.com/unsass/breakpoint =>
`` npm install @unsass/breakpoint``

**Fontsource Metropolis**

The CSS and web font files to easily self-host the “Metropolis” font. Please visit the main [Fontsource website](https://fontsource.org/fonts/metropolis) to view more details on this package.

``npm i @fontsource/metropolis``

Spotify Authorization Code Flow
    https://developer.spotify.com/documentation/web-api/tutorials/code-flow


PKCE: What and Why? => https://dropbox.tech/developers/pkce--what-and-why-

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash


# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
