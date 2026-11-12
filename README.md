# ActTrader Dealer Manual (with how-to videos)

This repository is the **finished website** for the ActTrader Dealer app: plain HTML, CSS,
JavaScript, images and MP4 videos. There is no server code, database or build step. Search
works in the browser.

Live copy: https://rakesh-kumar9.github.io/dealer-manual/

## Install on a web server

1. Get the files: **Code → Download ZIP** on GitHub, or `git clone`.
2. Copy everything **except `.git`, `.nojekyll` and `README.md`** into the folder you serve,
   so that `index.html` sits directly in that folder. All links are relative, so any folder works.
3. Optional: set `404.html` as that folder's page-not-found page.

## Server settings

- About 35 MB, mostly the videos in `videos/`.
- MIME types: `.mp4` → `video/mp4`, `.srt` → `text/plain`.
- Allow range requests for `.mp4` (on by default in IIS, nginx and Apache).
