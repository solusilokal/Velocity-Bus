# Velocity Bus - Mini Website Jasa Transportasi Bus

Mini website interaktif untuk profil dan pemesanan tiket bus **Velocity Bus**, dibuat dengan React, TypeScript, Tailwind CSS, dan Lucide Icons.

---

## 🚀 Cara Melihat Preview

Ada 2 cara mudah untuk melihat preview website ini:

### Cara 1: Standalone Preview (Paling Cepat & Tanpa Terminal)
1. Buka folder ini di File Explorer: `Mini Website\jasa transportasi bus`
2. Klik ganda (**double-click**) pada file **`preview.html`**
3. Halaman website akan langsung terbuka di browser Anda (Google Chrome / Microsoft Edge) tanpa perlu menjalankan server atau terminal.

---

### Cara 2: Menjalankan Local Dev Server (Vite)
Jika ingin menggunakan live preview dengan hot-reload:

1. **Menggunakan launcher otomatis:**
   - Klik ganda file **`start-dev.bat`**
   - Script akan otomatis mengecek dependensi, menginstal jika belum ada, dan membuka browser di `http://localhost:3000`.

2. **Atau melalui terminal/Command Prompt:**
   ```bash
   npm run dev
   ```
   Lalu buka URL yang muncul di terminal (biasanya `http://localhost:3000`).

---

## 📁 Struktur File

- `preview.html` : Versi preview mandiri (standalone) yang bisa dibuka langsung di browser.
- `start-dev.bat` : Launcher otomatis 1-klik untuk Windows.
- `velocity_bus.tsx` : Komponen utama React Velocity Bus.
- `index.html` : Entry point HTML untuk build Vite.
- `src/App.tsx` : Penghubung komponen utama.
- `src/main.tsx` : Root entry React DOM.
- `src/index.css` : Konfigurasi Tailwind CSS dan font Plus Jakarta Sans.
- `package.json` : Konfigurasi dependensi project.
- `vite.config.ts` : Konfigurasi bundler Vite.
- `tailwind.config.js` : Konfigurasi Tailwind CSS.

---

## 🛠️ Fitur Website
- **Hero & Profil Pool**: Informasi kontak, media sosial, dan tombol booking.
- **Highlights Bar**: Keunggulan layanan (Tepat Waktu, Armada Baru, Kru Profesional).
- **Tentang Kami & Sejarah**: Kisah perjalanan dan milestone Velocity Bus.
- **Katalog Armada**: Galeri interaktif kelas bus (Sleeper Class, Super Executive, VIP) lengkap dengan Lightbox viewer layar penuh.
- **Rute & Harga**: Daftar tarif perjalanan antarkota.
- **Lokasi Pool**: Titik kumpul dan alamat agen.
- **FAQ Interaktif**: Accordion tanya-jawab yang bisa dibuka/tutup.
- **Testimoni**: Ulasan dari penumpang.
- **Formulir Pemesanan Tiket**: Terintegrasi langsung untuk mengirim pesan WhatsApp ke admin reservasi.
- **Share Modal**: Fitur berbagi tautan ke WhatsApp, Twitter/X, Facebook, dan salin link.
- **Sticky CTA**: Tombol pemesanan mengambang saat halaman digulir.
