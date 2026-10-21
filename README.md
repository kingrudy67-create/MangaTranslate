# MangaTranslate AI v0.2 — prototipe penggantian teks

## Perubahan
- Upload gambar dan URL gambar langsung.
- OCR Tesseract membaca posisi kotak teks (bounding boxes).
- Setiap baris yang dikenali diterjemahkan ke Indonesia melalui MyMemory.
- Hasil terjemahan ditulis kembali ke gambar dan dapat diunduh sebagai PNG.
- Antarmuka mobile-first gelap dengan gradien.

## Cara pakai di Android
1. Upload isi folder ini ke repositori GitHub (file `index.html` harus berada di root).
2. Di Settings → Pages, pilih `Deploy from a branch`, pilih branch repositori (mis. `utama`) dan folder `/(root)`, lalu Save.
3. Buka URL GitHub Pages di Chrome. Internet dibutuhkan untuk memuat Tesseract dan layanan terjemahan.
4. Upload gambar atau masukkan URL gambar langsung, pilih bahasa sumber atau Deteksi otomatis, lalu tekan Terjemahkan & ganti teks.
5. Unduh hasil PNG.

## Batasan nyata
Ini prototipe, bukan hasil setara penerjemah komik profesional. OCR multilingual membutuhkan unduhan paket bahasa dan bisa gagal mengenali font artistik, tulisan vertikal, efek suara, atau teks kecil. Deteksi bahasa otomatis masih berbasis aksara; teks Latin diasumsikan Inggris. Terjemahan per baris bisa kurang natural. Penutup teks memakai warna terang/gelap sederhana, bukan rekonstruksi latar (inpainting), sehingga bisa menutup garis balon atau detail gambar. Link chapter website biasanya tidak dapat diambil langsung karena CORS, login, anti-bot, dan ketentuan situs; URL gambar langsung lebih memungkinkan. Tidak ada hasil yang dijamin untuk semua situs/bahasa.
