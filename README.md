# fs25_newMod

## editable/

Editable version of the MRS by Trebor badge.

- `mrs_badge_editable.svg` - layered SVG (base art, MRS text, ribbon text, OIHL logo,
  your-logo placeholder). Opens in Inkscape / Illustrator / Figma; every layer is a
  separate movable group.
- `index.html` - browser drag-and-drop editor for the SVG (drag layers, mouse-wheel to
  resize, edit text, swap logos, export self-contained SVG or PNG). Serve the folder
  and open it, e.g. `python3 -m http.server 8000` inside `editable/`.
- `assets/badge_base_clean.png` - badge art with the text removed (generated).
- `assets/badge_base_original.png` - original art with baked-in text.
- `assets/oihl_logo.png` - Ontario Intercounty Handgun League logo, sourced from
  classifieds.oihl.ca (archived copy of OIHL-logo-no-type-250x84.png).
