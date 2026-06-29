# Easy Mart — E-commerce Marketplace Homepage (Demo)

A responsive, single-page e-commerce marketplace homepage built as a
learning/portfolio project, inspired by major retail layouts like Daraz.

> **Note:** This is a demo/practice project built while learning HTML, CSS,
> and Bootstrap 5. "Easy Mart" is not a real registered business.

## Features

- Sticky navbar with search bar, cart icon with notification badge, and login link
- Multi-column "mega menu" dropdown (Electronics / Fashion / Grocery)
- Hero section with a Bootstrap Carousel + a vertical advertising sidebar
- "Flash Sale" section with a live countdown timer and discounted product cards
- "Just For You" responsive product grid
- Hover animations on product cards (lift + shadow + image zoom)
- Fully responsive using the Bootstrap 5 grid system

## Tech Stack

- HTML5
- CSS3 (custom styles, no preprocessor)
- [Bootstrap 5.3.3](https://getbootstrap.com/) (CDN)
- [Bootstrap Icons](https://icons.getbootstrap.com/) (CDN)
- Vanilla JavaScript (for the countdown timer)

## Project Structure

```
easy-mart-project/
├── index.html
├── download-images.sh      <- run this once to fetch all images locally
├── README.md
└── images/
    ├── carousel/            <- 3 hero banner images
    ├── ads/                 <- 2 sidebar ad images
    └── products/            <- 12 product card images
```

## Setup

The images are not included in this repo/folder by default — they're
downloaded on demand to keep the project lightweight and to respect
Unsplash's usage terms.

**Before opening `index.html`, run the image downloader once:**

```bash
bash download-images.sh
```

This requires `curl` (pre-installed on macOS/Linux; on Windows, use
Git Bash or WSL). It downloads all 17 images into the `images/` folder,
matching the filenames `index.html` already expects — no further
configuration needed.

After that, just open `index.html` directly in your browser.

## Deploying

This is a static site — any static host works:

- **Netlify:** drag-and-drop the whole `easy-mart-project` folder onto
  [netlify.com](https://netlify.com)'s deploy page
- **Vercel:** push the folder to a GitHub repo, then import it on
  [vercel.com](https://vercel.com)
- **GitHub Pages:** push to a repo, enable Pages in repo settings

## Credits

Product and banner photos sourced from [Unsplash](https://unsplash.com),
used under the [Unsplash License](https://unsplash.com/license).
