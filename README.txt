MSABA SMART DISPLAY V4.1 - DIRECT LAUNCH / KIOSK

1. APPS SCRIPT: gantikan fungsi doGet() lama SAHAJA dengan APPS-SCRIPT-doGet-PATCH.gs.
2. Save. Deploy > Manage deployments > Edit > New version > Deploy.
3. GITHUB: replace/upload index.html, manifest.json, service-worker.js, offline.html, icon-192.png, icon-512.png di ROOT.
4. Commit dan tunggu GitHub Pages deploy.
5. Tutup app lama. Buka GitHub Pages dan Ctrl+Shift+R.
6. Jika app terpasang masih cache versi lama, tutup/buka semula; jika perlu uninstall dan install semula.

V4.1 mengekalkan app pada domain GitHub dan memuatkan Apps Script dalam iframe. Ini mengelakkan redirect ke script.google.com yang menyebabkan external-site bar.
Target: https://script.google.com/macros/s/AKfycbyPomsJrKK3XYeaigyLI_y5MFHiR1EiK_wx5pKSw4GDkKLv-NFEnBHG00RfQEEjLvq8/exec
