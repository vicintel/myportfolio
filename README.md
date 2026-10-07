# myportfolio

Source for my personal site — [myportfolio-one-eta-18.vercel.app](https://myportfolio-one-eta-18.vercel.app)

I'm Victor Dickson, a full-stack engineer in Lagos. I build commerce, payments and AI
infrastructure for Nigerian businesses — mostly [Myshoplet](https://myshoplet.com), a
storefront and sales platform where I own the whole stack.

## What's on it

- **The work** — the systems I've shipped and what they actually do
- **Seven things that broke** — production incidents, what went wrong, and what I changed
  so it couldn't happen again. The most honest page on the site.
- **Also shipped** — a running log of smaller things
- **What I work in** — the stack, without the skill-bar theatre
- **Verified credential** — Google AI Professional Certificate and supplied course records
- **[CV](https://myportfolio-one-eta-18.vercel.app/cv.html)** — a printable one-pager

## How it's built

Deliberately plain: hand-written HTML and CSS with a little vanilla JavaScript. No
framework, no build step, no dependencies to rot. Two pages, some images, deployed
straight to Vercel.

```
index.html     the site
cv.html        printable CV
certificates/  verified credential images
g1.jpeg/g2.jpeg profile photos
myshoplet.png  project screenshot
og-card.png    1200×630 social preview
```

## Running it locally

There's no toolchain. Clone it and open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## License

The code is MIT. The written content, CV and images are mine — please don't republish
those as your own.
