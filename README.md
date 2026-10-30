# Laporan Proyek & Commit - Aplikasi Profil Flutter

**Nama:** Muhamad Rayhan Ramadhansyah  
**NIM:** 1124160086  
**Kelas:** TI24-P SE 2  
**Prodi:** Teknik Informatika  
**Konsentrasi:** Software Engineering  
**Tugas:** Praktikum 5 (Extract Widget & Debugging)

---

## Progres Pengerjaan: Hari 1 (Siang) — Extract Widget (Bagian 1)

### 1. Deskripsi Aktivitas
Pada sesi siang hari pertama, dilakukan proses *refactoring* dengan memecah komponen UI di dalam `Column` yang tadinya monolitik menjadi beberapa *Custom Widget* yang terpisah dan dapat digunakan kembali (*reusable widgets*):
* **`ProfileAvatar`**: Mengisolasi komponen foto profil (`CircleAvatar` dan `Icon`).
* **`ProfileInfo`**: Mengisolasi komponen teks nama dan jabatan, serta menerapkan teknik *parameter passing data* agar komponen bersifat dinamis.

### 2. Riwayat Commit (Conventional Commits)
* **Pesan Commit:** `refactor: extract avatar and info into custom widgets`[cite: 2]