# My Gumroad Page Backup

These are backup copies of my Gumroad storefront pages. That's all this repo is —
a versioned backup, nothing more.

Live versions live at `dyno1927.gumroad.com`; Gumroad keeps no page history and
can't undo a deletion, so I keep the source under version control here.

## Files

- `profile.html` — my storefront page (`dyno1927.gumroad.com`)
- `about.html` — my About page (`/about`)
- `support.html` — my Support page (`/support`)

Each page is self-contained HTML I wrote by hand (inline CSS only — ready for
Gumroad's sanitizer).

## How I keep this in sync

1. Edit the page source here.
2. Preview it: `gumroad pages preview <file>`
3. Publish it: `gumroad pages push <profile|about|support> <file>`
4. Commit and push the change here.

The pages are intentionally public the moment they're published — this repo
just keeps history so I can roll back or restore.