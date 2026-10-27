# Qarma Labs

The public company website for **Qarma Labs**: a technology studio helping businesses and individuals navigate technology through expert consultation, AI and ICT solutions.

- **Live website:** https://qarma-labs.github.io/
- **Organization:** https://github.com/Qarma-Labs
- **Instagram:** https://www.instagram.com/qarmalabs/

## About the site

This responsive, single-page company website introduces Qarma Labs’ services—custom software, AI and automation, and ICT consultation—along with the organization’s public open-source work. Its company wording follows Qarma Labs’ own public profile and posts. It avoids invented client names, testimonials, performance statistics, contact details and project claims.

The site’s visual direction takes inspiration from Wabi.ai’s friendly editorial type, colorful cards and conversational product storytelling, while using Qarma Labs’ own brand and original copy. The official Qarma Labs GitHub organization avatar is included locally in `public/assets/`.

The workflow examples are illustrative concepts, not a functioning AI product. The site has no sign-in, enquiry backend, external API or analytics. Contact links open Qarma Labs’ public Instagram profile.

## Run locally

Requires Node.js 24.15 or newer.

```bash
npm ci
npm run dev
```

To verify and build:

```bash
npm run typecheck
npm test
npm run build
npm run preview
```

## Publish

Every push to `main` runs type checks and tests, builds `dist/`, and publishes it to GitHub Pages via [`.github/workflows/pages.yml`](.github/workflows/pages.yml). The Vite base is relative so the same build works at the organization’s root Pages URL.
