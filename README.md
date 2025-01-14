# Rollup starter library template
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fvidesk%2Fmongoose-dummy.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fvidesk%2Fmongoose-dummy?ref=badge_shield)


Use this Rollup configuration template with library projects. Is not recommended use with frameworks like Vue, Svelte, React or Angular, otherwise modify with your own Rollup configuration.

The compiled files will be exported and minify in `umd`, `cjs` (CommonJS), and `esm` (ES Modules) format. Also, it's used Babel for maximize compatibility of your code in browsers.

## Development

```shell
npm run dev
```

In development mode you will be able to play adding your code on `public/main.js`. Rollup automatically add a hot-reload on `bundle.js` file, where is the original library code. Remember, in dev mode only exports the UMD version (browsers).

## Production

```shell
npm run build
```

## Publish (NPM)

```
npm run upload
```

To publish to NPM can execute the command script `upload`. With the command will build and upload based on version in `package.json`.



## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fvidesk%2Fmongoose-dummy.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fvidesk%2Fmongoose-dummy?ref=badge_large)