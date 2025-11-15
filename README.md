# 🧩 Tugas Pertemuan 13 — Penerapan Login dengan Java Persistence API (JPA)

---

## 🚀 Fitur Utama

### 🔐 1. Login User
- Validasi username dan password berdasarkan data di tabel `akun`.
- Jika login berhasil, akan ditampilkan pesan:
  > "Selamat datang, username!"
- Jika login gagal, aplikasi menampilkan pesan kesalahan.

---

### 🧾 2. Register (Buat Akun)
- Pengguna dapat membuat akun baru melalui form registrasi.
- Data akun otomatis tersimpan ke database melalui JPA.
- Terdapat validasi untuk mencegah penggunaan **username yang sama**.

---

### 🔁 3. Lupa / Ubah Password
- Pengguna dapat mencari username yang terdaftar.
- Jika username ditemukan, field untuk memasukkan password baru akan muncul.
- Password diperbarui langsung ke database menggunakan **EntityManager**.

---

### 💾 4. Integrasi Database
- Menggunakan **PostgreSQL** sebagai DBMS.
- Konfigurasi koneksi diatur melalui **persistence.xml**.
- Menggunakan **EclipseLink JPA 2.2** sebagai ORM provider.

---
