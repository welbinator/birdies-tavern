# Birdie's Tavern + Grill

Marketing website for **Birdie's Tavern + Grill** — a golf-themed neighborhood grill in Ankeny, Iowa.

- **Address:** 1975 N Ankeny Blvd, Unit 117, Ankeny, IA 50023
- **Phone:** (515) 608-6878
- **Hours:** Tue–Thu 11a–9p · Fri–Sat 11a–10p · Sun 11a–8p · Closed Mondays

## Stack
Static single-page site served via a Cloudflare Worker with static assets.

## Deploy
```bash
export CLOUDFLARE_API_TOKEN=...
export CLOUDFLARE_ACCOUNT_ID=...
npx wrangler deploy
```

Menu and prices sourced from the restaurant's public DoorDash/Uber Eats listings (Oct 2026) and subject to change.
