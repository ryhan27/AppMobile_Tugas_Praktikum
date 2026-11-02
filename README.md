# Aplikasi Profil Flutter

Proyek pembuatan antarmuka aplikasi profil menggunakan framework Flutter. Praktikum ini difokuskan pada manajemen tata letak (*layouting*), modularisasi komponen (*Extract Widget*), serta penyelesaian masalah (*debugging*) pada kode.

- **Nama:** Muhamad Rayhan Ramadhansyah
- **NIM:** 1124160086
- **Kelas:** TI24-P SE 2
- **Prodi:** Teknik Informatika
- **Konsentrasi:** Software Engineering

---

## Riwayat Commit

### Hari 1
* **Commit 1: `feat: create basic profile page structure with avatar and text`**
  * Menginisialisasi halaman profil utama menggunakan struktur `Scaffold` dan `AppBar`.
  * Menempatkan elemen dasar seperti foto profil dan teks identitas pengguna.
  * Memperbaiki kesalahan penggunaan dimensi pada `SizedBox` (mengubah `width` menjadi `height`).
* **Commit 2: `refactor: extract avatar and info into custom widgets`**
  * Menerapkan prinsip modularitas dengan memecah widget `Column` yang panjang.
  * Mengekstrak bagian foto dan informasi pengguna menjadi kelas widget mandiri (`ProfileAvatar` dan `ProfileInfo`).

### Hari 2
* **Commit 1: `feat: add profile statistics row`**
  * Menyisipkan komponen baris yang menampilkan indikator statistik (Proyek, Followers, Following).
  * Mengatur perataan letak secara horizontal menggunakan widget `Row`.
  * Melakukan perbaikan tipe data pada argumen angka (*integer* menjadi *string*).
* **Commit 2: `refactor: extract statistics UI into ProfileStats and StatItem widgets`**
  * Mengubah blok antarmuka statistik menjadi komponen yang *reusable*.
  * Membuat kelas `ProfileStats` untuk kerangka luar dan `StatItem` untuk masing-masing item angka dan label.

### Hari 3
* **Commit 1: `feat: add scrollable experience list using ListView.builder`**
  * Merancang daftar riwayat proyek dan pengalaman kerja.
  * Mengimplementasikan `ListView.builder` yang dibungkus dengan widget `Expanded` untuk mencegah masalah *render overflow*.
  * Memperbaiki sintaks *array* data yang kehilangan tanda koma.
* **Commit 2: `refactor: extract list tile into ExperienceCard widget and apply styling`**
  * Memisahkan desain setiap baris daftar ke dalam widget berbentuk kartu.
  * Menambahkan gaya visual, ikon, dan efek bayangan (*elevation*) pada komponen `ExperienceCard`.

### Hari 4
* **Commit 1: `style: adjust padding and spacing for profile components`**
  * Mengoptimalkan jarak dan margin antar komponen UI secara keseluruhan.
  * Menyesuaikan proporsi ruang kosong agar tampilan aplikasi lebih teratur dan profesional.
* **Commit 2: `feat: add static edit button with snackbar notification`**
  * Mengintegrasikan tombol aksi "Edit Profil" pada layar utama.
  * Menyematkan fungsi interaksi statis berupa pesan *pop-up* (`SnackBar`) di bagian bawah layar saat tombol ditekan.
  * Menyelesaikan dan merapikan dokumentasi proyek pada file `README.md`.
