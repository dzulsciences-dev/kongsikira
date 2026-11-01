# KongsiKira

Aplikasi web ringkas dalam Bahasa Malaysia untuk membahagi bil makan. Berfungsi pada telefon dan desktop; boleh dipasang sebagai PWA.

## Ciri

- Imbas foto resit dan baca teks melalui OCR dalam pelayar (memerlukan internet untuk memuat turun enjin OCR pada penggunaan pertama).
- Tambah dan ubah item, kuantiti, harga, dan tetapkan seorang kawan bagi setiap item.
- Tambah pelbagai jenis cukai atau caj dengan kadar peratus tersuai.
- Bahagikan cukai mengikut bahagian item yang dipesan dan agihkan pembundaran kepada sen.
- Salin ringkasan pembayaran untuk dikongsi dalam group chat.
- Simpan draf pada peranti dan cache shell aplikasi untuk penggunaan semula.

## Terbitkan ke GitHub Pages

1. Muat naik fail projek ini ke repositori GitHub.
2. Buka **Settings → Pages**.
3. Pilih **Deploy from a branch**, pilih `main` dan folder `/ (root)`, kemudian tekan **Save**.
4. Buka URL GitHub Pages pada telefon. Untuk memasang, pilih **Add to Home Screen** (iPhone) atau **Install app** (Android).

OCR menggunakan Tesseract.js dari CDN. Jika tiada internet atau pengecaman kurang tepat, tambah item menggunakan butang **Tambah item** dan semak semua harga imbasan sebelum berkongsi.
