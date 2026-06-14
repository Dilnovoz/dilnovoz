# Dilnovoz Abdurazzakova — Personal Academic Website

## Files
- `index.html` — Home page
- `research.html` — Research & publications
- `cv.html` — Full CV
- `photography.html` — Photography gallery
- `style.css` — Shared stylesheet

## How to deploy on GitHub Pages (free, ~10 minutes)

1. Go to https://github.com and create a free account if you don't have one
2. Click the **+** button → **New repository**
3. Name it exactly: `yourusername.github.io` (replace with your GitHub username)
4. Set it to **Public**, then click **Create repository**
5. Click **uploading an existing file** on the next screen
6. Drag and drop ALL the files from this folder (index.html, research.html, cv.html, photography.html, style.css)
7. Click **Commit changes**
8. Wait ~2 minutes, then visit `https://yourusername.github.io` — your site is live!

## Adding your CV PDF
- Put your CV PDF file in the same folder, e.g. `CV_Abdurazzakova.pdf`
- In `cv.html`, find the download link and update it:
  `<a class="cv-download" href="CV_Abdurazzakova.pdf" download>`

## Adding photos to the Photography page
- Create a `photos/` folder
- Put your image files inside (JPG or WebP recommended)
- In `photography.html`, replace each placeholder block like this:

```html
<!-- BEFORE (placeholder) -->
<div class="photo-cell">
  <div class="placeholder">...</div>
</div>

<!-- AFTER (with your photo) -->
<div class="photo-cell">
  <img src="photos/your-photo.jpg" alt="Brief description">
</div>
```

## Things to update
- [ ] Add your Google Scholar / SSRN links in `index.html` (hero-links section)
- [ ] Upload your CV PDF and update the download link in `cv.html`
- [ ] Add supervisor faculty page links in `index.html`
- [ ] Add your photos to the photography page
- [ ] Add paper PDFs and update links in `research.html`
