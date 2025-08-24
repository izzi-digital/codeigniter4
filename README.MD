<div align="center">
  <br />
  <h1 align="center">Qohwah CI4</h1>
</div>
<br>

<details>
  <summary>Daftar Isi</summary>
  <ol>
    <li><a href="#tentang-proyek">Tentang Proyek</a></li>
    <li><a href="#memulai">Memulai</a></li>
    <li><a href="#lisensi">Lisensi</a></li>
    <li><a href="#kontak">Kontak</a></li>
  </ol>
</details>

---

## Tentang Proyek

**Qohwah CI4** dirancang untuk memudahkan pembuatan aplikasi berbasis web dengan Codeigniter 4.

---

## Memulai

Untuk menjalankan salinan proyek ini di komputer lokal Anda, ikuti langkah-langkah sederhana berikut.

### Prasyarat

Pastikan Anda sudah menginstal perangkat lunak berikut:

- PHP (v8.1 atau lebih baru)
- Composer
- Server Web Lokal (seperti XAMPP, Laragon) dengan database MySQL.

### Instalasi

1.  **Clone repositori ini:**

    ```sh
    git clone https://github.com/izzi-digital/codeigniter4.git
    ```

    ```sh
    cd codeigniter4
    ```

2.  **Install dependensi Composer:**

    ```sh
    composer install
    ```

3.  **Konfigurasi Lingkungan:**

    - Salin file `.env.example` menjadi `.env`.
    - Salin file `.htaccess.example` menjadi `.htaccess`.
    - Buka Direktori public, dan salin file `.htaccess.public-example` menjadi `.htaccess`.
    - Buka server MySQL (bisa pakai phpMyAdmin), dan buatlah database dengan nama myinvito.
    - Atur koneksi database Anda:
      ```env
      database.default.hostname = localhost
      database.default.database = codeigniter4
      database.default.username = root
      database.default.password =
      database.default.DBDriver = MySQLi
      ```

4.  **Jalankan Migrasi Database:**
    Pastikan Anda sudah membuat database `codeigniter4` di server MySQL Anda. Lalu, jalankan perintah ini dari terminal untuk membuat semua tabel yang dibutuhkan:

    ```sh
    php spark migrate
    ```

5.  **Jalankan Server Development:**
    Anda dapat menjalankan aplikasi di `http://localhost/codeigniter4`.

---

## Lisensi

Didistribusikan di bawah Lisensi MIT. Lihat `LICENSE` untuk informasi lebih lanjut.

---

## Kontak

<p align="center">
  <a href="https://github.com/izzi-digital"><img src="https://img.shields.io/badge/GitHub-izzi--digital-0D335D?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>
<p align="center">
  <a href="https://www.youtube.com/@qohwah-id"><img src="https://img.shields.io/badge/YouTube-Qohwah%20ID-0D335D?style=for-the-badge&logo=youtube&logoColor=white" /></a>
</p>
<p align="center">
  <a href="https://www.tiktok.com/@qohwah_id"><img src="https://img.shields.io/badge/TikTok-@qohwah_id-0D335D?style=for-the-badge&logo=tiktok&logoColor=white" /></a>
</p>

---

<p align="center">
  <a href="https://ko-fi.com/izzidigi"><img src="https://img.shields.io/badge/Ko--fi-Support%20Me-0D335D?style=for-the-badge&logo=ko-fi&logoColor=white" /></a> 
  <a href="https://sociabuzz.com/qohwah"><img src="https://img.shields.io/badge/SociaBuzz-Support%20Me-0D335D?style=for-the-badge&logoColor=white" /></a> 
</p>

<p align="center">
  <a href="https://github.com/izzi-digital/myinvito-ci">
  <img src="https://img.shields.io/badge/MyInvito-000000?style=for-the-badge&logo=github&logoColor=white" /></a> 
</p>
