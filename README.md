# ÉLAN Atelier

A luxury fashion website for ÉLAN Atelier: a scroll-driven film hero, plus New In, Ready to Wear, Collections, Our Story, Journal and product pages with a working bag.

## Run locally
The film frames load from relative paths, so serve the folder rather than opening the file directly:

```
python3 -m http.server 8000
```
Then open http://localhost:8000.

## Structure
- `index.html`: the whole site (markup, styles and script)
- `frames/s1` to `frames/s5`: 80 WebP frames per scene for the scroll film
- `p/`: product, editorial and journal photography

## Deploy
Enable GitHub Pages on the `main` branch (root folder) and the site works as is.
