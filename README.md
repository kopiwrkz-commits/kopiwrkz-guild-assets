# KOPIWRKZ Guild Assets

Assets for the KOPIWRKZ Guild Library portfolio at kopiwrkz.com/portfolio. The site loads everything here through the jsDelivr CDN, pinned to a release tag:

`https://cdn.jsdelivr.net/gh/kopiwrkz-commits/kopiwrkz-guild-assets@v1.0.0/`

| Folder | What it holds |
| --- | --- |
| `lib/` | `kwz-libs.js`: three.js r160 (bundled from its ES module build, no deprecated scripts) plus every add-on library the page uses |
| `brand/` | KOPIWRKZ Guild logo: badge, mark and favicons (SVG + PNG) |
| `img/` | Guild Master art and book covers |
| `models/` | Compressed glTF props (meshopt + WebP textures) |
| `textures/` | Stone, marble and wood texture sets, HDRI lighting |
| `sfx/` | Door, page, fire and ambience sounds |
| `manifest.json` | What the site loads and where each prop is placed |

## Updating

Change files, update `manifest.json`, commit, then create a new tag (for example `v1.0.1`) and point the `ASSET_BASE` link in the GHL code at that tag. A tag never changes once published, so visitors always get a matching set.

## Credits and licenses

Code bundled in `lib/kwz-libs.js`:

- [pmndrs/postprocessing](https://github.com/pmndrs/postprocessing): Zlib
- [N8python/n8ao](https://github.com/N8python/n8ao): CC0
- [protectwise/troika](https://github.com/protectwise/troika) (troika-three-text): MIT
- [gkjohnson/three-mesh-bvh](https://github.com/gkjohnson/three-mesh-bvh): MIT
- [theatre-js/theatre](https://github.com/theatre-js/theatre) (@theatre/core): Apache-2.0
- [mrdoob/three.js](https://github.com/mrdoob/three.js) addons (GLTFLoader, RGBELoader, Reflector, meshopt decoder): MIT

Also bundled: three.js r160 core (MIT). Loaded separately: [howler.js](https://github.com/goldfire/howler.js) (MIT) from cdnjs. Font: Cinzel (SIL Open Font License).

Third-party models, textures and sounds added to `models/`, `textures/` and `sfx/` are CC0 (Poly Haven, Quaternius, Kenney, Freesound CC0 filter); each folder's README lists the source of every file.
