# Fractional Icons

Static single-file website for Fractional Icons (fractionalicons.com).
No build step, no dependencies — `index.html` is the entire site.

## Deploy
Production deploys to Vercel when a pull request is merged into `main`. Preview deployments are disabled.

Required GitHub secret: `VERCEL_DEPLOY_HOOK_URL`.

## Notes
- Retainer CTAs currently point at placeholder intake links. Wire them to Stripe
  Payment Links once the recurring products are created in the Stripe dashboard.
- Calendar slots are placeholders until a real booking URL is added.
