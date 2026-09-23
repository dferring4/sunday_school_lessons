# Lesson 29 – The Jews Resist the Holy Spirit (Acts 6–7)

Static comic-style presentation. No build step.

## Deploy (GitHub + Cloudflare Pages)
1. Create a GitHub repo and upload everything in this folder (index.html, img/, _headers).
2. Cloudflare dashboard → Workers & Pages → Create → Pages → Connect to Git → pick the repo.
3. Framework preset: None. Build command: (leave blank). Build output directory: `/`
4. Deploy. Every push to the repo redeploys automatically.

## Presenting
- Home page: click any panel. Each slide has a big HOME burst (top-right).
- → / Space / Page Down / clicker "next": reveals the next caption, then moves to the next slide.
- ← / Page Up: goes back.  H or Esc: home.  T (or clicker "blank" key): hide/show all text.  F: full screen.
- Clicking anywhere on the picture also advances.
- Direct links work: yoursite.pages.dev/#7 opens slide 7.

## Editing text or positions
All slide text lives in the `SLIDES` list near the bottom of index.html.
Each caption is `[step, "position", html]`; positions are % of the picture.
