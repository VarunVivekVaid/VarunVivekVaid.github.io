# varunvaid.com

My personal site. Plain HTML — no build step, no dependencies, nothing to install.

## Editing

Everything lives in `index.html`. Open it, change the text, save.

- **Projects** — duplicate or delete an `<a class="item">` block. Order top to bottom is the order they appear.
- **Colors** — the `:root` block at the top of the `<style>` tag. Dark mode values are right below it.
- **Links** — the `<footer>` at the bottom.

## Publishing

Commit to `main`. GitHub Pages redeploys in under a minute.

```sh
git add -A && git commit -m "Update site" && git push
```

Or just edit the file on github.com and commit there.

## Notes

`CNAME` tells GitHub Pages which domain to serve. Leave it alone unless the domain changes.

DNS is managed at Cloudflare: four A records and four AAAA records on the apex pointing at GitHub Pages, plus a CNAME on `www`.
