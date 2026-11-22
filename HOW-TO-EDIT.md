# how to edit my site

everything on the site lives in `content.txt`. open it on github, click the pencil, change it, click "commit changes". the site updates in about a minute.

## sections in content.txt

- `# now` — the one line in the "right now" box.
- `# home` — `photo: images/...` then the lines that show under the photo (one per line).
- `# about` — one line = one paragraph. `## heading` makes a heading. `linkedin <url>` / `instagram <url>` become icons.
- `# songs` — songs section. whatever you write after `# songs` becomes the heading (e.g. `# songs i've been listening`). one per line: paste the spotify share link, then optionally ` — a note`. e.g. `https://open.spotify.com/track/abc123 — 3am walks home`. the section hides itself when empty.
- `# fafo` — one idea per line: `name — note` (note is optional).
- `# requests` — ideas people sent me: `idea — from name` (from is optional).
- `# friends` — one photo per line: `images/file.jpg | who | caption | 2025-06`
- `# elsewhere` — one place per line: `images/file.jpg | place | caption | 2025-06`
- `# writing` — each entry starts with `## 2026-11-21 21:14 | title` (title optional). the text goes underneath. a blank line makes a new paragraph.

## shelf

- `# shelf` then `## books`, `## shows`, `## films`, `## music`, `## links`. one item per line: `Title | author or network | genre | what it's about | my own note` (everything after the title is optional, but keep the `|` dividers in order). covers go in `images/shelf/` named after the title in lowercase with dashes, e.g. `the-diary-of-a-ceo.jpg`. books without a cover get a plain designed cover.

## things i like

- `# likes`: random images that show up as a collage when you scroll down on the home page. one per line: `images/file.jpg` (optionally ` | a few words`).

## notes vs writing

- `# writing`: blogs and serious pieces. each starts with `## 2026-11-21 21:14 | title`.
- `# notes` (or `# musings`): everyday random stuff, shows on the home page under "musings" (scroll down past the photo). each starts with `## 2026-11-22 21:14` (no title), text underneath. newest shows first.

## adding photos

1. on github, click into the `images` folder first (so the photo lands there).
2. click "add file" → "upload files", drag the photo in, click "commit changes".
3. use jpg or png. iphone photos are often .heic, which browsers can't show — on iphone, set settings → camera → formats → "most compatible", or screenshot / export the photo as jpg first.
4. avoid spaces in the file name (rename `IMG 2041.jpg` to `scooter.jpg`).
5. open `content.txt`, add a line under `# friends` (or `# elsewhere`), e.g.
   `images/scooter.jpg | names | caption | 2025-01`
   names, caption and date are all optional, but keep the `|` dividers.
