# Praktikum Pemrograman Web 1 - Modul 02

**Nama:** Ignatius Dadi Ahadiyat  
**NIM:** 20250910002  

---

## F. POST-TEST

### 1. Apa fungsi dari `git merge` dalam workflow Git?
`git merge` berfungsi untuk menggabungkan riwayat perubahan (*commit*) dari satu *branch* (cabang pengembangan) ke dalam *branch* lainnya (seperti *branch* utama `main`).

### 2. Jelaskan cara mengatasi konflik saat melakukan merge!
1. Cek file yang mengalami konflik dengan perintah `git status`.
2. Buka file tersebut di VS Code dan cari penanda konflik (`<<<<<<< HEAD`, `=======`, `>>>>>>>`).
3. Hapus penanda konflik dan sunting kode sesuai versi akhir yang diinginkan.
4. Simpan file, jalankan `git add .`, lalu akhiri dengan `git commit -m "Menyelesaikan merge conflict"`.

### 3. Langkah-langkah menambahkan file baru dan melakukan commit:
1. Tambahkan file ke *staging area* menggunakan perintah `git add <nama_file>` atau `git add .`
2. Periksa status file dengan `git status`.
3. Simpan perubahan secara permanen dengan perintah `git commit -m "Pesan commit"`.

---

## G. LATIHAN / TUGAS (Dokumentasi)

### 1. Pembuatan Repository, Commit, dan Push ke GitHub
Proses inisialisasi repository lokal, menambahkan file praktikum Modul 01, melakukan commit, dan mengirimkannya (*push*) ke repository GitHub (`pweb1`):

![Dokumentasi 1](dokumentasi/dokumentasi%201.png)
![Dokumentasi 2](dokumentasi/dokumentasi%202.png)
![Dokumentasi 3](dokumentasi/dokumentasi%203.png)

---

### 2. Rancangan Workflow Git (Branch Fitur Baru & Merge)
Alur kerja pembuatan branch baru (`fitur-profil`) dan penggabungannya kembali ke branch utama (`main`):

`[main]` ➔ `git checkout -b fitur-profil` ➔ *(Tambah File profil.html)* ➔ `git add & commit` ➔ `git checkout main` ➔ `git merge fitur-profil` ➔ `git push origin main`

![Dokumentasi 4](dokumentasi/dokumentasi%204.png)
![Dokumentasi 5](dokumentasi/dokumentasi%205.png)