Écorché Atlas — self-hosting

Upload this whole folder to any static web host (GitHub Pages, Netlify, Cloudflare Pages, or your
own server) and open index.html from its web address. Opening index.html straight from your disk
will not work, because browsers block pages from loading their data files that way; use
Ecorche-Atlas-offline.html for that instead.

index.html loads three.js and fonts from public CDNs (jsdelivr, Google Fonts). Everything else is
in this folder.
