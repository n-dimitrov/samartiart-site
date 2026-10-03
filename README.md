# samartiart-site

The company page for Samarti Art at https://samartiart.com, served by GitHub Pages from `main`.

One static file, no build step. Fonts are self-hosted in `fonts/` (Source Serif 4, IBM Plex Mono; both SIL Open Font License) so the page makes no third-party requests.

## Preview

    python3 -m http.server 8090

## Deploy

Push to `main`. Pages settings: branch `main`, root folder, custom domain `samartiart.com` (the `CNAME` file), Enforce HTTPS.

DNS for the apex: four `A` records to GitHub Pages (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) and `www` as a CNAME to `<owner>.github.io`.
