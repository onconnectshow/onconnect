# OnConnect ()

Website for **OnConnect ()**, a group show at The Living Gallery, 1094 Broadway, Brooklyn, New York.
October 18–23, 2026.

## Files

- `index.html` — the whole site (home, Artworks, Artists, About)
- `poster.jpg` — the poster shown on the About page

## Editing

Most text lives directly in `index.html`:

- **Artist bios:** search for `class="a-bio"`
- **Artworks** (titles, materials, descriptions, Instagram, floor-map positions): search for `var WORKS =`
- **About text, gallery info and press:** search for `id="page-about"`
- **Home page dates, venue and reception:** search for `<!-- Dates -->`

To add photos for an artwork, upload the image to this repository, then add an `images` list to that artwork in `WORKS`, e.g.

```js
"images": [{ "src": "vape-thurible.jpg", "caption": "Installation view" }]
```
