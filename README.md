# Logo Remover Studio

Browser-based video logo-area remover for videos you own or have permission to edit.

- Load a local video in your browser.
- Draw a rectangle around a fixed logo.
- Process with FFmpeg's `delogo` filter.
- Preview and download the processed MP4.
- Video files stay in the browser and are not uploaded to this website.

This is not AI reconstruction. Results vary with the background, movement and logo size. Perfect removal or original encoding quality cannot be guaranteed. Start with a short MP4.

## Run locally
Run `npm install`, then `npm run dev`.

## Deploy
The GitHub Actions workflow builds and deploys to GitHub Pages on pushes to `main`. In repository Settings → Pages, choose GitHub Actions as the source if needed.
