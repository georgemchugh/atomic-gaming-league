# Atomic Gaming League — public site

Player landing for [atomicgamingleague.com](https://atomicgamingleague.com).

## Live copy locks

- How to play: Steam WARDOGS (`1867240`) → Server Browser → US West → search `agl` or `AGL`
- Discord: `discord.gg/RWNCDqrZPZ`
- X: `@AGL__Esports`
- Mail: `hello@aglesports.com`
- Form: Tally `LZrl7p` (cup roster / waitlist)
- atomiclive! tease only — no date, no tickets. Slate: WARDOGS + SC2 + BYOC
- Not official Bulkhead / Team17. No purse language. No ®

## Do not publish on the player domain

`pitch/` is founder material. `_redirects` sends `/pitch/*` home. Keep pitch out of the public nav. Prefer a private repo for investor pages.

Do not add: game-server IP, prize figures, venue names, festival dates, official-league claims, investor CTAs.

## Deploy

Cloudflare Pages → this repo → no build command → output `/`.
Pretty URL: `/rules` rewrites to `rules.html`.
