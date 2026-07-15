# 8 Color Palette Builder

A self-contained browser app for creating an 8 color palette, extracting a palette from an uploaded image or image URL, and exporting the palette as a `.hex` file.

## Open Locally

Open `index.html` directly in a browser.

## Publish With GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `README.md`, and `.nojekyll` from this folder to the repository root.
3. In the repository, go to `Settings` -> `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Set the branch to `main` and folder to `/root`, then save.
6. GitHub will publish the site at a URL like:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/
```

## Notes

Image uploads work fully offline in the browser. Image URLs depend on the remote host allowing browser canvas access; if a linked image blocks extraction, download it and use the upload option.
