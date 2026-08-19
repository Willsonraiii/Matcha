# Matcha Station

A single-page shopfront for ceremonial-grade matcha drinks, brewed in Kathmandu.

Vanilla HTML, CSS, and JavaScript. No build step.

## Run it

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## What’s here

- Six flavors with local cup and fruit art (no third-party CDN)
- Desktop arc picker, mobile arrows, swipe, and keyboard left/right
- Cart saved in `localStorage`
- Pickup reservation form (pay in store — nothing is charged online)
- Menu, location (Thamel), and share / follow actions
- Accessible dialogs: Escape, focus return, backdrop click

## Project layout

```
index.html
assets/favicon.svg
assets/mountains.svg
assets/cups/*.jpg
assets/fruit/*
```
