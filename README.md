# cbn-assets

Static images and web fonts for **ไทยติดชา / thaitidcha** (by CNB — China 'N Beyond),
served through [jsDelivr](https://www.jsdelivr.com/) so the app's own hosting does not
pay the bandwidth for them.

```
https://cdn.jsdelivr.net/gh/Jamamaboy/cbn-assets@v1/<path>
```

Always reference a **tag** (`@v1`), never `@main` — tagged URLs are cached as immutable.
Bump the tag whenever a file changes, then update `NEXT_PUBLIC_ASSET_BASE` in the app.

| path | what |
|---|---|
| `bg_home.webp` | home / intro background (960w) |
| `bg_card.webp` | result + share-card background (720w) |
| `ui-atlas.webp` | UI sprite sheet, 2360×400 — **do not resize**, coordinates are hardcoded |
| `cnb_logo.webp` | logo drawn into the share card |
| `tea/*.webp` | 16 character illustrations, 700w — used by the canvas share card |
| `tea/sm/*.webp` | same 16 at 400w — used on screen |
| `fonts/mali-*.woff2` | Mali, weights 300–700, subset to 240 glyphs |

Artwork by the ไทยติดชา team. Published here for CDN delivery only.
