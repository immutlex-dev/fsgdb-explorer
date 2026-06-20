# fsgdb graph explorer

Static build of the fsgdb graph explorer, served at
[explorer.immutlex.dev](https://explorer.immutlex.dev/) as a Cloudflare Worker
(static assets in `dist/`, configured by `wrangler.jsonc`).

It is a thin client: it talks only to an fsgdb instance running on your own
machine (your graph never leaves localhost) and ships no secrets. This repo
holds the compiled, installable web app only - it is a generated artifact and
is not edited by hand.

fsgdb is an immutlex add-on. See [immutlex.dev/fsgdb](https://immutlex.dev/fsgdb).
