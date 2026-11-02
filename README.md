# KongsiKira

Aplikasi web Bahasa Malaysia untuk bahagi bil makan dengan kawan. Direka untuk paparan telefon dan desktop, dan boleh dipasang sebagai PWA melalui GitHub Pages.

## Fungsi

- Imbas foto resit menggunakan OCR dalam pelayar. OCR perlukan internet; semak setiap item dan harga yang dikenal pasti.
- Pilih sama ada mahu ambil gambar resit dengan kamera atau muat naik foto daripada album.
- Tukar antara tab **Satu resit** dan **Gabung resit**. Tab **Satu resit** dibuka sebagai lalai; mod gabungan menyimpan beberapa resit berasingan dan mengira semua hidangan dalam satu jumlah.
- Tambah, sunting, assign kepada kawan, atau buang hidangan.
- Tambah dan buang kawan; hidangan mereka akan dipindahkan kepada kawan pertama yang tinggal.
- Tambah pelbagai cukai atau caj peratus. Setiap caj dibahagi mengikut nilai makanan setiap orang.
- Lihat laporan penuh makanan, cukai, item setiap kawan, dan jumlah bayaran.
- Salin laporan untuk group chat atau cetak/simpan sebagai PDF.
- Simpan draf pada peranti. Versi web boleh dimuat semula melalui service worker.

## Terbitkan ke GitHub Pages

1. Muat naik `index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`, dan `README.md` ke akar repositori.
2. Buka **Settings → Pages**.
3. Pilih **Deploy from a branch**, branch `main`, folder `/(root)`, dan tekan **Save**.
4. Selepas deployment berjaya, buka pautan Pages pada telefon.
5. Pilih **Add to Home Screen** (iPhone) atau **Install app** (Android).

Semua data bil disimpan dalam storan pelayar pada peranti itu. OCR memuatkan Tesseract.js daripada CDN; kalau pengecaman gagal, tambah atau betulkan item secara manual. Dalam mod gabungan, senarai kawan dan kadar cukai digunakan bersama untuk semua resit.
