# Nuxt Plotly Module

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![License][license-src]][license-href]
[![Nuxt][nuxt-src]][nuxt-href]

📊 `nuxt-plotly` module is thin Nuxt3 wrapper for [plotly.js](https://plotly.com/javascript/)

- [✨ &nbsp;Release Notes](/CHANGELOG.md)
  <!-- - [🏀 Online playground](https://stackblitz.com/github/your-org/nuxt-plotly?file=playground%2Fapp.vue) -->
  <!-- - [📖 &nbsp;Documentation](https://example.com) -->

## Features

<!-- Highlight some of the features your module provide here -->

- 🎇 &nbsp; All plotly.js methods and events
- 🗾 &nbsp; Auto redraw on screensize changes and props update
- 🚀 &nbsp; Data reactivity

## Quick Setup

1. Add `nuxt-plotly` dependency to your project

```bash
# Using pnpm
pnpm add -D nuxt-plotly

# Using yarn
yarn add --dev nuxt-plotly

# Using npm
npm install --save-dev nuxt-plotly
```

2. Add `nuxt-plotly` to the `modules` section of `nuxt.config.ts`

```js
export default defineNuxtConfig({
  modules: ["nuxt-plotly"],
});
```

That's it! You can now use Nuxt Plotly Module in your Nuxt app ✨

## Development

```bash
# Install dependencies
npm install

# Generate type stubs
npm run dev:prepare

# Develop with the playground
npm run dev

# Build the playground
npm run dev:build

# Run ESLint
npm run lint

# Run Vitest
npm run test
npm run test:watch

# Release new version
npm run release
```

<!-- Badges -->

[npm-version-src]: https://img.shields.io/npm/v/nuxt-plotly/latest.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-version-href]: https://npmjs.com/package/nuxt-plotly
[npm-downloads-src]: https://img.shields.io/npm/dm/nuxt-plotly.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-downloads-href]: https://npmjs.com/package/nuxt-plotly
[license-src]: https://img.shields.io/npm/l/nuxt-plotly.svg?style=flat&colorA=18181B&colorB=28CF8D
[license-href]: https://npmjs.com/package/nuxt-plotly
[nuxt-src]: https://img.shields.io/badge/Nuxt-18181B?logo=nuxt.js
[nuxt-href]: https://nuxt.com
