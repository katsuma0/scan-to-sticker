# scan to sticker

I photographed 45 pages of an old insect book and wanted stickers out of them without cutting the book. This takes the photos, straightens each page, finds the whole pictures, the body text and the blank paper, and lays them out in rows like a sheet of stamps. Every stamp is its own sticker, cut straight, with a paper margin round the picture.

Open `index.html` in a browser and drop the photos on it. Nothing uploads anywhere.

Each sheet uses one palette: green beige black brown, or black and white. The picture gets mapped onto those colours dark to light, with a halftone screen between them, so two colours can still show shading. Some stamps use three of the four colours so the sheet doesn't look like one filter.

A stamp is about 3 cm tall, mostly portrait with some square and landscape ones, and each row is stretched to the sheet width. Every stamp is a picture. Its width follows the picture's shape so the whole thing fits, photos cropped just inside their own edges and drawings framed with a bit of page, sometimes with the caption. No text-only stamps. Gutters are 3 mm, enough for a cutter. Click a stamp to swap its picture.

The picture finder gets most of them, misses some small drawings, and now and then boxes something that makes no sense, like the shadow under the book. Check pictures opens each page with its boxes: click a box to drop it, drag to draw one. Sheets only use what's boxed, and the boxes are remembered in that browser. Same seed gives the same sheet.

The default sheet is 14 by 21 cm at 300 dpi. Sticker PNG has a transparent background. Cut lines PNG is the stamp outlines alone, for a cutter that wants its own layer.

The scans I had were 360 by 640, which is too small. Small type turns to dots. Full size phone photos, around 3000 px, should fix that. Pages shot at an angle get rotated straight, but keystone from tilting the phone stays, so shoot from directly above.

`window.__debugMaps()` in the console returns an image of the page analysis: red desk, blue figure, green text, yellow boxes around whole figures.
