# Suya English Game

A simple HTML speaking game for kids.

## Files

- `index.html`: homepage for GitHub Pages
- `game.html`: same game page kept as the original working file
- `images/README.md`: image filename guide

## Publish to GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html` and any image assets you want to use.
3. Open repository `Settings` -> `Pages`.
4. Under `Build and deployment`:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Save and wait for deployment.

Your site URL will usually be:

`https://<your-github-username>.github.io/<repository-name>/`

## Notes

- For custom content, update `APP_CONFIG` near the top of `index.html`.
- Put your own images into the `images/` folder and keep the filenames matched with `images/README.md`.
- Recording features work best over `https`, which GitHub Pages provides.
- Progress is stored in the browser with IndexedDB and falls back to localStorage.
