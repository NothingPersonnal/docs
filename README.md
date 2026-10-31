# Sonder player guide

Source for https://docs.playsonder.app, the player guide for Sonder.

All edits go through this repo. Every push to `main` deploys to the live site through the Mintlify GitHub app. Edits made in the Mintlify web editor or API should be committed back here, or the next push will overwrite them.

## Layout

- `docs.json`: site settings, colors, fonts, navbar and sidebar navigation
- `index.mdx`: the Introduction page
- `heroes/`, `town/`, `adventure/`, `roadmap/`: one folder per sidebar group

Hero images are served from https://playsonder.app/heroes/.

## Preview locally

```
npm i -g mint
mint dev
```

Then open http://localhost:3000.
