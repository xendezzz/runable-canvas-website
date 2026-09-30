# Runable Canvas Website

Static HTML, CSS and JavaScript prototype. Canvas is the default page; the Chat prototype is retained at `/chat.html`.

## Run locally

```sh
python3 -m http.server 4173 --bind 127.0.0.1 --directory dist
```

Open http://127.0.0.1:4173. Publish `dist/` on any static host. No build step is required.

## Canvas experience

- Floating hero assets with cursor tilt, clouds and blur entrances.
- The same five assets move into a dotted canvas on scroll.
- Scripted Edit, Mark Edit, Text Edit, Upscale and Export walkthroughs, with persistent image/video updates.
- Eased cursor movement, contextual toolbars, animated button presses and quiet play/pause controls.
- Centered tabs, toolbar sign-up CTA, FAQs, pricing and closing CTA.
- Responsive layouts and reduced-motion support.

The editing, upscaling and export interactions are demonstrations, not live AI services. Pricing is a static snapshot. Sign-up links lead to Runable.

## Main files

- `dist/index.html` and `dist/canvas.html`: Canvas page entry points.
- `dist/canvas-hero.js` / `.css`: hero layout and interaction.
- `dist/canvas-walkthrough.js` / `.css`: asset handoff and scripted canvas demo.
- `dist/canvas.js` / `.css`: page styling and reveals.
- `dist/features-pricing.js` / `.css`: shared pricing.
- `dist/assets/`: local imagery, videos, fonts and icons.

Keep the two Canvas HTML entry points synchronized when changing markup. Shared Chat files are included so its optional page continues to work.

Design and brand assets belong to their respective owners. No additional license is granted.
