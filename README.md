# Justin Huynh – Sports Performance

Personal portfolio site: coaching background, experience, and working demos of athlete-monitoring tools.

All demo athletes are ID codes and every value is simulated. No real athlete data is stored in this repository.

## Structure

- `index.html` – the whole site (Home, Sports Science, Experience, Contact)
- `assets/` – photos, resume PDF, logo icons, and the link-preview image

## Hosting

Static site, no build step. Works on GitHub Pages (Settings → Pages → Deploy from branch `main`, folder `/`) or as a Render Static Site (publish directory `.`).

## Writing (blog)

- Editor: https://justintrihuynh.github.io/admin/ (sign in with a GitHub fine-grained token that has Contents read/write on this repo only).
- New post → fill in Title, Date, Summary, Body → Save. Leave **Published** off to keep it a draft; turn it on and save to put it live.
- Drafts never appear on the site, but this repo is public, so a draft file can be read on GitHub.
- Posts live in `_posts/`, images in `assets/blog/`. The Writing tab appears on the site once at least one post is published.
