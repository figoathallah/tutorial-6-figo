Figo Athallah<br>
200653571<br>
Game Development

## Latihan Mandiri: Fitur Tambahan

Rincian fitur tambahan yang saya kerjakan untuk tutorial 6 ini sebagai berikut:

<h3>Stage Select</h3>

Tombol **LinkButton** "Stage Select" di lengkapi dengan pertama menginisalisasikan sebuah scene baru yang memiliki nama yang sama. Scene tersebut berisi screenshot dari Level 1 dan Level 2 beserta **LinkButton** teks di bawahnya, dan jika ditekan akan membawa kita ke level yang kita inginkan masing-masing. Saya menyederhanakan script untuk **LinkButton** agar cukup memiliki satu sinyal saja, sebab mekanisme tombol tersebut tidak jauh beda untuk tiap instance sehingga kita hanya mengandalkan parameter sceneName yang menjadi target scene. Selain itu, ditambahkan juga perintah reset counter nyawa agar kembali menjadi 3 saat game di-ulang.

<h3>Return to Main Menu</h3>

Scene game over ditambahkan tombol yang membawa kita kembali ke Main Menu, menggunakan mekanisme yang sama dengan **LinkButton** lainnya. Selain itu, tombol tersebut juga ditambahkan pada Win Screen agar kita tidak berdiam pada scene tersebut sampai kita memencet tombol exit.
