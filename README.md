# Denki Brew Landing

Static landing page for [denkibrew.com](https://denkibrew.com), deployed as a Cloudflare Worker with Static Assets.

## Project structure

- `landing/` contains the HTML, logo, and favicon assets served by Cloudflare.
- `wrangler.jsonc` configures the existing `withered-bush-ee11` Worker.

## Development

Install dependencies:

```sh
npm install
```

Run the site locally:

```sh
npm run dev
```

Validate a deployment without uploading:

```sh
npm run deploy:check
```

Deploy manually:

```sh
npm run deploy
```

Pushes to `main` are automatically deployed by Cloudflare Workers Builds.
