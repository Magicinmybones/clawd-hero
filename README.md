# Clawd hero

Static site converted from the supplied HTML prototype. The deployable files are in `public/`; images, fonts, CSS, and JavaScript are in `public/assets/`.

Live site: https://clawd-hero.pages.dev/

To publish a change to Cloudflare Pages from this folder:

```sh
npx wrangler pages deploy public --project-name clawd-hero --branch main
```

The Cloudflare Pages project uses direct upload, so a GitHub push alone does not deploy a change.
