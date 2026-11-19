# 1 park, 4 futures

An interactive map of four speculative futures for Victoria Park, London: Anthropocentric, Fourth-Nature, Restoration and Forager. Made for the Design Methods module (M5012) at the London Interdisciplinary School.

It's a static site: `index.html` holds all the code and text, `base.png` is the map outline, and the `nature-*.svg` files are the card illustrations. There's no build step.

## Run it locally

Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Deploy

Vercel builds this repo on every push to `main`. In Vercel, import the repo with framework preset **Other** and leave the build and output settings empty.
