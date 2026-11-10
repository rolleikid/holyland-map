# Then and Now: Exploring the Ancient "Holy Land" and its People

An interactive map pairing Library of Congress archive photographs (1898 to 1946) with my own photographs of the same places.

## Put it on GitHub Pages (about 10 minutes)

1. Sign in at github.com. Click **New repository**. Name it `holyland-map`. Set it to **Public**. Click **Create repository**.
2. On the new repository page, click **uploading an existing file**.
3. Unzip this folder on your computer. Drag everything *inside* `holyland-map` (index.html, images, README.md) into the upload box. Click **Commit changes**.
4. Go to **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**. Click **Save**.
5. Wait a minute. Your site appears at `https://YOUR-USERNAME.github.io/holyland-map/`.

To test on your own computer first, open `index.html` in a browser.

## Add your photographs

1. Download your photos from Google Photos (open a photo, press Shift+D, or use the three-dot menu > Download).
2. Resize each to about 1600 pixels wide. Phone photos at full size make the site slow.
3. Rename each one to match the place, for example `western-wall.jpg`, and save it in `images/mine/`.
4. Edit the caption for each place in `index.html`, in the block marked PLACES: EDIT YOUR CONTENT HERE.

| Pin | Main photo in images/mine/ |
|---|---|
| 1 The Western Wall | western-wall.jpg |
| 2 Prayer on the Mount of Olives | mount-of-olives-prayer.jpg |
| 3 The Kidron Valley | kidron-valley.jpg |
| 4 The Golden Gate | golden-gate.jpg |
| 5 West Jerusalem | west-jerusalem.jpg |
| 6 Bethlehem | bethlehem.jpg |
| 7 Rachel's Tomb and the wall | rachels-tomb-wall.jpg |
| 8 Hebron | hebron.jpg |
| 9 Down the Kidron to the Dead Sea | judean-wilderness.jpg |
| 10 Masada | masada-synagogue.jpg |
| 11 The Golan Heights | golan.jpg |
| 12 Capernaum | capernaum-shell.jpg |
| 13 Caesarea Maritima | caesarea.jpg |
| 14 Mount Nebo | mount-nebo.jpg |
| 15 Rabbah (Amman Citadel) | amman-citadel.jpg |
| 16 Petra | petra.jpg |
| 17 Wadi Rum | wadi-rum.jpg |

Extra photos for a place go in the `more` list for that place. They appear as a small gallery under the main pair.

## Archive photographs

Each archive photo loads from the Library of Congress by its number. For a site that never breaks, download each image from its Library of Congress page and save it in `images/archive/` as `matpc-NUMBER.jpg`, for example `matpc-00027.jpg`.

Every place now has an archive photo. Check each title and date against its record before you submit. Click the pin, follow the search link, pick a photo and copy its number into the PLACES block in `index.html`.

### Before you submit: check each record

Open each Library of Congress record and confirm:
- the exact title (several entries say "check exact title")
- the date
- the creator (American Colony Photo Department or Matson Photo Service)
- the Rights Advisory line says "No known restrictions on publication"
- it is not a colour lantern slide (these carry donor restrictions)

Credit line required by the Library: Library of Congress, Prints & Photographs Division, [reproduction number].

## Credits

Map: Leaflet (BSD licence, included inside index.html). Base maps by Esri, no API key needed.
