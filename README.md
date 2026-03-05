# Trello Archive Manager

Aplikasi web untuk melihat dan mencari semua kartu yang diarsipkan di Trello.

## Fitur
- 🗂️ Muat semua kartu arsip dari seluruh board
- 🖼️ Thumbnail gambar pada kartu
- 🔍 Search & filter (board, hari/bulan/tahun, label)
- 📎 Lihat & unduh lampiran
- 💬 Lihat aktivitas & komentar kartu
- 🌐 Bahasa Indonesia / English

## Deploy ke GitHub Pages

1. Buat repository baru di GitHub (misal: `trello-archive`)
2. Upload file `index.html` ke repository
3. Buka **Settings** → **Pages**
4. Source: `Deploy from a branch` → branch `main` → folder `/ (root)`
5. Klik **Save**
6. Tunggu ~1 menit → akses di `https://USERNAME.github.io/trello-archive`

## Cara Mendapatkan API Key & Token Trello

1. Buka [https://trello.com/app-key](https://trello.com/app-key)
2. Salin **API Key**
3. Klik **"Generate a Token"** → izinkan akses → salin **Token**
4. Tempel keduanya di aplikasi → klik **Muat Arsip**

## Catatan
- API Key & Token hanya tersimpan di browser (tidak dikirim ke server manapun)
- Aplikasi berjalan 100% di sisi klien (GitHub Pages static hosting)
