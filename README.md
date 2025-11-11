# 🧭 H1D023043_Tugas6

---

## 📁 Struktur Folder

```
lib/
├── main.dart
└── ui/
    ├── form_data.dart
    └── tampil_data.dart
```

---

## 🧩 Deskripsi Proyek

Aplikasi ini memiliki dua tampilan utama:

1. **Form Data (`form_data.dart`)**
   Berisi form input untuk memasukkan:

   * Nama
   * NIM
   * Tahun Lahir

   Setelah pengguna mengisi dan menekan tombol **“Simpan Data”**, data akan dikirim ke halaman berikutnya.

2. **Tampil Data (`tampil_data.dart`)**
   Menampilkan hasil dari data yang telah diinput pada form sebelumnya.

---

## 🔄 Proses Passing Data

1. Pengguna mengisi form di `form_data.dart`.
2. Nilai input disimpan menggunakan **TextEditingController**.
3. Data dikirim ke halaman hasil dengan **Navigator.push()**, dan diteruskan melalui **parameter konstruktor** widget `TampilData`.
4. Halaman `tampil_data.dart` menerima data tersebut dan menampilkannya pada layar.

---

## 🖼️ Screenshot Tampilan

<p align="center">
  <img src="https://github.com/user-attachments/assets/530e7bb1-5246-41bc-9711-2f9db2028b72" alt="Tampilan Form" width="300" style="margin-right: 20px;"/>
  <img src="https://github.com/user-attachments/assets/704fb184-009c-4a53-be21-0a7841f66f7d" alt="Tampilan Hasil" width="300"/>
</p>

> 📷 **Keterangan:**
>
> * **Tampilan Form:** Menampilkan halaman input dengan kolom teks (Nama, NIM, Tahun Lahir) dan tombol “Simpan Data” serta “Reset Form”.
> * **Tampilan Hasil:** Menampilkan hasil input berupa teks Nama, NIM, dan Tahun Lahir yang telah dimasukkan pengguna serta tombol “Kembali ke Form”.

---

## 📘 Kesimpulan

Proyek ini menunjukkan cara sederhana melakukan **passing data antar halaman** di Flutter dengan memanfaatkan:

* **TextEditingController** untuk menangkap input pengguna.
* **Navigator.push()** dengan **parameter konstruktor** untuk mengirim data antar widget.

---

**Nama:** Aisyah Syifa Karima
**NIM:** H1D023043
**Tugas:** 6 — Praktikum Pemrograman Mobile Flutter

---
