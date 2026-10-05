# Preet & Pankti — Wedding Invitation Website

A ready-to-publish static copy of the wedding invitation site.
Just `index.html` + the `assets/` folder — no build step, no server needed, and **no domain to buy**.

## What's inside

- `index.html` — the whole site: locked cover, 8 invitation pages (Grah Shanti, Haldi, Sangeet, Baraat, Wedding Ceremony, Our Families), Social Media page, RSVP dialog, background music, dot/swipe/keyboard/wheel navigation, pinch-to-zoom
- `assets/` — all artwork (JPEG + lighter WebP copies), the two Instagram QR codes, tiny ambient backgrounds, cover side-panel strips, and the background music
- Everything works with no backend: tap targets, WhatsApp RSVP, map links, music with mute

## Publish with GitHub Pages (free, no domain needed)

GitHub gives you a free web address like `https://YOUR-USERNAME.github.io/REPO-NAME/` — nothing to buy.

1. Create a **free GitHub account** at https://github.com (skip if you already have one).
2. Create a **new public repository** — e.g. `preet-pankti-wedding`.
   (On GitHub: **+ → New repository**, give it a name, keep it **Public**, click **Create repository**.)
3. Upload this package into the repo:
   - On the repo page, click **Add file → Upload files**.
   - Drag in `index.html` **and** the `assets` folder together. (`index.html` must sit at the top level of the repo, with `assets/` right next to it.)
   - Click **Commit changes**.
4. Enable Pages: go to **Settings → Pages**.
5. Under **Build and deployment**, set **Source** to **Deploy from a branch**, branch `main`, folder `/ (root)`. Click **Save**.
6. Wait a minute or two, then open **Settings → Pages** again — GitHub shows your live link:
   `https://YOUR-USERNAME.github.io/REPO-NAME/`

That's your own website address — share it on WhatsApp just like any link.

## Updating the site later

This copy does **not** update itself when the main invitation is edited. For every round of changes, ask for a fresh export package and repeat step 3 (upload the new `index.html` + `assets/`, overwriting the old files). GitHub Pages picks up the new version within a minute or two.

## Notes

- The page title is **Preet & Pankti Wedding Invitation** (browser tab + link previews).
- To change the WhatsApp number, map links, or hashtag later, edit them directly in `index.html` (search for `wa.me`, `maps.app.goo.gl`, `preetkiShaadi`).
- To replace any artwork, swap the file in `assets/` keeping the same filename (there is a `.jpg` and a lighter `.webp` for each page — replace both, or delete the `.webp` and the page will fall back to the `.jpg` automatically).
