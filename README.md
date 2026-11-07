# lmtassistant.com

The marketing site for LMT Assistant: home, FAQ, Privacy Policy and Terms.
Plain static HTML, no build step.

## Deploying

The Vercel project `lmtassistant-website` is connected to this repo:

- **Push or merge to `main`** → deploys to production (lmtassistant.com).
- **Pull requests** → a preview link appears on the PR. Check it before merging.

Don't run `vercel --prod` from another folder; this repo is the source of truth.

## Files

| Path | Page |
|---|---|
| `index.html` | Home |
| `faq/index.html` | /faq |
| `privacy/index.html` | /privacy |
| `terms/index.html` | /terms |
| `vercel.json` | Clean URLs, the /tutorial redirect, security headers |

When the app changes what it does with data (new service providers, new features
that send data anywhere), update the Privacy Policy here in the same release.
