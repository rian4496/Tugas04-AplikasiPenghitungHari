# Tugas04-AplikasiPenghitungHari
 Tugas04-M. Rian Gunadi-2210010497

![gambar](https://github.com/user-attachments/assets/22d603e8-f380-4546-ba4c-48a790c3d2e0)

# Aplikasi Perhitungan Hari

Aplikasi ini merupakan aplikasi berbasis Java Swing yang berfungsi untuk menghitung jumlah hari dalam bulan tertentu, mengecek apakah tahun tersebut merupakan tahun kabisat, serta menampilkan selisih hari antara dua tanggal yang dipilih.

## Fitur

- Menampilkan jumlah hari dalam bulan tertentu berdasarkan tahun yang dipilih.
- Menentukan apakah tahun yang dipilih merupakan tahun kabisat atau bukan.
- Menampilkan hari pertama dan terakhir dari bulan yang dipilih.
- Menghitung selisih hari antara dua tanggal yang dipilih.

## Teknologi yang Digunakan

- **Java Swing**: Untuk antarmuka pengguna grafis.
- **JCalendar**: Untuk memilih tanggal dengan mudah menggunakan komponen kalender.
- **JDateChooser**: Untuk pemilihan tanggal kedua yang akan digunakan untuk menghitung selisih hari.

## Struktur Kode

- **`AplikasiPerhitunganHari`**: Kelas utama yang mengelola tampilan dan logika aplikasi.
  - **`syncFromCalendar()`**: Sinkronisasi tanggal yang dipilih di `JCalendar` dengan `cbbBulan` dan `spTahun`.
  - **`syncToCalendar()`**: Sinkronisasi pilihan bulan dan tahun dari `cbbBulan` dan `spTahun` ke `JCalendar`.
  - **`hitungHari()`**: Menghitung jumlah hari dalam bulan dan tahun yang dipilih, serta selisih hari antara dua tanggal.

## Cara Menggunakan

1. Pilih bulan dan tahun melalui `cbbBulan` dan `spTahun`.
2. Klik tombol **Hitung** untuk melihat jumlah hari dalam bulan tersebut dan informasi tambahan.
3. Pilih tanggal pada `JCalendar` dan `JDateChooser`, lalu klik **Hitung** untuk melihat selisih hari antara kedua tanggal.

## Contoh Hasil

Hasil akan ditampilkan di area `txtHasil`, termasuk informasi berikut:
- Jumlah hari dalam bulan dan tahun yang dipilih.
- Status apakah tahun tersebut kabisat atau bukan.
- Hari pertama dan terakhir dalam bulan yang dipilih.
- Selisih hari antara tanggal yang dipilih pada `JCalendar` dan `JDateChooser`.
