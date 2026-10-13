# 3D Flip Cards

Click-to-flip product cards built with plain HTML and CSS. Each card shows a product image and name on the front, and a spec sheet on the back. Built for product advertisements.

## Preview

Open `index.html` in a browser. Hover over a card to flip it.

## Files

- `index.html`: the cards and their content
- `style.css`: layout, 3D flip, and styling
- `images/`: product photos

## Adding a product card

Copy one `<div class="card-container">` block in `index.html` and change:

1. The `<img>` `src` and `alt` text
2. The front title and tagline (`.card-title`)
3. The back title and spec list (`.specs-list`)

## Customizing

- Card size: `.card-container` in `style.css` (default 320 × 450px)
- Colors: the `#f4f1ea` paper background, `#1e1e1e` card dark, and `#d4af37` gold accent
- Photo look: the `filter` on each `<img>`, or on `.card-front img` for all cards

Fonts (Playfair Display and Roboto) load from Google Fonts, so an internet connection is needed for them to display as designed.
