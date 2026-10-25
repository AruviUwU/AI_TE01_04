# AI-TE
# 🏋️‍♂️ Sistem Pakar Kebugaran (Fitness Expert System)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![React](https://img.shields.io/badge/React-18+-61dafb?logo=react)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-4+-3178c6?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-3+-38bdf8?logo=tailwindcss)](https://tailwindcss.com/)

Sistem pakar berbasis web modern yang membantu pengguna merencanakan rutinitas latihan yang dipersonalisasi dan menampilkan kutipan motivasi. Dibangun dengan **React**, **TypeScript**, dan **Tailwind CSS**, proyek ini mendemonstrasikan mesin inferensi berbasis aturan (*rule-based inference engine*) untuk rekomendasi kebugaran.

## ✨ Fitur
- **Perencana Latihan yang Dipersonalisasi:** Masukkan tujuan kebugaran, tingkat pengalaman, dan peralatan yang tersedia untuk mendapatkan rencana latihan yang sesuai.
- **Basis Data Latihan:** Kumpulan latihan pilihan lengkap dengan deskripsi detail dan kategori.
- **Kutipan Motivasi:** Kutipan inspiratif yang ditampilkan secara acak untuk menjaga semangatmu.
- **Mesin Inferensi Berbasis Aturan:** Rekomendasi cerdas berdasarkan masukan pengguna dan aturan pakar.
- **UI Modern:** Antarmuka yang responsif, mudah diakses, dan menarik secara visual, didukung oleh Tailwind CSS.

## 📁 Struktur Proyek

```text
fitness-expert-system/
├── src/
│   ├── components/    # Komponen React yang dapat digunakan ulang
│   ├── data/          # Data latihan, kutipan, dan aturan
│   ├── hooks/         # Custom hooks React
│   ├── types/         # Definisi tipe TypeScript
│   └── utils/         # Mesin inferensi dan fungsi utilitas
├── index.html         # File HTML utama
├── package.json       # Metadata proyek dan dependensi
├── tailwind.config.js # Konfigurasi Tailwind CSS
├── vite.config.ts     # Konfigurasi build Vite
└── ...
```

## 🚀 Memulai

### Prasyarat
- [Node.js](https://nodejs.org/) (disarankan v16 atau lebih baru)
- [npm](https://www.npmjs.com/)

### Instalasi
1. **Clone repositori:**
   ```sh
   git clone https://github.com/your-username/fitness-expert-system.git
   cd fitness-expert-system
   ```
2. **Instal dependensi:**
   ```sh
   npm install
   ```
3. **Jalankan server pengembangan:**
   ```sh
   npm run dev
   ```
4. **Buka** [http://localhost:5173](http://localhost:5173) di browser kamu.

## 📝 Cara Penggunaan

1. Isi formulir latihan sesuai preferensimu.
2. Lihat rencana latihan yang dipersonalisasi beserta kutipan motivasinya.
3. Ubah masukanmu untuk menghasilkan rencana baru.

## 🛠️ Teknologi yang Digunakan

- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vite](https://vitejs.dev/)

## 📸 Tangkapan Layar

### Beranda
<div align="center">
   <img src="./src/screenshots/homepg-one.png" alt="Beranda" width="600" />
   <img src="./src/screenshots/homepg-two.png" alt="Beranda" width="600" />
   <img src="./src/screenshots/homepg-three.png" alt="Beranda" width="600" />
   <img src="./src/screenshots/homepg-four.png" alt="Beranda" width="600" />
</div>

### Formulir Input
<div align="center">
   <img src="./src/screenshots/input-form-one.png" alt="Formulir Input" width="600" />
   <img src="./src/screenshots/input-form-two.png" alt="Formulir Input" width="600" />
</div>

### Rekomendasi
<div align="center">
   <img src="./src/screenshots/recommendation-one.png" alt="Rekomendasi" width="600" />
   <img src="./src/screenshots/recommendation-two.png" alt="Rekomendasi" width="600" />
   <img src="./src/screenshots/recommendation-three.png" alt="Rekomendasi" width="600" />
</div>

## 🤝 Kontribusi

Kontribusi sangat diterima! Silakan buka *issue* atau kirim *pull request* untuk perbaikan dan penyelesaian bug.

1. Fork repositori ini
2. Buat branch fitur kamu (`git checkout -b feature/FiturKamu`)
3. Commit perubahanmu (`git commit -m 'Tambah fitur baru'`)
4. Push ke branch tersebut (`git push origin feature/FiturKamu`)
5. Buka pull request

## 📄 Lisensi

Proyek ini dilisensikan di bawah [Lisensi MIT](LICENSE).

## 🙏 Ucapan Terima Kasih

- Terinspirasi oleh kebutuhan akan alat perencanaan kebugaran yang mudah diakses dan didukung oleh keahlian pakar.
- Terima kasih kepada komunitas open-source atas pustaka dan sumber dayanya.

## 📬 Kontak

Untuk pertanyaan, masukan, atau kolaborasi, silakan hubungi [chinomsochristian03@gmail.com](mailto:chinomsochristian03@gmail.com).

## 🧑‍💻 Penulis

**Nduoma Chinomso Christian**  
_AKA Buzz brain_