# Captain: Japan Adventures v0.4.4

Code update after reintegrating final backgrounds.

What changed:
- index.html now loads style.css?v=044 and game.js?v=044
- game.js adds ASSET_V for asset cache busting
- background, character, and item image URLs now append ?v=044

Purpose:
- force browsers and GitHub Pages clients to fetch the new final background images instead of cached older versions.
