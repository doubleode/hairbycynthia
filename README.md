# Hair by Cynthia

Static website for Hair by Cynthia (Boise). Hosted free on Cloudflare (Worker, static assets): https://hairbycynthia.doubleode.workers.dev

## Turning on online booking

Open `public/index.html` and paste Cynthia's Google Calendar booking link between the quotes here:

```html
<div id="site" data-booking-url="">
```

While it's empty, the site shows a "Book by text" card instead.

## Cloudflare

Pushing to `main` redeploys automatically. Only the `public/` folder is published (see `wrangler.jsonc`).
