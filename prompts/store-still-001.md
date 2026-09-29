# dogstar.fun store still — batch 001

**What it's for:** the background picture for the liquidation merch page, made the way zadonsky00 made X-TREME GEAR: the whole website is one GPT Image still. His After Effects step is replaced by three.js. Three boxes are left empty, and live spinning GLBs get laid over them:

| Box | Where | Product that goes in it |
|---|---|---|
| **A** | left column, top tile | Heat Death Cocoa (`props/heat_death_cocoa.glb`) |
| **B** | centre FEATURE PRESENTATION room | Dog Star Kibble (`props/dog_star_kibble.glb`) |
| **C** | right column, top tile | Cold Sun Lozenges (`props/cold_sun_lozenge.glb`) |

**Model:** GPT Image 2.5, 1024×1024, **high quality**, because the page is dense with small text.
**Palette rule:** the page uses the web-safe colours; the products stay teal and persimmon. The 3D brings the teal, so the still doesn't need any.
**Reference:** `prompts/ref_xtreme_gear.png` is a clean frame of his site, cropped from `/mnt/DreamVault/zadonsky00_DcyIJjHRFdg.mp4`. Only S04 uses it.

**Batch (8 images), in scroll order:**
1. S01 × 4: the master prompt
2. S02 × 2: master, with a starfield in the feature room instead of sky
3. S03 × 1: master, plus Windows XP scareware popups baked into the picture
4. S04 × 1: master, with the reference frame attached as Image 1

Pick on gut feel. After you pick, I measure boxes A, B and C on your pick and line the 3D up with them.

---

## S01 — master

