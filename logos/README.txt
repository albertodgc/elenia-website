Customer logos for the hero carousel
=====================================

How to add a customer logo:

1. Get written consent from the customer to feature their logo
   on the Elenia marketing site. (Email or WhatsApp is fine —
   archive it.)

2. Export their logo as an SVG. Monochrome white-on-transparent
   is ideal — the CSS will render it at 28px tall against the
   green hero gradient. If you only have a colored logo, the
   CSS rule `.logo-item img { filter: brightness(0) invert(1) }`
   will force it to white.

3. Save the file here as `cliente-<N>.svg` (matching one of the
   8 slots already wired into index.html), or use a descriptive
   slug like `glamour-nails.svg` and update the corresponding
   <img src> + alt + fallback text in index.html.

4. The carousel slots are duplicated for a seamless loop —
   update BOTH Set A and Set B entries in the .logos-track so
   the scroll stays in sync.

5. If a file is missing, the slot gracefully falls back to the
   text label (e.g. "Cliente 1"), so nothing breaks during the
   rollout as you collect consent.
