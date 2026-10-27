# My Growth System — Versi 0.1

Aplikasi web mobile-first untuk target, rutinitas, belajar, evaluasi, portofolio, dan pencatatan penghasilan.

## File
- `index.html`: aplikasi utama.
- `manifest.json`: metadata instalasi PWA.
- `sw.js`: cache offline dasar.

## Penting
- Data disimpan di browser perangkat melalui localStorage.
- Gunakan menu **Data → Ekspor cadangan** secara berkala.
- Tidak ada akun atau server database pada versi ini.
- Coach adalah sistem respons berbasis aturan lokal, bukan model AI generatif.
- Input suara memakai Web Speech API jika didukung browser. Dukungan dan pemrosesan suara bergantung pada browser.
- Mode kamera hanya menampilkan preview kamera lokal untuk latihan bicara; ini bukan panggilan video AI.
- Pemasangan PWA dan service worker umumnya memerlukan hosting HTTPS. Untuk benar-benar gratis, folder ini dapat diunggah ke layanan hosting statis gratis seperti GitHub Pages; proses penerbitan masih perlu dilakukan.
- Pembaruan: ganti file di hosting dengan versi baru. Ekspor cadangan data sebelum perubahan besar.

## Cara paling mudah mencoba
Buka `index.html` di browser. Beberapa fitur seperti kamera, service worker, dan instalasi PWA bisa membutuhkan HTTPS/localhost.
