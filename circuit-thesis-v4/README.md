# The Circuit Thesis — deck (v2)

Self-contained HTML pitch deck. No build step, no dependencies, no internet
needed — everything (styles, scripts, fonts fallbacks) lives in `index.html`,
and all images sit next to it.

## View it

Double-click `index.html` (opens in any browser), or serve the folder:

    python3 -m http.server 8091
    # then open http://localhost:8091/

Navigation: ← / → arrows or swipe · **A** shows all slides stacked · **F**
fullscreen. Append `?all` to the URL for the stacked view. Print from the
stacked view for a PDF (colors are preserved).

## Edit it

- All slide content is plain HTML in `index.html` — each slide is one
  `<section class="slide">` block, in order, clearly commented
  (`<!-- 3 · THE FLOOD -->` etc.). Edit text directly.
- Colors/typography are CSS custom properties at the top of the `<style>`
  block (dark + light themes).
- Diagrams are inline SVG inside each slide — edit them in place.
- `deck.md` is a faithful markdown transcription of every slide (content,
  figure descriptions, plus notes on the deck's language rules) — read it
  first if you're editing copy, or hand it to an AI agent as context.

## Files

- `index.html` — the deck (15 slides)
- `deck.md` — full content transcription + editing notes
- `*.jpg` / `*.png` — photos, screenshots, logos referenced by the slides
