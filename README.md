# nuxt-browser-console

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![Github Actions CI][github-actions-ci-src]][github-actions-ci-href]
[![Codecov][codecov-src]][codecov-href]
[![License][license-src]][license-href]

> With this module, you can use console functions to show your message/data. No matter you are using this module inside the server-side or client-side events, the message is always shown in the browser console. This is good for monitoring server events on production (for example, Axios calls and response from server/asyncData functions can be logged into the browser console).

[📖 **Release Notes**](./CHANGELOG.md)

## Setup

1. Add `nuxt-browser-console` dependency to your project

```bash
yarn add nuxt-browser-console # or npm install nuxt-browser-console
```

2. Add `nuxt-browser-console` to the `modules` section of `nuxt.config.js`

```js
{
  modules: [
    // Simple usage
    'nuxt-browser-console',

    // With options
    ['nuxt-browser-console', { /* module options */ }]
  ]
}
```

## Development

1. Clone this repository
2. Install dependencies using `yarn install` or `npm install`
3. Start development server using `npm run dev`

## License

[MIT License](./LICENSE)

Copyright (c) Mohammad Saleh Fadaei ([@ms-fadaei](https://github.com/ms-fadaei))

<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/v/nuxt-browser-console/latest.svg
[npm-version-href]: https://npmjs.com/package/nuxt-browser-console

[npm-downloads-src]: https://img.shields.io/npm/dt/nuxt-browser-console.svg
[npm-downloads-href]: https://npmjs.com/package/nuxt-browser-console

[github-actions-ci-src]: https://github.com/ms-fadaei/nuxt-browser-console/workflows/ci/badge.svg
[github-actions-ci-href]: https://github.com/ms-fadaei/nuxt-browser-console/actions?query=workflow%3Aci

[codecov-src]: https://img.shields.io/codecov/c/github/ms-fadaei/nuxt-browser-console.svg
[codecov-href]: https://codecov.io/gh/ms-fadaei/nuxt-browser-console

[license-src]: https://img.shields.io/npm/l/nuxt-browser-console.svg
[license-href]: https://npmjs.com/package/nuxt-browser-console
