# White Paper Page Maintenance

Public URL: https://atce-alliance.github.io/white-paper/

This directory contains a static website. No dependency installation or build command is required. GitHub Pages publishes from the root of the `main` branch. Committing changes to that branch triggers deployment automatically.

## Files

- `index.html`: White paper introduction, reading and download links, chapter contents, and editorial team.
- `style.css`: Page styling and responsive layouts.
- `assets/AI短剧版权治理白皮书V1.0.pdf`: The white paper PDF. Its document title matches its filename; page contents are unchanged.
- `assets/cover.png`: An image rendered from the first page of the PDF.

## Updating the White Paper

1. Replace `assets/AI短剧版权治理白皮书V1.0.pdf` with the updated document.
2. Update the document date, page count, file size, chapter titles, and chapter page numbers in `index.html`. If the filename changes, update every PDF link as well.
3. If the cover changes, regenerate `assets/cover.png` from the first page of the updated PDF.
4. Commit the changes and wait for GitHub Pages deployment to finish. Check the reading, download, and chapter links on desktop and mobile browsers.

The browser provides the PDF viewer. The `#page=N` fragment may not work in some mobile or WeChat browsers; the page includes a note explaining this limitation.

This implementation adds only the `/white-paper/` page. The alliance homepage is outside its scope.
