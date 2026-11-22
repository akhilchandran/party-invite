# Abhil & Nima Wedding Invitation — Deployment Package (v3)

## What's Updated
- **Envelope-to-Full-Screen Zoom Out (`#inside`)**: After the 3D envelope flaps fold open, the invitation card emerges from inside the square envelope (`scale(0.55)` at the envelope's center) and smoothly zooms out (`1.15s` cubic-bezier) to fill the full card frame while the cover fades behind it.
- **Envelope-Bounded 3D Flaps**: Only the square envelope (`10.33%` left, `79.34%` width, `23.00%` to `78.92%` height) folds open, leaving the flatlay desk/floral background stationary.
- **Smooth First-Click Opening**: Two-frame `requestAnimationFrame` transition commitment and `img.decode()` preloading eliminate first-tap stutter.

## Required Image Files
Place these three image files in the same root folder alongside `index.html` before uploading to Netlify:
- `cover.jpg`
- `invitation_2.jpg`
- `preview.jpg`

## How to Deploy
1. Extract this ZIP archive.
2. Copy `cover.jpg`, `invitation_2.jpg`, and `preview.jpg` into the extracted folder alongside `index.html`.
3. Drag and drop the folder onto Netlify Drop (https://app.netlify.com/drop) or push to your repository.
