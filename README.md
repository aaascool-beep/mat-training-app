# MAT Training App (Ready)

## Run locally
```bash
npm install
npm run dev
```

## Deploy (Netlify/Vercel)
1. Create new site from your Git repo or upload `dist/` after:
```bash
npm run build
```

## Payments (No backend needed)
- Create a **Stripe Payment Link** in your Stripe Dashboard.
- In the app, go to **Admin → Settings** and paste the URL.
- Trainees click **Buy Course** to pay; you can unlock by verifying payment manually or add a backend later for automatic verification.

## Admin
- Default passcode: `1234` (change it in Admin → Settings).

## Languages
- Switch EN/ES/AR from the header.

## Export
- Admin → **Export CSV** for completions & quiz score.
