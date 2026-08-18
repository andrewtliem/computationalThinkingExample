# 🧩 Lab Berpikir Komputasional (Computational Thinking Lab)

Media pembelajaran interaktif berbasis web untuk memahami **4 Pilar Berpikir Komputasional (*Computational Thinking*)**:
1. **Abstraksi (*Abstraction*)**
2. **Dekomposisi (*Decomposition*)**
3. **Pengenalan Pola (*Pattern Recognition*)**
4. **Perancangan Algoritma (*Algorithmic Thinking*)**

Dibuat dalam format **single-file standalone (`index.html`)** tanpa dependensi backend atau bundler, siap dijalankan langsung di browser atau di-host melalui **GitHub Pages**.

---

## 🚀 Live Demo
Website ini dapat diakses secara publik melalui GitHub Pages:  
👉 **https://andrewtliem.github.io/computationalThinkingExample/**

---

## 🎯 Modul Pembelajaran Interaktif

### 1. 👥 Modul 1: Barisan Siswa (*Sorting - Bubble Sort*)
* **Studi Kasus:** Mengurutkan barisan siswa dari yang paling pendek ke paling tinggi dengan atribut: Nama, Tinggi Badan, Berat Badan, dan Jenis Kelamin.
* **Fitur Interaktif:**
  * Filter Abstraksi: Memilih data penting vs data yang diabaikan secara visual.
  * Dekomposisi: Memecah barisan menjadi perbandingan 2 orang bersebelahan.
  * Pengenalan Pola: Aturan kondisi `IF (Kiri > Kanan) THEN TUKAR`.
  * Visualizer Algoritma: Simulasi Bubble Sort step-by-step & otomatis, pengatur kecepatan animasi, generator acak siswa (*Randomize*), dan visualizer baris kode live.

### 2. 📚 Modul 2: Perpustakaan Kampus (*Searching - Binary vs Linear Search*)
* **Studi Kasus:** Menemukan buku referensi (*contoh: 005.1 - Dasar Pemrograman*) di antara deretan buku berkode Dewey Decimal.
* **Fitur Interaktif:**
  * Abstraksi: Fokus pada Kode Rak & Judul, mengabaikan jumlah halaman & harga buku.
  * Dekomposisi: 4 tingkat hierarki pencarian (Gedung $\rightarrow$ Lantai $\rightarrow$ Rak $\rightarrow$ Buku).
  * Pengenalan Pola: Memahami pola keterurutan dan eliminasi separuh rak (*Binary Elimination*).
  * Visualizer Algoritma: Membandingkan kecepatan **Binary Search** (bagi dua) vs **Linear Search** (satu-satu) langsung di rak buku interaktif.

---

## 🛠️ Teknologi yang Digunakan
* **HTML5 & CSS3** (Flexbox, Grid, CSS Variables, Keyframes Animation)
* **Vanilla JavaScript** (ES6+ State Machine & Async Search)
* **Web Audio API** (Sound Effect synthesizer tanpa file audio eksternal)
* **Google Fonts** (Plus Jakarta Sans & Fira Code)

---

## 💻 Cara Menjalankan Secara Lokal
Cukup *clone* repository ini dan buka file `index.html` di browser Anda:

```bash
git clone https://github.com/andrewtliem/computationalThinkingExample.git
cd computationalThinkingExample
open index.html # di macOS
# atau start index.html di Windows
```

---

## 👨‍🏫 Lisensi & Penggunaan
Proyek ini bebas digunakan untuk keperluan edukasi, pengajaran di kelas, presentasi kuliah, dan lokakarya (*workshop*).
