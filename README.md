# Pertemuan 10 - String dan Pengolahan Teks

**Nama:** Fridha Septiana  
**NIM:** 2225250068  
**Kelas:** 3E

## Tujuan

Mengolah dan menormalisasi data teks dengan string Python, meliputi membersihkan spasi, mengubah format huruf, memisahkan kata, menggabungkan teks, menghitung jumlah kata, dan membuat inisial nama mahasiswa menggunakan fungsi.

## Cara Menjalankan

1. Buka folder repositori Pertemuan 10 di VS Code.
2. Buka Terminal.
3. Jalankan perintah berikut:

```bash
python3 tugas/normalisasi_data_mahasiswa.py
```

4. Masukkan nama lengkap mahasiswa dan kode kelas sesuai permintaan program.
5. Program akan menampilkan nama yang sudah dinormalisasi, kode kelas, jumlah kata, dan inisial mahasiswa.

## Algoritma

1. Program menerima input nama lengkap mahasiswa dan kode kelas dalam bentuk string.
2. Nama dibersihkan menggunakan `strip()` untuk menghapus spasi di awal dan akhir, kemudian diubah ke format title case menggunakan `title()`.
3. Nama dipisahkan menjadi beberapa kata menggunakan `split()` untuk menghitung jumlah kata dan membuat inisial.
4. Inisial dibuat dengan mengambil huruf pertama dari setiap kata nama, kemudian menggabungkannya.
5. Kode kelas dibersihkan menggunakan `strip()`, diubah menjadi huruf kapital menggunakan `upper()`, dan dipisahkan menggunakan `split()`.
6. Kata-kata pada kode kelas digabungkan menggunakan `join()` dengan tanda hubung sebagai pemisah.
7. Program menampilkan nama bersih, kode kelas yang telah dinormalisasi, jumlah kata, dan inisial mahasiswa.

Program menggunakan tiga fungsi, yaitu `normalisasi_nama()`, `buat_inisial()`, dan `normalisasi_kode()`, agar setiap proses teks memiliki tanggung jawab yang jelas.

## Test Case

### Test Case 1

**Input Nama:** `aan hendrayana`  
**Input Kode:** `pmat a 2026`

**Hasil yang Diharapkan:**
- Nama bersih: Aan Hendrayana
- Kode kelas: PMAT-A-2026
- Jumlah kata: 2
- Inisial: AH

**Hasil Aktual:** Sesuai dengan hasil yang diharapkan setelah program dijalankan.  
**Status:** Berhasil

### Test Case 2

**Input Nama:** `fATHIYYAH mUTHMAINNAH`  
**Input Kode:** `kelas b`

**Hasil yang Diharapkan:**
- Nama bersih: Fathiyyah Muthmainnah
- Kode kelas: KELAS-B
- Jumlah kata: 2
- Inisial: FM

**Hasil Aktual:** Sesuai dengan hasil yang diharapkan setelah program dijalankan.  
**Status:** Berhasil

### Test Case 3

**Input Nama:** `BUDI`  
**Input Kode:** `pmtk 01`

**Hasil yang Diharapkan:**
- Nama bersih: Budi
- Kode kelas: PMTK-01
- Jumlah kata: 1
- Inisial: B

**Hasil Aktual:** Sesuai dengan hasil yang diharapkan setelah program dijalankan.  
**Status:** Berhasil

### Test Case 4

**Input Nama:** `siti nur aisyah`  
**Input Kode:** `kelas c`

**Hasil yang Diharapkan:**
- Nama bersih: Siti Nur Aisyah
- Kode kelas: KELAS-C
- Jumlah kata: 3
- Inisial: SNA

**Hasil Aktual:** Sesuai dengan hasil yang diharapkan setelah program dijalankan.  
**Status:** Berhasil

## Refleksi

Masalah teks yang ditemukan adalah penulisan nama dan kode kelas yang tidak konsisten, seperti penggunaan huruf kapital yang berbeda serta adanya spasi yang tidak diperlukan. Masalah tersebut diperbaiki menggunakan `strip()`, `title()`, `upper()`, `split()`, dan `join()`. Penggunaan fungsi membantu membuat program lebih terstruktur, mudah dipahami, dan dapat digunakan kembali. Melalui tugas ini, saya memahami cara mengolah string Python untuk menormalisasi data mahasiswa secara konsisten.

## Sumber Bantuan

- Bahan Ajar Pertemuan 10: String dan Pengolahan Teks.
- ChatGPT, digunakan sebagai bantuan untuk memahami penyusunan program dan dokumentasi.
