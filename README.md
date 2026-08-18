# 🧩 Lab Berpikir Komputasional (Computational Thinking Lab)

Media pembelajaran interaktif berbasis web untuk memahami **4 Pilar Berpikir Komputasional (*Computational Thinking*)**:
1. **Abstraksi (*Abstraction*)**
2. **Dekomposisi (*Decomposition*)**
3. **Pengenalan Pola (*Pattern Recognition*)**
4. **Perancangan Algoritma (*Algorithmic Thinking*)**
---

## 🚀 Live Demo Website
Akses simulasi interaktif secara online di:  
👉 **[https://andrewtliem.github.io/computationalThinkingExample/](https://andrewtliem.github.io/computationalThinkingExample/)**

---

## 🎯 Modul Pembelajaran Interaktif

### 1. 👥 Modul 1: Barisan Siswa (*Sorting - Bubble Sort*)
* **Studi Kasus:** Mengurutkan barisan siswa dari yang paling pendek ke paling tinggi dengan atribut: Nama, Tinggi Badan, Berat Badan, dan Jenis Kelamin.
* **Fitur Interaktif:**
  * **Abstraksi:** Memilih data penting vs data yang diabaikan (berat badan & gender) secara visual.
  * **Dekomposisi:** Memecah barisan menjadi perbandingan 2 orang bersebelahan.
  * **Pengenalan Pola:** Menerapkan aturan kondisi `IF (Tinggi Kiri > Tinggi Kanan) THEN TUKAR`.
  * **Visualizer Algoritma:** Simulasi Bubble Sort *step-by-step* & otomatis, pengatur kecepatan animasi, generator acak siswa (*Randomize*), dan *live code highlighter*.

### 2. 📚 Modul 2: Perpustakaan Kampus (*Searching - Binary vs Linear Search*)
* **Studi Kasus:** Menemukan buku referensi (*contoh: 005.1 - Dasar Pemrograman*) di antara deretan buku berkode Dewey Decimal.
* **Fitur Interaktif:**
  * **Abstraksi:** Fokus pada Kode Rak & Judul, mengabaikan jumlah halaman & harga buku.
  * **Dekomposisi:** 4 tingkat hierarki pencarian (Gedung &rarr; Lantai/Kategori &rarr; Rak &rarr; Buku).
  * **Pengenalan Pola:** Memahami pola keterurutan dan eliminasi separuh rak (*Binary Elimination*).
  * **Visualizer Algoritma:** Membandingkan efisiensi **Binary Search** (bagi dua) vs **Linear Search** (satu-satu) langsung di rak buku interaktif.

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
