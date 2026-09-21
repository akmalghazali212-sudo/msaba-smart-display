MSABA SMART DISPLAY V4 - APP SHELL

TARGET SMART DISPLAY:
https://script.google.com/macros/s/AKfycbyPomsJrKK3XYeaigyLI_y5MFHiR1EiK_wx5pKSw4GDkKLv-NFEnBHG00RfQEEjLvq8/exec

FAIL:
- index.html
- manifest.json
- service-worker.js
- offline.html
- icons/icon-192.png
- icons/icon-512.png

CARA HOST PALING MUDAH (GITHUB PAGES):
1. Buat repository baru, contoh: msaba-smart-display.
2. Upload SEMUA kandungan folder ini ke root repository.
3. Settings > Pages.
4. Source: Deploy from a branch.
5. Branch: main / root.
6. Save dan tunggu GitHub Pages URL keluar.
7. Buka URL Pages menggunakan Chrome/Edge.
8. Tekan INSTALL APP jika butang tersedia, atau menu browser > Install app/Add to Home screen.
9. Bila app dibuka, tekan BUKA SMART DISPLAY.

NOTA:
App shell/PWA ini tidak cuba menyalin google.script.run keluar dari Apps Script.
Paparan Smart Display sebenar kekal dijalankan oleh deployment Apps Script asal supaya fungsi Google Sheets, Drive, audio dan scheduler kekal serasi.
