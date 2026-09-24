```markdown
# Praktikum 1: HTML Dasar

Repositori ini dibuat untuk mendokumentasikan hasil pengerjaan Praktikum 1 mata kuliah Pemrograman Web[cite: 1]. Fokus praktikum ini membahas pengenalan struktur dokumen web, implementasi berbagai tag teks, pengelolaan gambar, navigasi hyperlink, hingga pengelompokan informasi menggunakan list[cite: 1].

---

## Struktur Berkas Proyek

```text
Lab1Web/
├── index.html        # halaman pertama
├── halaman2.html      # Halaman profil gabungan
├── README.md         # Dokumentasi pengerjaan praktikum
└── images/
    └── profil.jpg    # Aset gambar/foto profil

```

---

## Penjelasan Kode Program

### 1. `index.html` (Eksplorasi Tag Dasar HTML)

File ini memuat eksperimen berbagai tag dasar untuk memahami fungsi dan penampilannya pada browser:

* **Deklarasi dan Kerangka Dasar:** Dokumen diawali dengan deklarasi `<!DOCTYPE html>` untuk memastikan browser merender halaman dengan standar HTML5. Elemen `<html>` bertindak sebagai pembungkus utama, `<head>` memuat judul halaman pada tab browser (`<title>Praktikum HTML Dasar</title>`), dan `<body>` menampung konten visual.


* **Hierarki Judul (Heading):** Menggunakan `<h1>Belajar Dasar HTML</h1>` sebagai penanda judul utama konten. Subjudul diatur dengan tag `<h2>` untuk mengelompokkan materi, seperti pembahasan paragraf, keahlian, dan tahapan belajar.


* **Pengelolaan Gambar (`<img>`):** Gambar disisipkan melalui atribut `src="images/profil.jpg"`. Ukuran lebarnya dibatasi menggunakan `width="200"`, dilengkapi atribut `alt="Foto profil mahasiswa"` sebagai teks pengganti jika berkas gagal dimuat, serta `title="Foto Profil Mahasiswa"` untuk menampilkan tooltip saat kursor diarahkan ke gambar.


* **Daftar / List:**
* **Unordered List (`<ul>` & `<li>`):** Menampilkan daftar keahlian (*HTML, CSS, JavaScript*) memakai bullet tanpa penomoran urut.


* **Ordered List (`<ol>` & `<li>`):** Menampilkan langkah pembelajaran (*Mempelajari struktur HTML* hingga *Menguji halaman pada browser*) dengan nomor urut otomatis 1 sampai 4.




* **Paragraf dan Format Teks:**
* Paragraf dibungkus menggunakan tag `<p>` untuk membentuk blok tulisan yang rapi.


* `<b>` digunakan untuk mencetak tebal teks secara visual.


* `<strong>` memberi penekanan semantik penting pada teks *bahasa markup*.


* `<i>` memformat teks menjadi miring untuk istilah asing atau penekanan bacaan.


* `<sub>` dan `<sup>` dimanfaatkan dalam penulisan indeks bawah dan pangkat, seperti pada rumus air $H_2O$ serta notasi matematika $x^2$.




* **Navigasi dan Hyperlink (`<nav>` & `<a>`):**
* Tautan internal: Menghubungkan berkas di dalam folder kerja yang sama, yaitu `index.html` dan `halaman2.html`.


* Tautan eksternal: Mengarahkan pengguna langsung ke laman luar melalui tautan absolut `https://www.google.com`.


* Garis horizontal `<hr>` diletakkan sebagai pembatas visual antarkelompok konten.




* **Komentar (`<!-- ... -->`):** Berfungsi sebagai catatan dokumentasi untuk mempermudah pembacaan struktur kode tanpa ikut dieksekusi atau tampil di halaman web.



---

### 2. `halaman2.html` (Profil Mahasiswa / Halaman Gabungan)

File ini menggabungkan berbagai elemen dasar yang telah dipelajari menjadi satu halaman profil yang rapi dan terstruktur:

* **Navigasi Halaman:** Menu diletakkan pada bagian atas dengan pembungkus tag semantik `<nav>`, menyediakan tautan balik menuju `index.html` (Beranda) dan halaman aktif `halaman2.html`. Pemisah horizontal `<hr>` ditambahkan di bawah menu navigasi.


* **Header Profil:** Menampilkan judul utama `<h1>Profil Mahasiswa</h1>` dan menyematkan foto identitas berukuran proporsional `width="200"`.


* **Bagian Data Diri:** Disusun menggunakan subjudul `<h2>Data Diri</h2>` yang diikuti paragraf `<p>` berisi informasi Nama, Program Studi (Teknik Informatika), serta ringkasan motivasi belajar web.


* **Rangkuman Keahlian dan Target:**
* Tag `<ul>` digunakan untuk menampilkan ringkasan kemampuan teknis yang sedang dipelajari (*HTML, CSS, JavaScript*).


* Tag `<ol>` menyusun target belajar secara bertahap dan sistematis dari poin 1 hingga 3.





```

```
