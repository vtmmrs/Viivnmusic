# Viivn — EPK site

Single self-contained HTML file, no build step needed.

## Setup

1. Create a new GitHub repo (e.g. `viivn-epk`).
2. Add `viivn-epk.html` to the repo root and **rename it to `index.html`** — GitHub Pages needs that exact name to serve the site at your domain's root.
3. Create an `images/` folder in the repo root (see table below for filenames).
4. Push, then in the repo go to **Settings → Pages**, set source to the `main` branch / root, and save. Your site will be live at `https://<username>.github.io/<repo-name>/` a minute or two later. A custom domain can be added from the same Pages settings screen.

## Adding thumbnails, hero shot & clip frames

The page already has image slots wired up — they just need matching files dropped into `images/`. Nothing else needs to change in the HTML; a missing file just leaves that spot blank (no broken-image icon), so you can add these gradually.

Suggested size: 16:9, at least 800×450px, JPG. The hero banner can be wider/taller (it gets cropped to cover the top section) — 1600×900 or bigger works well.

| Filename | Where it shows |
|---|---|
| `images/hero.jpg` | Hero banner, top of the home page |
| `images/mix-revolver-upstairs.jpg` | "Hybrid Set — Revolver Upstairs" mix card |
| `images/mix-festival-no23.jpg` | "Live at Festival No.23" mix card |
| `images/mix-arts-centre-melbourne.jpg` | "Live at Arts Centre Melbourne × Resonate" mix card |
| `images/mix-maribyrnong.jpg` | "Live at Maribyrnong River Lookout" mix card |
| `images/mix-live-set-2.jpg` | "Live Set" mix card (youtu.be/iT7CSb2zB2Q) |
| `images/clip-ultra-music-festival.jpg` | "Ultra Music Festival" clip card |
| `images/clip-festival-no23-crowd.jpg` | "Festival No.23" clip card |
| `images/clip-electric-breakfast-club.jpg` | "Electric — The Breakfast Club" clip card |
| `images/clip-hybrid-set.jpg` | "Hybrid Set" clip card |
| `images/clip-on-stage.jpg` | "On Stage" clip card |
| `images/clip-behind-the-decks.jpg` | "Behind the Decks" clip card |
| `images/clip-short-clip.jpg` | "Short Clip" clip card |

The existing three gallery photos on the Press Kit page are already embedded directly in the HTML, so no separate files are needed for those.

## Note on the Dropbox photo library

Wasn't able to pull the photos from the Dropbox folder into the page yet — happy to do that in a future session once file access is working again, or you can add them straight into `images/` / the gallery yourself in the meantime.
