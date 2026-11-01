# Arus — Catatan Keuangan (frontend PWA)

Folder ini di-hosting apa adanya (misalnya di GitHub Pages). Tidak ada proses build.
URL Web App dan kunci rahasia TIDAK disimpan di sini — diisi langsung di HP saat pertama kali membuka aplikasi.

Struktur:
- index.html            → kerangka halaman
- css/styles.css        → tampilan
- js/app.js             → logika utama
- js/api.js             → komunikasi ke Google Apps Script
- js/utils.js           → format Rupiah, tanggal, periode
- js/charts.js          → grafik SVG
- manifest.webmanifest  → identitas PWA (nama, ikon)
- sw.js                 → service worker (offline). Naikkan VERSION setiap mengubah file.
- icons/                → ikon aplikasi
