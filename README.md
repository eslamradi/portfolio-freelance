# portfolio-freelance

Personal freelance site for [Eslam Radi](https://eslamradi.com) — web developer focused on online stores, payment systems, and company websites.

## Stack

Single static page: HTML, CSS, and a bit of vanilla JS. No build step.

## Preview locally

```bash
open index.html
```

Or serve it:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Structure

| File | Purpose |
|------|---------|
| `index.html` | Full site (markup, styles, theme toggle) |
| `me.PNG` | Portrait |
| `og.png` | Open Graph / social preview image |

## Theme

Light and dark themes follow system preference by default, and can be toggled manually. Choice is stored in `localStorage`.

## Analytics (Cloudflare)

Traffic is tracked with [Cloudflare Web Analytics](https://developers.cloudflare.com/web-analytics/) (privacy-friendly, no cookies). The beacon is in `index.html`; view reports in the Cloudflare dashboard under **Analytics & logs** → **Web Analytics**.

## Live

[eslamradi.com](https://eslamradi.com)
