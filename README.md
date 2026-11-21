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
| 5 West Jerusalem | west-jerusalem-synagogue.jpg |
| 6 Bethlehem | bethlehem.jpg |
| 7 Rachel's Tomb and the wall | rachels-tomb-wall.jpg |
| 8 Hebron | hebron.jpg |
| 9 Down the Kidron to the Dead Sea | judean-wilderness.jpg |
| 10 Masada | masada-synagogue.jpg |
| 11 The Golan Heights | golan.jpg |
| 12 Capernaum | capernaum-shell.jpg |
| 13 Caesarea Maritima | caesarea.jpg |
| 14 Mount Nebo | mount-nebo.jpg |
| 15 Rabbah (Amman Citadel) | amman-umayyad.jpg |
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

## Citations and the bibliography

1. Add each source once to the BIBLIOGRAPHY block in `index.html` (search for "BIBLIOGRAPHY: ADD EACH SOURCE"). Give it a key such as `Magness 2019`, its type (`ancient` or `modern`) and the full Harvard reference.
2. In a note, cite it as `[[Magness 2019, p. 112]]`. Two sources: `[[Magness 2019, p. 112; Netzer 2006, p. 18]]`.
3. The site shows the citation as a link to the entry. A citation whose key has no entry shows in red with "[not in bibliography]". Fix those before you submit.
4. Bible and Josephus references on the texts line count as citations of the JPS, NRSV and Loeb entries automatically. Archive photographs are added to the bibliography automatically.
5. Set `ACCESSED` at the top of the block to the date you last checked the online sources.

## Sectioned entries (Jakub's layout)

A pin with an `intro` field shows four sections. Pins without it still show the old `note`.

```
intro:    "One sentence.",
josephus: "What Josephus says, with [[Josephus 1930 | Josephus, Ant. 4.161]].",
images:   "A sentence or two on your photo and the archive photo.",
further: {
  ancient: [ { key: "Strabo 1930", head: "Strabo (dates), Greek geographer, Geography (Geogr.) 16.4.21", desc: "what the reader finds." } ],
  modern:  [ { key: "Tholbecq 2025", head: "Tholbecq (2025)", desc: "what the reader finds." } ]
},
```

`key` must match a BIBLIO entry. `head` becomes the link text.
Loeb Josephus volumes: 1930 = Ant. 1-4 (LCL 242); 1943 = Ant. 12-14 (LCL 365); 1963 = Ant. 15-17 (LCL 410); 1928 = J.W. 5-7 (LCL 210).
Others you may need: Ant. 5-8 (LCL 281, 1934), J.W. 1-2 (LCL 203, 1927), J.W. 3-4 (LCL 487, 1927), Life (LCL 186, 1926). Check the year on the title page.
