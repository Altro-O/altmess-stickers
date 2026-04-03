# altmess-stickers

Static sticker packs for Altmess.

## CDN URLs

- jsDelivr manifest: `https://cdn.jsdelivr.net/gh/Altro-O/altmess-stickers@main/manifest.json`
- GitHub Pages manifest: `https://altro-o.github.io/altmess-stickers/manifest.json`

## Structure

```text
altmess-stickers/
  manifest.json
  .nojekyll
  catz/
  flork/
  kawaii/
  meownicorn/
  retro/
```

`manifest.json` contains a repo-level `baseUrl` and relative file paths. The messenger resolves sticker file URLs from it.

## GitHub Pages

1. Open repository `Settings`.
2. Open `Pages`.
3. Set `Source` to `Deploy from a branch`.
4. Select branch `main` and folder `/ (root)`.
5. Save and wait until GitHub publishes the site.

After that, static files will be available from `https://altro-o.github.io/altmess-stickers/`.

## jsDelivr

No extra setup is required. After files are pushed to GitHub, jsDelivr serves them from:

`https://cdn.jsdelivr.net/gh/Altro-O/altmess-stickers@main/`

Useful cache refresh URL after updates:

`https://purge.jsdelivr.net/gh/Altro-O/altmess-stickers@main/manifest.json`
