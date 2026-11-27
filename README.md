# StrungCharms

**Make 3D-printable letter beads for names, keyrings and bag charms, right in your browser.**

### ▶ [Open StrungCharms](https://strungcharms.com/)

Type a name, pick a bead shape and colours, and export a print-ready 3MF. Bambu Studio opens it as a complete project, with printer, plate type, filaments and every plate set up. Nothing to install, and nothing is uploaded: it all runs in the page.

If StrungCharms is useful to you, you can support it here:

[![Donate with PayPal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate/?hosted_button_id=PZVZSNGSJVZF8)

Or, for free: like, rate or boost my models on [MakerWorld](https://makerworld.com/en/@user_4006107580).

## How to use it

1. Type a name in the box at the top. Each letter becomes a bead.
2. Go through the tabs from left to right: spacer beads (the page opens on this one), bead shape and size, the cord you will thread them on, letter font, colours. The settings most people need are on show; the rest sit under **Advanced** in each tab.
3. Under **Printer & export**, pick your printer and slicer, then press **Export 3MF**.
4. Open the downloaded file in your slicer, load the filament colours in the slots shown under **Colours**, then slice and print.

One filament only? Choose **Engraved** under Letter and set every filament slot under Colours to 1.

## Features

- **Setup wizard:** opens when the page loads (until you press **Don't show again**) and from the **Setup wizard** button at the top. It asks five questions, one at a time: letter bead size, spacer bead size, single or double paracord, single- or double-sided letters, and horizontal or vertical. A sketch beside the questions shows the beads to scale and a cut across the cord, and changes as you pick. It starts from your current settings, and Undo brings the previous ones back.
- **One bead per letter, one cord per line.** Press Enter in the name box to start the next cord.
- **Quick sets:** beside the name box, **Common letters** fills in a stock of the most used letters (A A A A E E E L L L L I I I O O O R R R S S N N T T M M C H, 30 beads), **Spacer beads** fills in one of every spacer bead, **Every bead** fills in A to Z, 0 to 9 and one of every spacer bead, for printing a stock of beads, and **Random emoji** fills in 60 different smileys and people emoji picked at random (four cords of 15, about four build plates).
- **Bead shapes:** round, rounded square, rounded cube, hexagon, octagon and heart, with a soft bevel, rounded, flat-bevelled (chamfered) or sharp edges. By default the top and bottom edges both use the soft bevel (a 45° chamfer into the radius), so the bead is symmetric and the bottom prints cleanly without supports.
- **Letters:** inlaid flush in a second colour, engraved, or raised. Tick **Double-sided** to put the letter on the bottom face too (inlay and engraved), so the bead reads from both sides. Choose from a set of Google Fonts or use your own `.ttf` / `.otf` / `.woff` (your own font file is not kept between visits). A character the font lacks makes a blank bead and a warning.
- **Spacer beads:** hearts, bows, stars, rounded cubes, spacer pucks, barrels (`[barrel]`: the cord runs through its length; it prints standing on end), blanks and hundreds of icons. Type them in brackets: `MIA [heart]`, `[star] SAM`, `[bow]`, `[cube]`, `[star-bead]`. More shapes: flower, cloud, butterfly, gem, paw, crown, football, basketball, soccer ball, baseball, smiley, duck, round bow (sized and turned with the bow), bear, cat, bunny, ladybug, cupcake, fire, bulldog and emerald (an emerald-cut stone with a faceted, sloped top, along or across the cord) (`[flower-bead]`, `[soccer-bead]`, …); their markings print in the letter colour, as outlines, solid, or not at all. The Spacer beads tab has its own colour for newly added spacer beads, and a button to give every spacer bead that colour.
- **Emoji:** type or paste emoji into the name, or pick them from the **Emoji** tab, which lists every emoji the font draws (over 1,300) with a search box. Each becomes a bead with the emoji inlaid like a letter, in one colour, using the shape from Google's monochrome [Noto Emoji](https://fonts.google.com/noto/specimen/Noto+Emoji) font. Emoji made of several joined emoji (families, flags) show only the first one.
- **Cord holes:** sized for elastic, ball chain, leather, shoelace, paracord (single or double slot) and rope, with a pointed (teardrop) top so the hole prints without supports. The cord can run side to side (the name reads across) or top to bottom (the name hangs down).
- **Face-down printing:** optional (the **Print face down** box under **Export 3MF**, at the top and in Printer & export); flips every bead on the plate so the letter face prints on the bed, with the teardrop and bed-side edge flipped to match.
- **Edit in the preview:**
  - click a bead to change, move, duplicate or delete it
  - click a puck added by "Puck spacer between every bead" to turn all of those pucks into ordinary `[puck]` beads you can change one by one
  - every colour picker offers a grid of 32 common filament colours, plus Custom… for any other
  - give any single bead its own bead and letter colour (stored in the name as `A{#ff0000,#ffffff}`)
  - resize any single bead from 50% to 200% with its size slider (stored as `A{,,80%}`); the thickness and cord hole stay the same
  - drag an spacer bead from the picker straight onto the cord
  - drag beads to reorder them
  - with a bead selected: ← / → move it, Del or Backspace deletes it, Esc deselects
  - Ctrl+Z / Ctrl+Shift+Z (or Ctrl+Y) to undo and redo
- **Two previews:**
  - **On cord:** an isometric view of the finished strings. Use the mouse wheel or + / − to zoom, and 0 to fit the window. Drag to look around; the view eases back by itself.
  - **Build plate:** shows exactly what will be exported.
  - **Screenshot** opens a PNG of the preview to copy or download, snapped to the default view and cropped to the beads.
- **Plate layout:**
  - fills one or more plates
  - spacer beads in another colour go on their own plate
  - packs each bead at its own size, in lined-up rows, so mixed spacer beads fit tightly
  - keeps only the prime tower corner (back left) free, and keeps clear of the P1S / X1C no-print corner (front left)
  - "Fill the plate with sets" prints as many copies of the name as fit
- **Export** (under **Printer & export**):
  - **3MF for Bambu Studio / OrcaSlicer**, pre-painted or as separate parts per colour. Bambu projects are set up for the A1 mini, A1, P1S, X1 Carbon, P2S and H2S.
  - **3MF for PrusaSlicer**. Picking a Prusa printer selects it.
  - **STLs** (zip), one file per colour, for other slicers
  - after an export, a note lists the filament each slot needs and the next steps in the slicer
- **Help:** press **?** (or the ? button in the preview) for how it works and the full list of shortcuts and mouse controls. The settings tabs take ← / → / Home / End.
- **Share:** every setting is kept in the page URL. **Copy link** shares a design. Your design is also remembered in the browser, so it survives a reload.

## Selling and sharing

You may sell the beads you print with StrungCharms. Do not upload the exported files (3MF or STL) to MakerWorld or any other model-sharing site that pays or rewards uploads, and do not share or sell the files for profit.

## Running it yourself

StrungCharms is a static page: `index.html` plus `bambu-profiles.js`. Serve the folder with any web server, for example:

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

It loads three.js, manifold-3d, clipper-lib, opentype.js, JSZip and the fonts from public CDNs, so it needs an internet connection.

## Updating the Bambu Studio presets

`bambu-profiles.js` holds Bambu Studio's system presets, flattened so an exported project carries every value. Regenerate it after a Bambu Studio update:

```sh
python3 tools/build_bambu_profiles.py <BambuStudio profiles dir> bambu-profiles.js [version]
# Flatpak install:
python3 tools/build_bambu_profiles.py "$(flatpak info --show-location com.bambulab.BambuStudio)/files/share/BambuStudio/profiles" bambu-profiles.js
```

## Licence

[MIT](LICENSE).

`bambu-profiles.js` is generated from the system presets that ship with [Bambu Studio](https://github.com/bambulab/BambuStudio). Those presets are licensed under AGPL-3.0, so that file stays under AGPL-3.0.
