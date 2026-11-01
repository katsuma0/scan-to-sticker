# scan to sticker

I photographed 45 pages of an old insect book and wanted stickers out of them without cutting the book. This takes the photos, finds where the pictures, the body text and the blank paper are, and cuts random pieces into stickers. Some get pressed over with one or two flat inks, like a block print on a dictionary page. Then it packs them onto a sheet.

Open `index.html` in a browser and drop the photos on it. Nothing uploads anywhere.

Six styles: overprint (text page with two ink blocks on top), page clip (a straight cut of figure, text and white space), stamp (round, one ink), cutout (ink only, cut around its own shape), text snip (torn strip of text), duotone (photo in one ink). Click a sticker on the sheet to reroll it. Same seed gives the same sheet.

Sheet PNG prints at 300 dpi on letter, half letter, 4×6 or A4. Cut PNG is the same thing with a transparent background, which is what Cricut print then cut wants.

The scans I had were 360 by 640, which is too small. Body text turns to mush and photo styles look soft. Ink styles hide it. Full size phone photos, around 3000 px, should fix most of that.

`window.__debugMaps()` in the console returns an image of the page analysis, red desk, blue figure, green text.
