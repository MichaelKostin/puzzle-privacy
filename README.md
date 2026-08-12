# Puzzle Garden legal pages

Static legal and support pages for **Puzzle Garden**, translated into every locale supported by the app.

## Locales

English is served from the site root. Localized pages use locale directories matching the app's supported locale identifiers: `es`, `fr`, `de`, `pt-BR`, `ru`, `zh-Hans`, `ja`, `ko`, `hi`, `tr`, and `pl`.

## Pages

- `/privacy-policy.html`, `/terms-of-use.html`, and `/support.html`
- `/{locale}/privacy-policy.html`, `/{locale}/terms-of-use.html`, and `/{locale}/support.html`
- `/index.html` and `/{locale}/index.html` locale landing pages

The site has no build step. Serve the directory with any static web server.

Before deploying to a custom domain, add a `CNAME` file containing the final hostname.
