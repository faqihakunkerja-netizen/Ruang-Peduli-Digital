# Ruang Peduli Digital SMAN 3 Balikpapan 🏫🛡️

Aplikasi web interaktif berbasis gamifikasi dan literasi digital yang dirancang khusus untuk warga sekolah SMA Negeri 3 Balikpapan. Proyek ini merupakan ruang aman digital hasil kolaborasi edukatif bersama **PIK-R Bamboo Integrated** dan **Layanan Bimbingan Konseling (BK) SMAGA**.

Aplikasi ini bertujuan untuk mengedukasi siswa mengenai keamanan siber, privasi data, hukum UU ITE/PDP, pencegahan *cyberbullying*, serta menyediakan kanal pengaduan rahasia yang terintegrasi.

---

## 🚀 Fitur Utama

Aplikasi ini terbagi menjadi 4 ruang utama yang dapat diakses dengan mudah:

### 1. 🏠 Beranda (Home)
* Menyambut para siswa dengan antarmuka inklusif.
* Ringkasan edukasi cepat mengenai 3 pilar krusial: Privasi Data, Gerakan Anti-Bullying, serta Pengenalan Regulasi UU ITE & PDP.

### 2. 🧠 Gelembung Literasi Digital (Pusat Edukasi)
* Mengusung **4 Pilar CABE Digital** (Cakap, Aman, Budaya, Etika) dari Kemenkominfo.
* **Efek 3D Bubble Pop:** Dilengkapi antarmuka gelembung pastel kontras menonjol interaktif (`active:scale-95` dan efek bayangan) saat ditekan untuk memicu pengalaman membaca yang menyenangkan.
* Materi komprehensif mulai dari keamanan akun (2FA, *Phishing*, *Over-sharing*), Kesehatan Mental Siber (*Doomscrolling*, Jejak Digital), hingga Regulasi Negara.

### 3. 🎮 Bermain Game (Gamifikasi Interaktif)
Dua opsi permainan edukatif yang menantang dengan bank soal berisi **75 variasi kuis literasi digital menjebak**:
* **🎲 Ular Tangga Digital:** Papan 10x10 interaktif yang dilengkapi petunjuk rute lompatan (*Jump Route Text*) yang jelas pada kotak tangga/ular (misal: *Lompat 4➔14* atau *Turun 99➔78*). Pion bergerak dengan animasi halus dan disertai panduan bermain terintegrasi.

### 4. 🛡️ Ruang Lapor (Aduan Aman)
* Integrasi langsung menuju Google Form Layanan Pengaduan Rahasia BK Smaga & PIK-R Bamboo.
* Akses darurat ke *Hotline* Krisis Kesehatan Mental Nasional (Into The Light - 119 ext 8).

---

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun menggunakan arsitektur *Single Page Application* (SPA) sederhana yang efisien dan ringan tanpa *library* luar yang rumit:

* **HTML5:** Struktur semantik aplikasi.
* **Tailwind CSS v3:** Menggunakan utilitas kelas untuk tata letak modern, responsif, dan efek interaktif (*backdrop blur, custom animation transitions*).
* **Vanilla JavaScript (ES6):** Logika inti *state* permainan, algoritma pengacakan soal *Fisher-Yates*, animasi manipulasi DOM dinamis, dan sistem pergerakan mekanik bar.

---

## 💻 Cara Menjalankan Proyek

Karena proyek ini bersifat *client-side* murni, Anda tidak memerlukan proses instalasi atau *back-end server* khusus.

1. **Clone repositori ini:**
   ```bash
   git clone [https://github.com/faqihakunkerja-netizen/ruang-peduli-digital-smaga.git](https://github.com/faqihakunkerja-netizen/ruang-peduli-digital-smaga.git)
