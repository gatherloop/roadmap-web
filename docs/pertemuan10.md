# Intro Database MySQL

## Latar Belakang

Setelah kita seru-seruan di pertemuan sebelumnya, kita udah punya bekal yang lumayan lengkap nih buat bikin aplikasi web. Kita udah ngerti gimana Javascript bisa bikin halaman web jadi hidup, terus pake DOM kita bisa mainin elemen-elemen di halaman itu. Kita juga udah belajar Local Storage buat nyimpen data kecil-kecilan di browser pengguna, jadi aplikasi kita punya sedikit "ingatan" biar nggak ngulang dari nol tiap browser ditutup.

Nah, di pertemuan terakhir, kita udah loncat lebih jauh lagi. Kita udah ngulik Node.js sebagai backend atau "otak" di balik layar aplikasi kita. Kita belajar pake NPM buat nambahin fitur-fitur keren, dan yang paling penting, kita udah kenalan sama Express.js. Dengan Express, kita bisa bikin web server sendiri yang siap melayani permintaan dari browser. Kita juga udah paham tuh berbagai macam HTTP Method kayak GET, POST, PUT, DELETE, yang itu adalah cara kita berkomunikasi antara browser dan server, misalnya browser minta data (GET) atau ngirim data baru (POST). Jadi, sekarang kita udah bisa bikin server yang bisa ngasih respon dinamis ke browser dan juga nerima data dari browser.

Tapi, ada satu PR besar nih: data yang kita olah di server itu mau disimpan di mana biar permanen dan bisa diakses bareng-bareng sama banyak pengguna? Kalo cuma pake Local Storage, itu terbatas banget, cuma di satu browser aja, dan buat data yang kompleks jelas nggak cocok. Bayangin kalo kita bikin toko online, data produk, data pelanggan, atau riwayat transaksi itu kan jumlahnya banyak banget dan harus tersimpan rapi, terus bisa diakses oleh siapa aja yang buka toko kita. Nah, di sinilah peran Database MySQL jadi krusial. MySQL ini ibarat "gudang" atau "lemari arsip digital" yang super besar, rapi, dan terstruktur di server kita. Semua data penting aplikasi kita bakal disimpan di sana secara aman, sehingga suatu saat nanti web server kita yang udah kita bangun pake Node.js dan Express bisa dengan mudah ngambil data dari gudang ini, atau nyimpen data baru ke sana, kapanpun dibutuhkan oleh user yang berbeda-beda. Ini ngebikin aplikasi kita jadi lebih robust, bisa ngelola data dalam skala besar, dan tentunya bisa dinikmati oleh banyak orang.

## Tujuan

Materi ini dirancang untuk ngajak kamu lebih dalam lagi ke dunia manajemen data aplikasi web. Kita akan fokus pada Database MySQL sebagai sistem penyimpanan data utama. Tujuannya adalah biar kamu paham betul kenapa database itu penting, terutama setelah kita punya backend pake Node.js dan Express. Kamu akan belajar konsep dasar MySQL, gimana caranya bikin tabel buat nyimpen data, dan yang paling penting, kamu bisa melakukan operasi dasar kayak nambahin data baru, ngambil data yang udah ada, ngubah data, sampai ngehapus data dari database pake perintah SQL. Kita akan fokus pada pemahaman dan penguasaan MySQL secara mandiri dulu. Dengan menguasai materi ini, kamu akan mampu mengelola data secara terstruktur di dalam database, sebagai fondasi penting sebelum kita benar-benar menyambungkannya ke server di pertemuan selanjutnya. Ini akan jadi langkah besar menuju pembangunan aplikasi web yang datanya terkelola dengan baik dan siap dikembangkan lebih lanjut.


Berikut daftar topik yang bakal kita pelajari bareng:

- [Database MySQL Dasar](https://gilacoding.com/read/belajar-dasar-dasar-database-mysql-dengan-cmd)

>>>>>>> 814194c507d483c9e3302a4d77a754159f1f2542

