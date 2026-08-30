# Laporan Praktikum Minggu 1

## Hasil Mini Assignment
![Screenshot Aplikasi](screenshots/screenshot.jpeg)

## Refleksi Mandiri

### 1. Kapan native lebih tepat dipilih daripada cross-platform?
Aplikasi native lebih cocok dipilih ketika ingin membuat aplikasi yang butuh performa super berat, contohnya game 3D atau aplikasi edit video. Selain itu, native juga wajib dipakai kalau aplikasi kita butuh akses penuh ke fitur hardware bawaan HP yang paling baru, karena biasanya framework cross-platform belum mendukung fitur tersebut secara langsung.

### 2. Bagaimana perubahan state berhubungan dengan widget tree dan UI deklaratif?
Di Flutter yang pakai sistem UI deklaratif, tampilan layar itu mengikuti data atau keadaan (state) yang ada sekarang. Jadi, cocok data atau state-nya berubah, Flutter tidak akan mengubah tampilan layarnya satu per satu secara manual. Sistem akan otomatis merender ulang (rebuild) bagian widget tree yang datanya berubah tadi supaya layarnya langsung ikut terupdate.

### 3. Mengapa commit kecil dengan pesan jelas bermanfaat bagi pekerjaan tim dan portfolio?
Commit yang kecil dan rutin mempermudah saat melacak perubahan kode jika tiba-tiba terfapat bug atau error, jadi tidak akan mengacaukan kerjaan orang lain di tim. Buat portfolio, riwayat commit yang rapi dan pesannya jelas juga jadi bukti ke dosen atau rekruter kalau kita paham cara kerja manajemen proyek yang baik pakai Git.
