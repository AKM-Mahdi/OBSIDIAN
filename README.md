# OBSIDIAN — homepage

Static one-page site (HTML + CSS + vanilla JS, no build step).

## Publish on GitHub Pages
1. Push this folder (index.html + assets/) to a repository.
2. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. The site goes live at `https://<user>.github.io/<repo>/`.

## What's interactive
- Hero slider: 3 slides, auto-plays every 6 s, arrows + tabs, progress ring.
- Drop countdown in the top bar (counts down live).
- "As featured in" logo marquee (pauses on hover).
- Lookbook: arrows rotate 6 looks through the 3 framed photos.
- Featured product slider: arrows + dots, 6 products.
- Testimonials: swipe/scroll track with arrows.
- Scroll-reveal fade-ups, image hover zoom; all motion respects "reduce motion".

## Editing
- Brand accent colour: `--accent` at the top of the `<style>` block.
- Slider content: the arrays in the `<script>` at the bottom (`copy`, `looks`, `items`).
- Images live in `assets/`. Photos are from Unsplash (Unsplash License) — swap in your own product shots before launch.
