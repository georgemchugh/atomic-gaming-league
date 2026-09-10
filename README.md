# Atomic Gaming League — waitlist

Static waitlist landing for [atomicgamingleague.com](https://atomicgamingleague.com).

- Copy: Hero A + About/games + locked footer
- Join: `@AGL__Esports` · Discord `discord.gg/RWNCDqrZPZ` · Server `agl.xrealm.gg`
- Form: Tally embed `https://tally.so/r/LZrl7p`

## Local preview

Open `index.html` in a browser, or:

```bash
npx --yes serve .
```

## Deploy to Cloudflare Pages

1. Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git
2. Select `georgemchugh/atomic-gaming-league`
3. Build settings:
   - Framework preset: None
   - Build command: *(leave empty)*
   - Build output directory: `/`
4. Save and Deploy
5. Custom domains → add `atomicgamingleague.com` and `www` (zone already on Cloudflare)

Or direct upload:

```bash
npx wrangler pages deploy . --project-name=atomic-gaming-league
```

## Claim bans (do not add)

No purses, venues, festival dates, official-league language, investor CTAs, QONZER, or “Atomic Gaming” without “League”.
