# AR Memory Trail (WebAR)

This project creates a browser-based AR apology experience with A-Frame + AR.js.
No app download required.

## Files

- `index.html`: Main AR scene.
- `assets/memory-01.jpg` ... `assets/memory-06.jpg`: Your memory photos.

## 1) Add Your Photos

Place your photos in the `assets` folder with these exact names:

- `memory-01.jpg`
- `memory-02.jpg`
- `memory-03.jpg`
- `memory-04.jpg`
- `memory-05.jpg`
- `memory-06.jpg`

You can use `.png` if you update the file extensions in `index.html`.

## 2) Customize Messages

Edit the `<a-text>` entries in `index.html` to change apology lines and positions.

## 3) Deploy on GitHub Pages

1. Create a GitHub repository (example: `apology`).
2. Upload all files from this folder.
3. In repository settings, open **Pages**.
4. Set source to `Deploy from a branch`, branch `main`, folder `/ (root)`.
5. Save and wait for the site URL to appear.

Example URL:

- `https://a-k-0802.github.io/apology/`

## 4) Create QR Code

Generate a high-resolution QR code for your GitHub Pages URL and print it.

## Notes

- This works best over HTTPS (GitHub Pages provides HTTPS).
- On first open, camera permission is required.
- Some iPhones may need Safari and motion/camera permissions enabled.
