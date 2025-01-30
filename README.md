# Breakout Game with Vanilla JavaScript

Proyek ini adalah implementasi sederhana dari game klasik **Breakout** menggunakan **Vanilla JavaScript**, **HTML5 Canvas**, dan **CSS**. Tujuan utama proyek ini adalah untuk mempelajari dan mempraktikkan konsep dasar pemrograman game, seperti animasi, penanganan event, dan logika permainan, tanpa menggunakan library atau framework eksternal.

## Fitur Utama
- **Canvas Rendering**: Menggunakan HTML5 Canvas untuk menggambar elemen game seperti bola, paddle, dan bata.
- **Animasi**: Menggunakan `requestAnimationFrame` untuk membuat animasi yang halus.
- **Interaksi Pengguna**: Pemain dapat menggerakkan paddle menggunakan keyboard (tombol kiri dan kanan).
- **Logika Game**:
  - Bola memantul dari paddle, dinding, dan bata.
  - Bata akan hancur saat terkena bola, dan skor pemain akan bertambah.
  - Game akan direset jika bola jatuh ke bawah layar.
- **Skor**: Menampilkan skor pemain di layar.

## Daftar Tugas (TODOs)
1. **Create Canvas Context**  
   Membuat elemen `<canvas>` di HTML dan menginisialisasi context-nya di JavaScript.
2. **Create and Draw Ball**  
   Menggambar bola di canvas dengan properti seperti posisi (x, y), radius, dan warna.
3. **Create and Draw Paddle**  
   Menggambar paddle yang dapat digerakkan oleh pemain dengan properti seperti posisi (x, y), lebar, tinggi, dan warna.
4. **Create Bricks**  
   Membuat grid bata yang akan dihancurkan oleh bola. Setiap bata memiliki properti seperti posisi (x, y), lebar, tinggi, dan warna.
5. **Draw Score**  
   Menampilkan skor pemain di layar. Skor akan bertambah setiap kali bola menghancurkan bata.
6. **Add update() - Animate - requestAnimationFrame(cb)**  
   Membuat fungsi `update()` yang akan mengatur logika permainan dan animasi menggunakan `requestAnimationFrame`.
7. **Move Paddle**  
   Menambahkan logika untuk menggerakkan paddle ke kiri dan kanan berdasarkan input pengguna.
8. **Keyboard Event Handlers to Move Paddle**  
   Menambahkan event listener untuk tombol keyboard (kiri dan kanan) untuk mengontrol pergerakan paddle.
9. **Move Ball**  
   Menambahkan logika untuk menggerakkan bola di layar dengan kecepatan tertentu.
10. **Add Wall Boundaries**  
    Menambahkan deteksi tabrakan antara bola dengan dinding (atas, kiri, kanan) dan paddle. Bola akan memantul saat mengenai dinding atau paddle.
11. **Increase Score When Bricks Break**  
    Menambahkan logika untuk meningkatkan skor pemain setiap kali bola menghancurkan bata.
12. **Lose - Redraw Bricks, Reset Score**  
    Menambahkan logika untuk mengakhiri permainan jika bola jatuh ke bawah layar. Game akan direset dengan mengembalikan bata, mengatur ulang skor, dan mengembalikan bola ke posisi awal.

## Teknologi yang Digunakan
- **HTML5**: Untuk struktur dasar dan elemen `<canvas>`.
- **CSS**: Untuk styling dasar (opsional, tergantung kebutuhan).
- **JavaScript (Vanilla JS)**: Untuk logika permainan, animasi, dan interaksi pengguna.
