
# Pertemuan 11 - Dictionary/Map

**Nama:** Fahrezi Sauqi Alghani

**NIM:** 2225250029

**Kelas:** 3E

## Tujuan

Mempelajari penggunaan dictionary Python untuk
menyimpan dan mengolah data pendidikan menggunakan
pasangan key-value.

## Materi

1. Dasar dictionary
2. Akses dictionary menggunakan key
3. Penggunaan get()
4. Menambah, mengubah, dan menghapus data
5. Iterasi dictionary
6. Dictionary bersarang
7. Fungsi dictionary

## Struktur Data

Program menggunakan NIM sebagai key utama.
Setiap mahasiswa memiliki value berupa dictionary
yang berisi nama, kelas, dan nilai.

## Cara Menjalankan

Jalankan latihan dengan perintah:

```bash
py latihan/01_dasar_dictionary.py
```

Jalankan program praktik dengan perintah:

```bash
py praktik/data_mahasiswa.py
```

## Test Case

| Pengujian | Hasil |
|---|---|
| Pencarian A003 | Data Citra ditemukan |
| Pencarian A999 | Data tidak ditemukan |
| Mengubah nilai A002 | Nilai menjadi 82 |
| Menambahkan A006 | Data Fajar berhasil ditambahkan |
| Menampilkan items() | Seluruh data tampil |
| Menghitung rata-rata | 83.50 |

## Refleksi

Kesalahan yang dapat terjadi adalah KeyError ketika
mengakses key yang tidak tersedia.

Cara memperbaikinya adalah menggunakan method
get() atau memeriksa key menggunakan operator in.

## Kesimpulan

Dictionary memudahkan penyimpanan dan pencarian
data berdasarkan key. Dictionary juga dapat
dikombinasikan dengan list dan fungsi.
