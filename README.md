![Forest Parallax](img/Screenshot%202026-02-05%20090654.png)
# 🌲 Forest Parallax Page with GSAP

Project ini merupakan implementasi **parallax scrolling design** menggunakan **GSAP (GreenSock Animation Platform)** dengan tema **Forest**. Halaman ini dirancang untuk memberikan pengalaman visual yang imersif, seolah pengguna sedang berjalan menyusuri hutan dengan kedalaman dan pergerakan yang natural saat scroll.

---

## ✨ Konsep Parallax Design

**Parallax design** adalah teknik visual di mana beberapa layer bergerak dengan kecepatan berbeda ketika pengguna melakukan scroll. Perbedaan kecepatan ini menciptakan ilusi **kedalaman (depth)** dan ruang 3D pada halaman 2D.

Pada project ini, parallax digunakan untuk:
- Memberikan kesan hutan yang luas dan hidup
- Memisahkan elemen visual berdasarkan kedalaman
- Mengarahkan fokus pengguna secara bertahap

---

## 🌲 Tema Forest

Tema forest dipilih karena sangat cocok untuk eksplorasi efek parallax:

- **Background**  
  Langit, kabut, dan siluet pepohonan jauh  
- **Midground**  
  Pepohonan utama dan elemen hutan  
- **Foreground**  
  Daun, semak, dan elemen dekat yang bergerak lebih cepat  

Perbedaan kecepatan antar layer menciptakan efek seolah pengguna masuk lebih dalam ke hutan.

---

## 🚀 Kenapa Menggunakan GSAP?

GSAP digunakan karena:
- Performa animasi sangat halus dan stabil
- Kontrol animasi yang presisi melalui timeline
- Integrasi yang kuat dengan scroll menggunakan `ScrollTrigger`
- Cocok untuk animasi kompleks dan interaktif

GSAP memungkinkan parallax tidak hanya berbasis CSS, tetapi berbasis logika dan posisi scroll pengguna.

---

## 🧩 Struktur Layer Parallax

Struktur umum layer parallax pada halaman ini:
Forest Scene
│
├── Background Layer (gerak paling lambat)
│ └── Sky, fog, far trees
│
├── Midground Layer
│ └── Main forest trees
│
└── Foreground Layer (gerak paling cepat)
└── Leaves, branches, plants


Layer yang lebih dekat ke pengguna bergerak lebih cepat untuk menciptakan ilusi kedalaman.

---

## 🌀 Cara Kerja Parallax dengan GSAP

1. Setiap layer memiliki class atau ID sendiri
2. GSAP mengatur transformasi posisi (biasanya sumbu Y)
3. `ScrollTrigger` menghubungkan animasi dengan scroll
4. Background bergerak lebih lambat dibanding foreground

Contoh konsep pergerakan:
- Background: `y: -50`
- Midground: `y: -150`
- Foreground: `y: -300`

---

## 🎯 Tujuan Project

- Mempelajari parallax scrolling modern
- Eksplorasi GSAP dan ScrollTrigger
- Membuat landing page yang sinematik dan interaktif
- Meningkatkan pengalaman visual pengguna

---

## 🛠 Teknologi yang Digunakan

- HTML5
- CSS3
- JavaScript
- GSAP
- GSAP ScrollTrigger

---

## 📌 Catatan

Project ini lebih optimal jika dibuka melalui desktop atau layar besar agar efek parallax dapat dirasakan secara maksimal.

---

## 📄 License

MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy  
of this software and associated documentation files (the "Software"), to deal  
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  
copies of the Software, and to permit persons to whom the Software is  
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all  
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR  
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,  
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE  
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER  
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,  
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE  
SOFTWARE.
