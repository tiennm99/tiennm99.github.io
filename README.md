# tiennm99.github.io

GitHub Pages default repo for the `tiennm99` user. Serves a one-line client-side redirect to [miti99.com](https://miti99.com).

## How it works

`index.html` sets `window.location.hostname = "miti99.com"` — anyone landing at `https://tiennm99.github.io/` gets bounced to the matching path on `miti99.com`.

## Why so minimal

The `<user>.github.io` slot is a single naming claim — you only get one per account. This repo exists just to **claim the slot and forward**. The real site lives in [miti99](https://github.com/tiennm99/miti99) (Hugo + Stack theme, hosted at `miti99.com`).

## Firebase Hosting targets

`firebase.json` declares 4 hosting targets (`miti99`, `meetee`, `tiennm`, `tiennm99`) sharing the same `public/` directory — so this repo is **also** the source for those Firebase domains when redirecting traffic during migrations.

## License

Apache-2.0 — see [LICENSE](LICENSE).
