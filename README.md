# Deland Rd Fireworks Performance Pass

Repo-ready static site for `/delandfireworks`.

## Pages

- `index.html` - clean event info / landing page
- `launch.html` - separate interactive fireworks theater with mini-player

## Why this version exists

V3 ran fireworks across the entire background. Fun, yes. Also a small battery crime.

This version moves fireworks into a dedicated page/container:

- no full-site canvas background
- no bloom canvas
- fewer particles
- quality selector: Low / Medium / High-ish
- particle cap
- lower device-pixel-ratio cap
- contained canvas
- mini-player stays on the launch page

## Files

- `index.html`
- `launch.html`
- `audio/announcement.mp3`
- `favicon.svg`
- `share-card.svg`
- `facebook-post.txt`
- `.nojekyll`

## Deploy

Upload the contents of this folder to:

`/delandfireworks`

Expected URL:

`https://bearicide.github.io/delandfireworks/`

Launch page:

`https://bearicide.github.io/delandfireworks/launch.html`
