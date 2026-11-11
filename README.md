# Hair by Cynthia

Static website for Hair by Cynthia (Meridian, ID). Hosted free on Cloudflare Pages: https://hairbycynthia.pages.dev

## Turning on online booking

Open `public/index.html` and paste Cynthia's Google Calendar booking link between the quotes here:

```html
<div id="site" data-booking-url="">
```

While it's empty, the site shows a "Book by text" card instead.

## Cloudflare

Pushing to `main` redeploys automatically. Pages settings: framework None, no build command, build output directory `public`.
