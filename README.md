# lidwinae web

Situs statis sederhana untuk proyek Minecraft milik lidwinae. Desainnya memakai latar hitam, font Archivo, teks putih, dan screenshot Minecraft berukuran besar.

Situs ini tidak berisi pemberitahuan penghentian Google Sites. Fungsinya hanya sebagai tempat penjelasan proyek:

- **Winaeth** — dokumentasi cerita, dunia, karakter, ending, dan status pengembangan.
- **Clean & Clear Glass** — fitur, style, kompatibilitas, instalasi, dan tautan unduhan.
- **Future projects** — ruang untuk menambahkan mod atau resource pack lain nanti.

## Halaman

- `index.html` — halaman utama dan daftar proyek.
- `winaeth.html` — penjelasan lengkap Winaeth.
- `glass.html` — penjelasan Clean & Clear Glass.
- `404.html` — halaman untuk URL yang tidak ditemukan.
- `styles.css` — seluruh tampilan situs.
- `app.js` — menu perangkat kecil dan tahun footer otomatis.

## Mengganti screenshot

Saat ini semua slot gambar memakai:

`assets/screenshots/placeholder.jpg`

Gambar tersebut disalin dari:

`C:\Users\lidwina\Downloads\2026-07-24_17.03.14.jpg`

Ada dua cara menggantinya:

1. Timpa `placeholder.jpg` untuk mengganti semua slot sekaligus.
2. Simpan screenshot baru dengan nama berbeda, lalu ubah atribut `src` pada slot yang bersangkutan. Setiap slot sudah memiliki komentar HTML seperti `Replace with a ... screenshot` agar mudah dicari.

Aspek rasio yang disarankan adalah **16:9**. Resolusi seperti 1920×1080 atau 2560×1440 akan cocok dengan layout yang ada.

File `assets/og.png` adalah gambar generasi sebelumnya yang tetap disimpan sebagai koleksi. File tersebut tidak digunakan oleh halaman atau metadata situs.

## Menerbitkan melalui GitHub Pages

1. Upload seluruh **isi** folder ini ke root repositori `https://github.com/lidwinae/web`.
2. Pastikan `index.html` berada langsung di root repositori, bukan di dalam folder tambahan.
3. Di GitHub, buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch **main** dan folder **/(root)**, kemudian simpan.

Alamat situsnya akan menjadi:

`https://lidwinae.github.io/web/`

Situs ini hanya memakai HTML, CSS, dan JavaScript. Tidak ada dependency atau build command.
