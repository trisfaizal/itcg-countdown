# ITCG 2027 Countdown

Static countdown site served by Cloudflare Workers Static Assets.

## Event configuration

The event target is configured in `public/index.html`:

- Event: #ITCG2027 — 6th IT Community Gathering
- Date: 16 January 2027
- Time: 08:00 WIB (UTC+7)
- Venue: Sutan Raja Hotel and Convention Centre

## Local development

```bash
npm install --save-dev wrangler
npx wrangler dev
```

## Deploy

```bash
npx wrangler deploy
```

## Custom domain

After deploying, add `countdown.komitkabe.id` under the Worker **Settings → Domains & Routes → Add → Custom Domain**.
Do not change the routes or Worker currently serving `komitkabe.id`.
