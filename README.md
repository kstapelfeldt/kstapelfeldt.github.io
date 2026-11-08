# Kirsta Stapelfeldt — personal card

Live at **https://kstapelfeldt.github.io/**

A one-page site: `index.html` holds everything (no build step). GitHub Pages publishes the `main` branch automatically on every push.

## Editing

Open `index.html` in any text editor. Each link is one `<li>` block in the list; copy a block to add a link, delete one to remove it. Then commit and push; the site updates within a minute or two.

The email address is assembled by a small script at the bottom of the page so scraping bots can't read it from the source. To change it, edit the `data-user` and `data-domain` values on the Email row, not the visible text.

When the page changes, update the `<lastmod>` date in `sitemap.xml`.
