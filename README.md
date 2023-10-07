# LMS-laravel

## Summary

Buatlah aplikasi Course Detail LMS menggunakan Vue dan back-end menggunakan laravel. Dalam aplikasi ini terdapat tiga kategori course yaitu: `Lesson`, `Exam`, dan `Quiz`. User bisa mengakses mengakses halaman berdasarkan kategori, dan page hanya bisa terunlock apabila telah menyelesaikan lesson atau quiz sebelumnya.

## Competencies

- Vue
- Laravel

## Release 0

Buatlah sebuah halaman dengan path `/` yang menampilkan data course detail yang berkategori `Lesson`, `Quiz`, dan `Exam` secara berurut. Di setiap card, tambahkan button `Play Icon` jika belum terselesaikan dan `Checklist Icon` jika telah berhasil terselesaikan dan `Lock Button` untuk halaman yang belum bisa di akses.

![release-0](release-0.jpg)

## Release 1

Buatlah halaman lesson dengan path `/topic/:id` yang menampilkan materi yang akan di ajarkan. Tambahkan tombol `continue` untuk menyelesaikan lesson dan mengunlock halaman quiz selanjutnya 

![release-1](release-1.jpg)

## Release 2

Buatlah halaman quiz dengan path `/topic/:id/quiz/:id` yang menampilkan soal quiz dengan unlimited attempt untuk submit nilai.

![release-2](release-2.jpg)

## Release 3

Buatlah halaman exam dengan path `/topic/:id/exam/:id` yang menampilkan soal exam dengan batas waktu penyelesaian selama 20 menit dan nilai kkm sebesar 80. jika waktu timer telah habis, user tidak dapat submit. jawaban benar soal bisa lebih dari 1.

![release-3](release-3.jpt)
