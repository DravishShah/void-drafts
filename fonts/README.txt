Drop your Montech v02 font files here, named:

  Montech-v02.woff2   (preferred — smallest, best browser support)
  Montech-v02.woff    (fallback)
  Montech-v02.otf     (fallback)

index.html already references these paths via @font-face, so once
the files are here the whole page will pick up the real font
automatically — no code changes needed.

Only have a .ttf? Rename the src line in index.html's @font-face
to point at it, or convert to woff2 (smaller, faster) using any
free online converter.
