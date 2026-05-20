# Laporan Hasil Praktikum: Final Project Aplikasi Berbasis Container

## Identitas Mahasiswa

- **Nama:** I Made Widnyana Putra
- **NIM:** 2415354030
- **Kelas/Rombel:** TRPL B
- **Tanggal Praktikum:** 20 Mei 2026

---

## Teknologi & Tools yang Digunakan

- **Sistem Operasi:** Mac OS Ventura
- **Containerization:** Docker & Docker Hub
- **Bahasa Pemrograman / Framework:** Node.js
- **Tools Lain:** VS Code, Git, hoppscotch.

---

## Langkah-Langkah Praktikum & Dokumentasi

### Langkah 1: Pengujian Docker Compose, Volume, Network, Container

1. hasil membuat volume
img\Screenshot 2026-05-20 153552.png

2. hasil membuat network
img\hasil membuat network.png

3. hasil membuat images
img\hasil membuat images .png

4. hasil membuat container
img\pengujian container.png



### Langkah 2: ⁠⁠Pengujian Endpoint -> Request dan Response (Browser, Postman

1. uji post
img\hasil uji post.png

2. uji get
img\uji get.png

3. uji delete
img\uji delete.png

### Langkah 3: ⁠⁠Pengujian upload ke Docker Hub

1. uji upload docker hub
img\uji uploud dockerhub.png



---

## Kesimpulan

Hasil Praktikum
Praktikum Final Project arsitektur berbasis container ini berhasil diselesaikan dengan baik. Seluruh service mulai dari backend Node.js hingga database MySQL 8 mampu saling berkomunikasi di dalam satu isolasi jaringan (Bridge Network) secara persisten (Volume). Image aplikasi juga berhasil didistribusikan ke Docker Hub.

Kendala & Solusi
Kendala Autentikasi Docker Hub: Sempat terjadi error authorization failed karena salah menuliskan target username tujuan saat melakukan docker tag.

Solusi: Menyelaraskan nama tag image agar sama persis dengan username akun aktif yang teridentifikasi saat docker login yaitu aditalexander17.

Kendala Protokol pada Hoppscotch: Terjadi Network Error saat melakukan pengujian endpoint.

Solusi: Memperbaiki kesalahan ketik (typo) pada URL di Hoppscotch yang semula menggunakan double protokol https://http:// menjadi single protokol lokal yang valid yaitu http://localhost:3000/users.
