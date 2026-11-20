# Krupesh Shitkar – Video Editor Portfolio

One-page portfolio site. No build step: GitHub Pages serves it as is.

## Folder layout (keep it exactly like this)

```
index.html      ← the page
videos/         ← 32 reels (.mp4, H.264, each under 25 MB)
posters/        ← thumbnail for each reel (.jpg)
.nojekyll       ← tells GitHub Pages to serve files untouched
README.md
```

File names are case-sensitive on GitHub. Don't rename anything inside `videos/` or `posters/`.

## Put it online with GitHub Pages

1. Go to github.com → **New repository**. Name it, e.g. `portfolio`, set it to **Public**, then create it.
2. On the empty repo page click **uploading an existing file**.
3. Open the unzipped `ClayCo_Portfolio` folder on your computer, select **everything inside it** (`index.html`, `videos`, `posters`, `README.md`) and drag it into the browser. Drag the contents, not the outer folder.
4. Wait until all files finish uploading, then click **Commit changes**.
5. Go to **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
6. After 1–3 minutes the site is live at `https://<your-username>.github.io/portfolio/`.

`.nojekyll` is a hidden file, so it may not get dragged in. The site works without it.

## Notes

- The scroll transitions use the browser's built-in scroll-driven animations. They run in Chrome, Edge, Brave, Samsung Internet and Safari 26+. In Firefox the page shows all content without the scroll motion.
- If the computer has animations turned off (Windows: Settings → Accessibility → Visual effects → Animation effects; Mac/iPhone: Reduce Motion), the browser asks sites to stay still. The page respects that, so the transitions won't show on that device.
- Grid reels load only when you scroll near them, so the page opens fast. The two before/after reels autoplay muted while on screen.
