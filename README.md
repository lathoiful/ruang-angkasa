# Penjelajah Ruang Angkasa

Penjelajah Ruang Angkasa adalah game arcade 2D berbasis HTML5 Canvas dan JavaScript. Pemain mengendalikan pesawat luar angkasa untuk bertahan dari serangan asteroid dan musuh, mengumpulkan power-up, serta mencapai skor setinggi mungkin.

## Fitur Utama

- Gameplay real-time berbasis Canvas
- Sistem skor, nyawa, dan level
- Musuh dan asteroid dengan tingkat kesulitan meningkat
- Power-up dengan efek khusus (tembakan cepat dan tembakan ganda)
- Efek visual seperti ledakan dan partikel
- Sistem pause dan game over
- Kontrol keyboard dan dukungan touch untuk perangkat mobile
- Tampilan UI responsif

## Teknologi yang Digunakan

- HTML5
- CSS3
- JavaScript (Vanilla)
- HTML5 Canvas API

## Cara Menjalankan

1. Simpan seluruh kode ke dalam satu file bernama `index.html`
2. Buka file tersebut menggunakan browser modern (Chrome, Firefox, Edge)
3. Game akan langsung bisa dimainkan tanpa instalasi tambahan

## Kontrol Permainan

### Keyboard
- Panah Kiri / Kanan atau A / D : Menggerakkan pesawat
- Space : Menembak
- P : Pause / Lanjutkan permainan

### Mobile
- Geser layar ke kiri atau kanan untuk menggerakkan pesawat
- Lepas sentuhan untuk menembak

## Mekanisme Permainan

- Pemain memulai dengan 3 nyawa
- Musuh memberikan skor 100 poin
- Asteroid memberikan skor 50 poin
- Setiap 1000 poin, level akan meningkat
- Level yang lebih tinggi meningkatkan kecepatan dan jumlah musuh
- Game berakhir saat nyawa habis

## Power-Up

- RAPID  
  Memberikan tembakan cepat selama 10 detik

- DOUBLE  
  Memberikan dua tembakan sekaligus selama 10 detik

## Struktur Kode

- Canvas digunakan sebagai area utama permainan
- Loop permainan menggunakan `requestAnimationFrame`
- Sistem tabrakan menggunakan perhitungan rectangle dan circle
- Semua logika game berada dalam satu file untuk kemudahan pembelajaran

## Tujuan Proyek

Proyek ini dibuat sebagai latihan pengembangan game sederhana menggunakan JavaScript dan Canvas, sekaligus untuk memahami:
- Game loop
- Collision detection
- Manajemen state game
- Rendering grafis 2D

## Lisensi

Proyek ini bebas digunakan untuk keperluan belajar dan pengembangan pribadi.
