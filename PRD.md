Berikut adalah Product Requirements Document (PRD) untuk pengembangan template website perumahan sesuai dengan kriteria tugas Anda.

---

# Product Requirements Document (PRD): Website Perumahan

## 1. Ringkasan Proyek

Proyek ini bertujuan untuk membangun sebuah website profil perumahan yang berfungsi sebagai media informasi bagi calon pembeli dan manajemen inventaris properti. Website dirancang dengan pendekatan desain minimalis, elegan, dan profesional menggunakan HTML, CSS murni, dan framework Bootstrap tanpa penggunaan JavaScript.

## 2. Sasaran Pengguna

* **Calon Pembeli:** Mencari informasi unit rumah, fasilitas, dan harga.
* **Admin/Staf:** Mengelola data unit perumahan dan memantau formulir minat pembeli.

## 3. Fitur Utama (Functional Requirements)

Website ini akan terdiri dari tiga halaman utama dengan komponen wajib sebagai berikut:

### A. Landing Page (Informasi Publik)

* **Header:** Navigasi menuju bagian-bagian website dan link eksternal.
* **Hero Section:** Gambar utama perumahan dengan *heading* yang menarik.
* **Deskripsi (Paragraf):** Informasi mendalam mengenai keunggulan lokasi dan spesifikasi bangunan.
* **Galeri Unit:** Menampilkan gambar-gambar tipe rumah yang tersedia.
* **Footer:** Informasi hak cipta, alamat kantor di Makassar, dan tautan sosial media.

### B. Halaman Login

* **Formulir Otentikasi:** Input teks untuk *username* dan input *password* untuk akses staf.
* **Tombol Submit:** Bergaya minimalis menggunakan kelas Bootstrap.

### C. Halaman Manajemen (Admin Dashboard)

* **Tabel Data Unit:** Menampilkan daftar unit, tipe, status (Tersedia/Terjual), dan harga dalam format tabel yang rapi.
* **Formulir Input Data:** Formulir untuk menambah data unit baru atau formulir kontak bagi calon pembeli yang ingin memesan jadwal survei.

## 4. Struktur Navigasi (Sitemap)

* **Beranda (Index):** Landing Page utama.
* **Login:** Pintu masuk ke area manajemen.
* **Dashboard/Admin:** Halaman yang memuat tabel inventaris dan formulir input.

## 5. Spesifikasi Teknis & Desain

| Komponen | Spesifikasi |
| --- | --- |
| **Teknologi** | HTML5, CSS3, Bootstrap 5.x |
| **Scripting** | **Tanpa JavaScript** (Interaksi hanya menggunakan CSS/Bootstrap class) |
| **Palet Warna** | Dominan Hitam, Abu-abu tua, dan Putih (Minimalis/Elegan) |
| **Tipografi** | Sans-serif yang bersih (seperti Inter atau Roboto) |
| **Elemen Wajib** | Paragraph, Header, Footer, Heading, Gambar, Link, Form, Tabel |

---

## 6. Penjelasan Template Website

Template ini dirancang untuk memberikan kesan eksklusif pada proyek hunian.

1. **Landing Page** difokuskan pada aspek visual melalui penggunaan tag `<img>` berkualitas tinggi dan tata letak grid Bootstrap agar responsif.
2. **Halaman Dashboard** menggunakan komponen `<table class="table table-hover">` untuk menyajikan data unit secara terstruktur, memudahkan admin dalam membaca status ketersediaan stok secara cepat.
3. **Formulir** dirancang dengan validasi bawaan HTML5 (seperti `required`) untuk memastikan data terisi meskipun tanpa bantuan JavaScript.

## 7. Instruksi Pengunggahan ke GitHub

Setelah Anda menyelesaikan kode program:

1. Buat repositori baru di GitHub dengan nama (contoh): `uts-pemrograman-web-perumahan`.
2. Unggah file `index.html`, `login.html`, `admin.html`, dan folder `css/`.
3. Sertakan folder `img/` yang berisi tangkapan layar (*screenshot*) dari ketiga halaman tersebut.
4. Pastikan file `README.md` berisi deskripsi singkat proyek ini.

---

**Catatan Implementasi:**
Karena batasan "Tanpa JavaScript", Anda dapat memanfaatkan fitur-fitur CSS untuk interaksi sederhana seperti *hover effects* pada tombol dan transisi pada link navigasi untuk mempertahankan kesan elegan.
