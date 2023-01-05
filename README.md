# Durable Objects post handler

## Please read the [Durable Object documentation](https://developers.cloudflare.com/workers/learning/using-durable-objects)

Worker code is in `src/`. The Durable Object `Editor` class is in `src/Editor.ts`, and the eyeball script is in `index.ts`.

Rollup is configured to output a bundled ES Module to `dist/index.mjs`.

There's an example unit test in `src/index.test.ts`, which will run as part of `wrangler build`.   To run tests on their own use `npm test`.