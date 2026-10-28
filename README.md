# trail-finder-winter2

Last winter's Sentinel-2 photos for the 3D map's Winter view in [Trail Finder](https://allduf.github.io/trail-finder/), for the places that didn't fit on the first Winter photo site ([trail-finder-winter](https://github.com/allduf/trail-finder-winter)).

- `blocks.json`: the zoom-11 squares this site has photos for.
- `{z}/{x}/{y}.webp`: the tiles, zooms 6 to 14.

They're built by `scripts/winter-photos` in allduf/trail-finder (`scenes.py`, `build.py`, then `tiles.py`) and published by `.github/workflows/publish.yml`.

Imagery: Copernicus Sentinel-2 data (2026), processed by Trail Finder.
