# 🕌 Kalkulator Waris Islam Mazhab Syafi'i v2.4 (Ultimate Edition)

Aplikasi web *Single-File* modern untuk menghitung pembagian harta warisan (**Ilmu Faraidh**) secara proporsional, transparan, dan akurat sesuai Syariat Islam berlandaskan **Mazhab Imam Asy-Syafi'i**.

🌐 **Live Demo / Akses Aplikasi:** [Masukkan Link GitHub Pages Anda Di Sini]  
👨‍💻 **Dikembangkan oleh:** [fatur62]  
⚖️ **Lisensi:** MIT License  

---

## ✨ Fitur & Keunggulan Utama v2.4

Kalkulator ini tidak hanya menghitung kasus waris normal, tetapi juga telah dilengkapi dengan algoritma tingkat lanjut untuk menangani **seluruh kasus khusus/langka** dalam mazhab Syafi'i:

1. **Arsitektur Single-File (PWA Ready):** Seluruh logika, antarmuka (Tailwind CSS), ikon SVG, dan *engine* Faraidh menyatu dalam satu file `index.html`. Ringan, cepat, dan siap dijalankan secara offline.
2. **Kalkulasi Tirkah & Wasiat Otomatis:** Menghitung harta bersih siap waris setelah dikurangi hutang/biaya jenazah (*Tajhiz*) serta membatasi wasiat maksimal **1/3 (33.33%)** dari sisa harta sesuai syariat.
3. **Seleksi Hijab & Mahjub Hirman Otomatis:** Menyaring ahli waris yang gugur haknya karena terhalang oleh kerabat yang lebih dekat.
4. **Menangani 6 Kasus Khusus Faraidh Populer:**
   - **'Aul:** Penyesuaian proporsional ketika total bagian *Dzawil Furudh* melebihi 100% (defisit harta).
   - **Radd:** Pengembalian sisa harta secara proporsional kepada *Ashabul Furudh* nasabiyah jika tidak ada *Ashabah*.
   - **Gharrawain ('Umariyatain):** Kasus khusus Suami/Istri bersama Ibu dan Ayah (Ibu mendapat 1/3 dari sisa).
   - **Musyarakah (Himariyyah):** Ketika *Ashabah* kehabisan harta, Saudara Kandung berserikat dengan Saudara Seibu dalam porsi 1/3.
   - **Al-Akdariyyah:** Kakek bersama 1 Saudara Perempuan (terjadi 'Aul ke 9 lalu Tashih ke 27 dengan rasio 2:1).
   - **Takmilah & Ashabah Ma'al Ghair:** Cucu perempuan penyempurna 2/3 dan Saudara perempuan yang naik derajat menjadi *Ashabah*.
5. **Algoritma Al-Jadd wal Ikhwah (Kakek & Saudara):** Sesuai Mazhab Syafi'i, Kakek menguji opsi paling menguntungkan di antara *Muqasamah*, *1/3 Sisa*, atau *1/6 Total Harta*, lengkap dengan taktik *Al-Mu'addah*.
6. **Simulasi Mauquf Janin (Al-Haml):** Menghitung skenario janin dalam kandungan (lahir 1 Laki-laki, 1 Perempuan, atau Kembar) untuk menentukan bagian pasti dan dana aman yang harus ditahan (*Mauquf*).
7. **Tabel Komparasi Normal vs Koreksi:** Menyediakan transparansi penuh berupa perbandingan bagian awal normal dengan koreksi akhir syariat.
8. **Siap Cetak PDF:** Dilengkapi format cetak khusus yang otomatis merapikan laporan menjadi dokumen sertifikat/fatwa waris resmi.

---

## 📖 Petunjuk Penggunaan

1. **Akses Aplikasi:** Buka file `index.html` melalui browser atau kunjungi link GitHub Pages proyek ini.
2. **Seksi 1 (Data Harta):** Masukkan **Total Harta Kotor**, **Hutang/Biaya Jenazah**, dan **Wasiat** (sistem otomatis memperingatkan jika wasiat melebihi 1/3).
3. **Seksi 2, 3, & 4 (Ahli Waris):** Masukkan jumlah ahli waris yang hidup saat pewaris wafat. Anda juga dapat menggunakan tombol **Simulasi Cepat Kasus Khusus** di bagian atas form untuk mempelajari kasus-kasus langka dengan sekali klik.
4. **Seksi 5 (Status Khusus & Janin):** Centang opsi jika terdapat janin dalam kandungan (*Al-Haml*) atau kondisi khusus lainnya.
5. **Hitung & Cetak:** Klik tombol **"⚡ Hitung Pembagian Waris Sekarang"**, periksa rincian tabel perbandingannya, lalu klik **"🖨️ Cetak / Simpan PDF"** untuk mengunduh laporan.

---

## 🛠️ Struktur Repositori

```text
├── index.html        # File tunggal utama (HTML, Tailwind, SVG Icons & Master JS Engine)
└── README.md         # Dokumentasi resmi proyek
