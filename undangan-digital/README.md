# Web Undangan Pernikahan Digital - Arya & Annisa

Web undangan pernikahan digital elegan khas Indonesia, interaktif, responsif, dan **dapat diakses oleh siapa saja secara gratis tanpa perlu menyewa server**.

---

## 🌟 Fitur Lengkap Undangan
1. **Cover Pembuka Interaktif (Open Invitation):**
   - Mendukung nama tamu kustom dinamis via URL (Contoh: `?to=Bapak+Budi+Santoso`).
   - Tombol "Buka Undangan" otomatis memicu audio latar & animasi confetti.
2. **Audio / Musik Latar:**
   - Tombol floating musik (Play / Pause) dengan animasi piringan hitam berputar.
3. **Hitung Mundur (Countdown Timer):**
   - Hari, Jam, Menit, dan Detik otomatis menghitung mundur ke hari H acara.
4. **Profil Mempelai Khas Indonesia:**
   - Raden Arya Pratama, S.T. & Siti Annisa Rahmawati, S.Farm. lengkap dengan nama orang tua dan tautan sosial media.
5. **Kisah Cinta (Love Story Timeline):**
   - Perjalanan awal bertemu, lamaran, hingga menuju pelaminan.
6. **Rincian Acara & Peta Lokasi:**
   - Jadwal Akad Nikah & Resepsi di Grand Ballroom Sasana Kriya TMII Jakarta Timur.
   - Peta interaktif Google Maps + tombol "Buka di Google Maps" dan "Simpan ke Google Calendar".
7. **Galeri Foto Pre-Wedding:**
   - Tampilan foto grid estetik + Lightbox pop-up resolusi penuh.
8. **Amplop Digital (Wedding Gift):**
   - Nomor Rekening Bank BCA dan Mandiri dengan tombol **Salin Nomor Rekening (1-Klik)**.
   - Alamat pengiriman kado fisik lengkap dengan tombol salin alamat.
9. **Buku Tamu & RSVP Interaktif:**
   - Form konfirmasi kehadiran (Hadir / Tidak Hadir / Ragu), jumlah orang, dan kolom ucapan & doa restu.
   - Daftar ucapan tersimpan otomatis di browser (`localStorage`).
10. **Floating Bottom Navbar:** Navigasi cepat antar bagian undangan.

---

## 🌐 Cara Publikasi Online Gratis (Bisa Diakses Semua Orang)

Karena dibuat secara *serverless* (Single File Standalone), Anda dapat mengunggah file `index.html` ini ke layanan hosting gratis tanpa biaya sepeser pun:

### Opsi 1: GitHub Pages (Paling Populer & Permanen)
1. Buat repositori baru di GitHub (misal: `undangan-arya-annisa`).
2. Upload file `index.html`.
3. Buka **Settings** -> **Pages** -> Pilih Branch `main` -> Klik **Save**.
4. Link Anda akan langsung aktif, contoh: `https://username.github.io/undangan-arya-annisa/?to=Nama+Tamu`

### Opsi 2: Netlify Drop / Vercel (1 Menit Selesai)
1. Buka [app.netlify.com/drop](https://app.netlify.com/drop).
2. Tarik (*drag and drop*) folder `undangan-digital`.
3. Dalam 5 detik Anda mendapatkan tautan publik gratis `https://undangan-anda.netlify.app`.

---

## 💡 Cara Personalisasi Nama Tamu
Tambahkan parameter `?to=` di akhir link URL:
- `.../index.html?to=Bapak+Joko+Widodo`
- `.../index.html?to=Keluarga+Besar+Budi+Santoso`
- `.../index.html?to=Sahabat+Alumni+SMA+1`
