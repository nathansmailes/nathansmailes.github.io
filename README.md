# nathansmailes.github.io

Top-level website for [Maew Maps](https://nathansmailes.github.io/Maew-Maps/).

- `index.html` sends visitors on to the app.
- `.well-known/assetlinks.json` proves to Android that the Maew Maps Google Play app and this website belong together, so the app opens without a browser address bar. It gets its fingerprint once the Android app is built.
- `.nojekyll` makes GitHub Pages publish the `.well-known` folder.
