# Colin's Truck Sketch Archive

A scannable archive of Colin's truck coloring sketches on GitHub Pages: browse by date, filter by truck type, and download any sketch full-size.

New batches of 5 sketches are added twice a day (morning & afternoon).

## Adding sketches

1. Append lines to `~/workspace/coloring-book/sketch-archive-log.md` (`DATE | BATCH | TITLE | CATEGORY | FILE`).
2. Run `.tools/build_site.py` (copies images into `assets/`, makes thumbnails, rebuilds `index.html`).
3. Run `.tools/upload.py` to publish (GitHub Git Data API; keeps `main` and `gh-pages` in lockstep, Pages serves from `gh-pages`).
