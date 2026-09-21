# Vinyl Store — a Korean Hip Hop (KHH) Collage

## Overview

This is a three-page web collage exploring Korean hip hop (KHH) culture, framed as a visit to a vinyl record store:

1. **Storefront (`index.html`)** — a red Parisian storefront photo with hand-picked KHH stickers, flyers, and graffiti pasted on top, topped with a giant stretched title.
2. **Display Wall (`page2.html`)** — a 3×4 grid of KHH album covers redesigned as vinyl sleeves, laid over a photo of a store interior. Each sleeve flips on hover/tap to reveal the track and artist credits.
3. **2000s (`page3.html`)** — a close-up photo of a classic click-wheel MP3 player. Its screen holds four clickable album covers that each play a 20-second audio clip, and the body is covered in personal KHH-fan stickers with a subtle sway animation.

## Tech

Built with plain HTML, CSS (Grid, absolute positioning, `clip-path`, CSS animations, 3D flip transforms), and a small amount of vanilla JavaScript for the flip-card and audio-player interactions. Fonts are Abril Fatface (headlines) and Space Mono (UI text) from Google Fonts. No frameworks or build tools — the site is fully static and hosted on GitHub Pages.

## AI tool usage

I designed the whole concept myself — the vinyl-store narrative, the three-page structure, the visual direction for each page, and I sourced/edited/recorded all of the images and audio. I used Claude (Anthropic) as my coding partner to implement that vision in HTML/CSS/JS: I described what I wanted (layouts, interactions, specific effects) and gave feedback on drafts, and Claude wrote and revised the code accordingly. I did not write the CSS/JS myself from scratch.

Examples of how I directed the build:
- Described the overall concept ("a vinyl store you walk into, then a display wall, then an MP3 player") and worked through feasibility and layout ideas before any code was written.
- Supplied my own photos, found images (with source links), and redesigned album art, and asked for specific effects: a sticker-collage look on page 1, a 3×4 flip-card grid on page 2, and a close-up product shot with a clickable audio screen on page 3.
- Asked for audio to be extracted and trimmed from my screen-recorded videos (using ffmpeg) for the audio-player page.
- Gave iterative visual feedback across many rounds — e.g. "the background isn't filling the page," "these images are being cropped too aggressively," "make the star-shaped crop keep the face visible," "give the stickers a subtle sway animation" — until the pages matched what I had in mind.

## Credits

Full image and audio credits (with source links) are listed at the bottom of each page.
