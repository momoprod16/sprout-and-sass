# Sprout &amp; Sass — Website

Static storefront for the **Sprout &amp; Sass** print-on-demand business. Showcases the
plant-pun apparel collection and directs visitors to the [Etsy shop](https://www.etsy.com/shop/SproutAndSass)
for purchase. Also hosts the brand's Privacy Policy (required for the Pinterest developer app).

## Structure

```
index.html        Home (hero, features, featured products, contact CTA)
shop.html         Full collection (10 designs, links to Etsy)
about.html        Brand story
privacy.html      Privacy Policy  ← URL used for the Pinterest app
assets/styles.css Shared styles (botanical/cottagecore theme)
assets/designs/   Product design images
```

## Hosting

Deployed as a static site via **GitHub Pages**. No build step — plain HTML/CSS/JS.

To run locally, open `index.html` in a browser, or serve the folder:

```sh
python -m http.server 8080   # then visit http://localhost:8080
```

## Custom domain (planned)

Domain registered at Namecheap, DNS via Cloudflare, attached to the Pages site. Add a
`CNAME` file with the apex domain and configure the registrar/Cloudflare DNS records.
