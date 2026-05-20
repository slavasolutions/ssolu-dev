# ssolu.dev

Workshop landing page for [Slava Solutions](https://slavasolutions.com) projects and experiments.

Live: <https://ssolu.dev>

## What's here

A single static `index.html` listing the projects under the `@ssolu/*` npm scope and `slavasolutions/*` GitHub org. Visual language follows the [Mosaic](https://github.com/slavasolutions/mosaic) explainer — same cream + serif + mono palette, distinct copper accent.

## Stack

Static HTML. No build step. No deps. The logo assets live in `assets/`.

## Deploy

Cloudflare Pages project `ssolu-dev` builds on push. Custom domain: `ssolu.dev`.

```sh
wrangler pages deploy . --project-name=ssolu-dev --branch=main
```

## License

Apache 2.0 — see [LICENSE](./LICENSE).
