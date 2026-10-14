WEBSITE ULANG TAHUN ZARA KALISYA EVANIA 💗

ISI:
- index.html: website siap dibuka di browser.
- assets/: tempat menyimpan foto dan lagu jika ingin ditambahkan permanen.

COBA DI HP:
1. Unduh ZIP lalu ekstrak.
2. Buka index.html dengan Chrome (atau gunakan editor seperti Acode).
3. Pilih kotak foto untuk melihat preview foto. Preview pilihan foto hanya ada pada browser saat itu; agar permanen, ikuti bagian FOTO di bawah.

PERSONALISASI FOTO AGAR PERMANEN:
1. Masukkan foto ke folder assets, misalnya kenangan1.jpg, kenangan2.jpg, kenangan3.jpg.
2. Di index.html, cari bagian photo-grid. Ganti isi setiap label.photo dengan:
   <img src="assets/kenangan1.jpg" alt="Kenangan kita">
   (ganti nama file untuk foto berikutnya).
3. Unggah folder website beserta assets ke hosting.

MUSIK:
1. Simpan file audio yang kamu punya/berhak gunakan ke assets/lagu.mp3.
2. Di index.html cari `const MUSIC_URL=""` lalu ubah menjadi `const MUSIC_URL="assets/lagu.mp3"`.
3. Musik otomatis tanpa interaksi sering diblokir browser. Tombol musik disediakan agar pacar bisa menyalakannya setelah membuka web. Gunakan lagu yang kamu punya hak untuk pakai.

QR CODE:
- QR akan mengarah ke alamat halaman yang sedang dibuka. Dari file lokal, QR tidak berguna bagi orang lain.
- Setelah hosting, buka link publik website lalu tekan “Buat QR dari link ini”.
- QR standar dipilih agar lebih mudah dipindai. Jangan ubah pola QR menjadi bentuk hati penuh karena bisa membuatnya gagal terbaca.

PUBLIKASI GRATIS DENGAN GITHUB PAGES:
1. Login/daftar di https://github.com
2. Buat repository baru, misalnya `ultah-zara`. Pilih Public.
3. Unggah `index.html` dan folder `assets` (jika ada) ke repository.
4. Buka Settings > Pages.
5. Pada “Build and deployment”, pilih “Deploy from a branch”.
6. Pilih branch `main`, folder `/(root)`, lalu Save.
7. Tunggu beberapa menit. Link akan tampil di bagian Pages, biasanya seperti https://username.github.io/ultah-zara/
8. Buka link tersebut di browser. Tekan “Buat QR dari link ini” untuk membuat QR yang mengarah ke web publik.

ALTERNATIF NETLIFY DROP:
1. Buka https://app.netlify.com/drop
2. Ekstrak ZIP.
3. Seret folder `website_ultah_zara` ke area upload Netlify Drop dari browser/perangkat yang mendukung upload folder.
4. Tunggu hingga Netlify memberi URL publik. Jika dari HP tidak bisa mengunggah folder, gunakan GitHub Pages atau komputer.

CATATAN:
- Hitung mundur diarahkan ke 15 Oktober 2026, zona waktu WIB (UTC+7). Jika tanggal sudah lewat, angka akan menunjukkan waktu yang telah berlalu dan label ulang tahun tiba.
- QR menggunakan layanan QR eksternal saat tombol dipakai, jadi perangkat memerlukan internet.
- Tidak ada database/server; ini website statis.
