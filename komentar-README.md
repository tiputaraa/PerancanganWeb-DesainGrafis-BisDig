# Fitur Tampilkan Komentar

## Studi Kasus
Sebuah blog ingin menambahkan tombol "Tampilkan Komentar" agar komentar tidak langsung terlihat, tapi bisa muncul saat diklik.

## Penjelasan
File `komentar.html` menggunakan JavaScript untuk menyembunyikan dan menampilkan komentar secara dinamis. Saat tombol diklik, elemen `<div>` dengan id `comments` akan ditampilkan atau disembunyikan berdasarkan kondisi.

## Elemen Kunci
- Tombol HTML: `<button onclick="toggleComments()">`
- JavaScript: Fungsi `toggleComments()` mengatur properti `display` dari elemen komentar.