```
[OUTPUT FORMAT]
A flat 1:1 square screen capture of a Windows XP era web page, grabbed at 1024x768 on a CRT monitor and saved as a medium-quality JPEG circa 2002. Table-based HTML layout with 1-pixel table borders in mismatched colours. Pixel-crisp edges, aliased unsmoothed type, banded gradients, faint JPEG blocking. The web page fills the whole frame edge to edge, seen straight on.

[USE]
This is a background plate for a live web page. Three display boxes, A, B and C, are left empty on purpose: spinning 3D products get composited into them afterwards. Every other part of the page is fully dressed and crammed.

[THE SITE]
DOGSTAR.FUN, a 2002 online merch store for a dog-themed memecoin called $HEART, in total liquidation. Maximalist Y2K e-commerce, dense as a flea-market flyer.

[LAYOUT, TOP TO BOTTOM]
Page frame: a thick royal-blue border scattered with small yellow five-point stars, running round the whole page.

Row 1, three badges side by side:
- Left: "ALL STORES NOW IN LIQUIDATION" in bold red Impact on white, with a red outline box.
- Centre: "KIBBLE Y CACAO" in yellow block capitals on royal blue.
- Right: "FREE $HEART!!!" in lime green bubble letters on a magenta-and-blue checkerboard, next to a white email envelope icon.

Row 2, the logo bar on yellow: huge italic chrome-and-red flaming letters reading "DOGSTAR.FUN", with orange clip-art flames on both sides. At the right end of the bar is a purple box reading "APE IN NOW — SAVE 99%", with a red starburst sticker reading "NEW!".

Row 3, the nav bar: white bold capitals on royal blue, separated by vertical bars: "ABOUT | DROPS | KIBBLE | COCOA | LOZENGES | CHART | GUESTBOOK".

Row 4, the main area, in three columns:
- LEFT COLUMN, under a red header tab reading "EQUIP":
  - Display box A: a square tile with a thick bevelled frame. Its inside is one flat lime-green colour field, clean and empty. Below it is a caption strip: "HEAT DEATH COCOA".
  - A second tile, royal blue, holding a small photo of a red beanie hat with a heart logo. Caption: "$HEART BEANIE".
  - A grid of six small web-ring buttons, each a different colour, each with a tiny icon: "BARK ZONE RING", "SIRIUS WEBRING", "APE IN RING", "MEGA TREATS", "DOG STAR NET", "HEART LINKS".
  - A black hit counter with red LED digits: "00143394".
  - A black-and-yellow hazard-striped panel with a tiny construction-worker icon: "UNDER CONSTRUCTION".
  - Small grey serif text: "Best viewed in Netscape Navigator at 800x600".
- CENTRE COLUMN, under a red header bar reading "FEATURE PRESENTATION":
  - Display box B: a deep one-point-perspective room seen from its open front, like a stage set. Left wall cyan, right wall dark green, ceiling orange, floor hot magenta. The back wall is a blue sky with soft white clouds over a green hill. The room is empty apart from a small white spotlight pool in the centre of the floor.
  - Under the room is a grey Windows scrollbar, then a lime-green marquee strip repeating "$HEART*$HEART*$HEART*$HEART*" in red.
  - Under that, a caption: "DOG STAR KIBBLE — BRIGHTEST IN THE SKY".
- RIGHT COLUMN:
  - Display box C: a square tile with a thick bevelled frame. Its inside is one flat cyan colour field, clean and empty. Below it is a caption strip: "COLD SUN LOZENGES".
  - A second tile, hot green, holding a small photo of an orange basketball. Caption: "I KNOW BALL".
  - A big chrome button reading "ENTER" in red bevelled letters on a black starfield.
  - An email signup box: "e-mail address:" with a white text field and a grey "OK" button.
  - A purple box with yellow text: "SAVE 30% LIMITED TIME".
  - A red box with white text: "ALL STOCK MUST GO".
  - A blue box with a pen icon: "SIGN MY GUESTBOOK".

Row 5, the footer banner on yellow: huge black italic condensed capitals reading "EVERYTHING MUST GO", then a giant red price "39.99" with the "99" in superscript, then a red starburst sticker with white text "SAVE $30".

Row 6, fine print on white: "© 2002 DOGSTAR.FUN, INC. All rights reserved. $HEART is not a currency. Prices change without notice." Below it, blue underlined links: "Privacy Policy | Site Map | Webmaster | RSS Feeds".

[PALETTE]
Full saturated web-safe set: pure red #FF0000, royal blue #0000FF, magenta #FF00FF, yellow #FFFF00, lime #00FF00, cyan #00FFFF, orange #FF6600, purple #9900FF, plus black and white. Every cell has a different colour from its neighbours. Flat fills, clashing on purpose.

[TYPE]
Impact, Arial Black, Tahoma, Courier and Times New Roman: the stock fonts of a 2002 PC, all aliased. Render every quoted string exactly as written, letter for letter; the quoted strings are the complete text of the page.

[DISPLAY BOXES]
Boxes A and C hold only their flat interior colour. Box B holds only the room's coloured walls, floor, sky and spotlight pool. These three boxes are the calm spots in an otherwise crammed page.
```

---

## S02 — starfield room

The same as S01, except that in the `Display box B` line you replace the sentence starting "The back wall is a blue sky…" with:

```
The back wall is a deep black night sky full of stars, with one star far brighter than the rest, blue-white, with four long diffraction spikes: Sirius, the Dog Star.
```

---

## S03 — scareware baked in

The same as S01, with this block added right after `[DISPLAY BOXES]`:

```
[POPUPS]
Three Windows XP error dialog boxes overlap the page edges: one across the top-right badge, one across the left column's web-ring grid, one across the footer's right end. Each has the blue XP title bar, a yellow warning triangle icon and a grey "OK" button. Titles and messages, in order: "Security Alert" / "Your $HEART is at risk!", "System Warning" / "347 viruses detected", "McAfee Heart Scan" / "APE IN NOW to protect your wallet". The popups stay clear of display boxes A, B and C.
```

---

## S04 — with the reference frame

Attach `prompts/ref_xtreme_gear.png` as Image 1. Put this line first, then paste the whole of S01:

```
Image 1 is a layout and density reference only: match its grid rhythm, border weight, crammed density and colour clash. Every word, product, logo and name comes from the prompt below.
```
