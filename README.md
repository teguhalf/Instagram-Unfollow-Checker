# 📸 Instagram Unfollow Checker

Aplikasi berbasis web yang minimalis, modern, dan aman untuk mendeteksi siapa saja akun Instagram yang tidak mengikuti Anda kembali (*unfollow back*). Proses analisis dilakukan 100% secara lokal di browser Anda menggunakan file data resmi (`.json`) dari Instagram.

---

## ✨ Fitur Utama

- **100% Aman & Privat**: File data Anda tidak pernah diunggah ke server mana pun. Seluruh proses parsing dan komparasi logika berjalan sepenuhnya di sisi klien (*client-side*).
- **Desain Modern Minimalis**: Tampilan antarmuka estetik bertema *Glassmorphic* dengan dukungan Live Wallpaper latar belakang berbasis video `.mp4`.
- **Pencarian & Filter Instan**: Memudahkan Anda mencari *username* tertentu dari daftar akun yang tidak melakukan *followback*.
- **Salin Sekaligus (Copy All)**: Fitur sekali klik untuk menyalin seluruh daftar akun yang tidak mengikuti balik ke *clipboard* Anda.
- **Responsif & Interaktif**: Dilengkapi dengan animasi halus (*fade-up*), efek seret-dan-lepas (*drag & drop* file), serta notifikasi *toast*.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5**: Struktur semantik aplikasi.
- **CSS3 / Tailwind CSS**: Desain visual, tata letak grid/flexbox, efek transparansi kaca (*backdrop-filter*), dan animasi.
- **JavaScript (Vanilla)**: Logika pencarian data, enkapsulasi status (*state management*), *File Reader API*, dan manipulasi DOM.
- **Google Fonts**: Menggunakan font premium *Plus Jakarta Sans* (untuk judul) dan *Inter* (untuk teks data) agar tampilan terlihat bersih dan elegan.

---

## 📂 Struktur Repositori

```text
├── index.html       # Struktur utama aplikasi & Logika JavaScript
├── style.css        # Konfigurasi tema, video background, & efek glassmorphism
└── README.md        # Dokumentasi proyek (file ini)
