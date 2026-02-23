# 🌙 Ramadhan Ilmi: Daily Achievement Web App

![GitHub stars](https://img.shields.io/github/stars/MohammadIsma11/Ramadhan_Ilmi?style=for-the-badge&color=fbbf24)
![GitHub last commit](https://img.shields.io/github/last-commit/MohammadIsma11/Ramadhan_Ilmi?style=for-the-badge&color=064e3b)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**Ramadhan Ilmi** adalah proyek *web-based personal greeting* yang dirancang untuk menemani perjalanan Ramadan selama 30 hari penuh. Proyek ini menggabungkan estetika **Glassmorphism UI** dengan **Interactive Animation** sebagai bentuk apresiasi harian untuk pasangan/orang tersayang.

---

## ✨ Fitur Unggulan

* **📅 30 Days Journey**: Setiap hari memiliki halaman unik (`hari_1.html` - `hari_30.html`) dengan desain yang berevolusi tiap minggu.
* **💎 Premium Glassmorphism**: Desain mewah dengan teknik *backdrop-filter* dan gradasi warna (Emerald Gold untuk Week 1 & Midnight Blue untuk Week 2).
* **📱 Mobile-First Design**: Dioptimasi khusus untuk layar smartphone (presisi untuk HP Infinix, Samsung, iPhone, dll).
* **🎊 Interactive Celebration**: Animasi kembang api otomatis menggunakan `canvas-confetti` saat halaman dibuka.
* **📜 Emotional Typography**: Perpaduan font *Amiri* untuk nuansa Islami dan *Caveat* untuk sentuhan personal.

---

## 🛠️ Teknologi yang Digunakan

* **HTML5 & CSS3**: Custom Flexbox & Grid dengan variabel CSS untuk manajemen tema.
* **JavaScript (Vanilla)**: Manipulasi DOM untuk logika perayaan dan animasi.
* **GitHub Pages**: Sebagai platform *hosting* untuk akses link yang cepat dan mudah.

---

## 🚀 Cara Menggunakan (Untuk Pengembang Lain)

Jika Anda ingin menggunakan repositori ini untuk memberikan kejutan kepada orang tersayang, silakan ikuti langkah berikut:

1.  **Fork** repository ini ke akun GitHub Anda.
2.  **Kustomisasi Pesan**:
    * Cari bagian `<div class="emotional-text">` atau `<div class="message-box">` di setiap file HTML.
    * Ubah nama "Ilmi" menjadi nama orang tersayang Anda.
3.  **Deployment**:
    * Masuk ke menu **Settings** > **Pages** di repository Anda.
    * Pada bagian Build and deployment, pilih Branch **main** dan folder **/(root)**.
    * Website Anda akan aktif dalam hitungan menit di link `https://username.github.io/Ramadhan_Ilmi/`.

---

## 📂 Struktur Repositori

```text
.
├── index.html          # Gerbang utama (Verification System)
├── menu.html           # Dashboard target Ramadan
├── hari_1.html         # Ucapan Milestone Hari ke-1 (Week 1 Theme)
├── hari_7.html         # Penutup Minggu Pertama (Milestone 1 Week)
├── hari_8.html         # Awal Minggu Kedua (Midnight Blue Theme)
└── README.md           # Dokumentasi Proyek
