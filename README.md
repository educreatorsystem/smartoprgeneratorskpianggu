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
- Sheet ID: `1a30dcQ1hOgTHJe0nraHKZCp3_Dd4Q-KTrH7miVxnxiY`
- Drive Folder ID: `17VyCF8-8cSmeIPnGZgVZwHdPuLrRns26`
- Apps Script URL: `https://script.google.com/macros/s/AKfycbz0J25FhanYXblXGMiGTlPZ7AhCcrTFhaiFvwe4dYjMnsxkmoNKOsYf1TU4RhxzGsVCWw/exec`
