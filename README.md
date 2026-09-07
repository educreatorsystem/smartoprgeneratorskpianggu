# Sistem OPR SK Pianggu — PWA

Fail ini sedia untuk diterbitkan melalui GitHub Pages.

## Kandungan
- `index.html` — sistem OPR + konfigurasi PWA
- `Code.gs` — kod Google Apps Script untuk Google Sheet/Drive
- `manifest.webmanifest` — manifest pemasangan PWA
- `sw.js` — service worker/cache
- `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` — ikon aplikasi
- `apple-touch-icon.png` — ikon iPhone/iPad
- `.nojekyll`

## Publish ke GitHub Pages
1. Muat naik semua fail ini ke root repository GitHub.
2. Buka **Settings → Pages**.
3. Pilih **Deploy from a branch**.
4. Pilih `main` dan `/(root)`.
5. Buka URL GitHub Pages melalui HTTPS.

PWA menggunakan laluan relatif dan sesuai untuk GitHub Pages. Sambungan Google Sheet dan Google Drive menggunakan konfigurasi SK Pianggu.

> `Code.gs` perlu dideploy melalui Google Apps Script. Fail ini disertakan dalam ZIP sebagai rujukan/kod backend.

## Konfigurasi semasa
- Sheet ID: `1GQG64r6T0zGb052TGJ3Wtf04D6kgjQ4EfJdP0vo8uKk`
- Drive Folder ID: `1n6RrDekozKLJ1ngeqBThfGPZASQVYCWw`
- Apps Script URL telah ditetapkan dalam `index.html`.
