# The Open Plate website

Static HTML and CSS. No build step. Open `index.html` or host the folder anywhere.

## Replace images
Every image slot shows a gradient block with its filename (for example `images/hero-pastry-spread.jpg`).
Put your photo in the `images/` folder with that exact filename and the placeholder is replaced automatically. Use JPG or WebP at about 1200px wide.

## Edit contact details
Search all `.html` files for `hello@theopenplate.in` and change it (header-free: it appears in each footer and in `contact.html`).
The location text "Dombivali, Mumbai, Maharashtra" is in each footer and on `contact.html`.

## Menu
The menu comes from MENU.xlsx. Each category card uses `images/menu-<category>.jpg` (for example `menu-cookies.jpg`, `menu-tarts-and-pies.jpg`). To change items, edit the lists in `menu.html`.

## Colours
Edit the `:root` variables at the top of `assets.css`.

## Hosting
GitHub Pages: Settings > Pages > deploy from the `main` branch, root folder.
