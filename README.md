# petunjuk_instalasi

Lakukan pengintalan Xampp seperti penginstalan program pada umumnya. Xampp bisa diinstal di Drive mana saja baik C, D, E atau yang lainnya. Untuk tutorial ini saya instal di Drive C (lebih baik diinstal di Drive selain C untuk menghindari kehilangan data)
![slims 2](https://user-images.githubusercontent.com/88962175/129470616-c345bfd7-f054-4767-aad5-3cab94509080.png)

Tunggu sampai proses instalasi selesai, mungkin sekitar 5-10 menit. Setelah proses instal selesai, buka Xampp lalu klik start pada kotak merah yang saya tandai sehingga Apache dan MySQL aktif yang ditandai warna hijau. Jika muncul peringatan windows firewall klik saja Allow Access.
![image](https://user-images.githubusercontent.com/88962175/129470645-e224cf14-b9e7-4c19-a718-2bb574f3c701.png)



Instal SLiMS 9 Bulian

Ekstrak file SLiMS 9 Bulian dalam bentuk rar yang sudah didownload ke Directory C:\xampp\htdocs lalu rename nama foldernya terserah (dalam contoh ini saya rename menjadi Perpustakaan.
![image](https://user-images.githubusercontent.com/88962175/129470650-c5c3bcb3-3ddb-482b-badf-e31183ade9aa.png)



Langkah selanjutnya membuat Database. Buka browser lalu masukkan alamat localhost/phpmyadmin pada address bar. Kemudian klik Database lalu isi nama Database terserah (saya isi dengan Perpustakaan) lalu klik create. Perhatikan gambar dibawah ini.
![image](https://user-images.githubusercontent.com/88962175/129470654-7502895a-c2a3-4a2d-8023-574b476de320.png)



Setelah itu pilih Database yang sudah kita buat, lalu klik Privileges.
![image](https://user-images.githubusercontent.com/88962175/129470660-168931ec-7b9b-4000-bdd7-534434a7dbaf.png)



Klik add user account
![image](https://user-images.githubusercontent.com/88962175/129470664-9d058ac9-5057-4126-93b6-65d7feba5fbe.png)



Isi kolom yang tersedia
- Username diisi terserah (Saya isi perpus)
- Hostname pilih Localhost
- Pssword terserah (Saya isi perpus2020), isikan password yang sama pada kolom Re-type
- Pada bagian Global privileges silahkan centang Check All
Setelah semua diisi klik Go
![image](https://user-images.githubusercontent.com/88962175/129470671-38c5e49d-836f-4d9e-b643-415ad77faa0c.png)



Jika tampilannya seperti dibawah ini maka berarti sudah berhasil
![image](https://user-images.githubusercontent.com/88962175/129470676-a631e8ee-179a-41e9-8ae6-e5c1589db478.png)



Selanjutya masukkan alamat localhost/perpustakaan pada address bar (perpustakaan adalah nama folder instalasi slims 9 yang sudah direname hasil dari ekstrakan rar). Akan muncul halaman seperti gambar dibawah, lalu klik Get Started
![image](https://user-images.githubusercontent.com/88962175/129470681-1712543c-3a10-41d6-92b3-2e8e169b22c2.png)



klik next, lalu pilih Install SliMS
![image](https://user-images.githubusercontent.com/88962175/129470683-426a0a6f-e13f-4364-b2a8-b7094ee40d96.png)



Isikan informasi database yang sudah kita buat tadi yang meliputi Database host (localhost), Database name (perpustakaan), Database username (perpus), Database password (perpus2020) lalu klik Test Connection. Jika connection OK (berwarna hijau) klik next.
![image](https://user-images.githubusercontent.com/88962175/129470687-7e3c9554-3fae-4a91-b086-1d58f26a9966.png)



Selanjutnya kita mengisi kolom lagi untuk Super User Profiles. Isikan terserah kalian atau sama dengan yang isi gapapa, Username (admin), password (admin), Retype password (admin) lalu klik Run the Installation.
![image](https://user-images.githubusercontent.com/88962175/129470689-2508841e-4940-409e-ab3b-c35727c284d0.png)



Selanjutnya muncul halaman seperti dibawah. Jika muncul peringatan Folder install in your SLiMS is already exist. For security reason please rename or remove it from your machine Rename saja folder Install yang ada di directory C:/xampp/htdocs/Perpustakaan/install menjadi install_. Setelah selesai klik Go to my SLiMS.
![image](https://user-images.githubusercontent.com/88962175/129470694-795d4589-d419-4017-883e-91a17dc8bc3f.png)



Selesai, halaman utama SLiMS akan tampil seperti gambar dibawah ini
![image](https://user-images.githubusercontent.com/88962175/129470695-0eedf44d-0e09-4788-aa69-6e72fe0e5214.png)



Untuk masuk ke halaman admin, silahkan login terlebi dahulu dengan memasukkan alamat berikut localhost/perpustakaan/index.php?p=login isikan username (admin) dan password (admin).
![image](https://user-images.githubusercontent.com/88962175/129470700-05de03a4-b60f-42a4-ac09-33188000be09.png)
![image](https://user-images.githubusercontent.com/88962175/129470701-0c856953-433b-41ca-b947-20d3a4d9eeae.png)
https://youtu.be/cQFIcqtbc_s


=====#PETUNJUK KONFIGURASI#=====
OPAC yang akan dibahas pada bab ini merupakan akronim dari Online Public Access
Catalogue dengan terjemahan bebas menjadi Katalog Daring Akses Publik. Katalog
daring artinya rangkaian informasi tentang produk, dalam hal ini buku, yang diterbitkan
menggunakan internet dalam satu laman atau situs sehingga dapat diakses dari mana
pun, kapan pun, oleh siapa pun, dengan kata lain, akses publik.
OPAC merupakan salah satu antarmuka yang digunakan pada SLiMS. Selain OPAC,
antarmuka lainnya adalah antarmuka Administrasi. Antarmuka Administrasi akan
banyak dibahas dan dilihat pada bab-bab setelah bab ini. Di dalam bab ini, kita akan
melihat pernak-pernik yang ada di dalam antarmuka OPAC.
0.1. Tampilan Antarmuka OPAC SLiMS
Berikut ditampilkan antarmuka OPAC SLiMS mulai dari Senayan3-Stable14 Seulanga
sampai dengan versi terkini SLiMS 9 Bulian.
![image](https://user-images.githubusercontent.com/88962175/129470937-424f0ea6-7d82-4204-a201-7e39d9fcc642.png)
Gambar 2. Tampilan OPAC Senayan3-Stable14 Seulanga

Penjelasan:
OPAC Senayan 3 Stable 14 Seulanga menampilkan menu, header​, sidebar​, konten, dan
footer​. Menu yang disediakan adalah Home​, Library Information​, Help on Search​,
Member Area​, dan Librarian login​. Header merupakan logo dari SLiMS, judul, dan sub
judul. Kemudian sidebar terdiri dari Select Language​, Simple Search​, Advanced Search​.
Untuk konten berisi tentang koleksi yang dapat diakses oleh pemustaka. Sedangkan
footer​ adalah informasi mengenai SLiMS secara singkat.
![image](https://user-images.githubusercontent.com/88962175/129470987-b4b557f9-8706-477f-a091-8bc0c9d6988a.png)
Gambar 3. Tampilan OPAC SLiMS3-Stable15 Matoa

Penjelasan:
OPAC pada Senayan 3 Stable 15 Matoa, tidak memiliki perubahan yang signifikan
dengan apa yang telah dikembangkan pada OPAC Senayan 3 Stable 14 Seulanga.
Perubahan terdapat di beberapa titik saja antara lain, penambahan background pada
header​, penempatan kolom Search di bagian header yang sebelumnya di bagian sidebar
dan perubahan warna dasar agar terlihat lebih hidup.
![image](https://user-images.githubusercontent.com/88962175/129471002-f3b607ad-d567-4916-b34d-b0b4e758b9d9.png)
Gambar 4. Tampilan OPAC SLiMS 5 Meranti

Penjelasan:
Tampilan OPAC SLiMS 5 Meranti mengalami perubahan yang signifikan dari kedua versi
SLiMS sebelumnya. Hal ini ditandai dengan tidak adanya sidebar dan konten hasil
proses entri data koleksi. Fokus perubahan ada dengan ditempatkannya kolom Search
pada bagian tengah dari tampilan OPAC sehingga menjadi lebih elegan. Selain itu ada
penambahan bagian atas berupa navbar berisi tautan media sosial dan penempatan
baru dari ​Select Language​.
![image](https://user-images.githubusercontent.com/88962175/129471019-3ebf5d53-7b9b-4345-9c88-61238257cac6.png)
Gambar 5. Tampilan OPAC SLiMS 7 Cendana

Penjelasan:
Tampilan OPAC SLiMS 7 Cendana hanya menyempurnakan apa yang telah dilakukan
pada tampilan OPAC SLiMS 5 Meranti. Penyempurnaan menghasilkan background
dengan resolusi yang lebih tinggi sehingga tampak lebih menarik. Kemudian ada
penambahan pada sub menu yaitu Librarian yang menyediakan informasi terkait
Pustakawan pengelola perpustakaan.
![image](https://user-images.githubusercontent.com/88962175/129471028-3a597088-cf4e-4d65-9993-514c44f70cfe.png)
Gambar 6. Tampilan OPAC SLiMS 8 Akasia

Penjelasan:
Tampilan OPAC SLiMS 8 Akasia menjadi lebih berbeda. OPAC SLiMS 8 Akasia menjadi
terlihat sederhana namun tetap memiliki kesan elegan. Banyak perubahan yang
dihasilkan pada tampilan OPAC SLiMS 8 Akasia yaitu antara lain penambahan logo
menu. Menu yang disediakan Home​, Library News​, Library Information​, Library Location​,
Member Area​, Librarian​, Help on Search​, Librarian Login​, dan About SLiMS, serta menu
pengganti bahasa antarmuka. Kolom pencarian menjadi lebih sederhana karena hanya
menyediakan satu kolom saja namun tidak mengurangi kualitas hasil pencarian.
Penambahan fitur pada OPAC SLiMS 8 Akasia adalah fitur live chat​. Kemudian
penempatan media sosial juga diubah menjadi di bagian ​footer​.
![image](https://user-images.githubusercontent.com/88962175/129471043-067dfce4-d55b-4bab-9342-e3c56edd06ad.png)
Gambar 7. Tampilan OPAC SLiMS 9 Bulian

Penjelasan:
Versi baru, tampilan dibuat menjadi lebih segar. SLiMS 9 Bulian menggunakan templat
OPAC Classic yang sudah dioptimalkan. Pada templat ini, informasi data bibliografi
ditampilkan berdasarkan klasifikasi. Ditampilkan pula daftar koleksi terpopuler, daftar
koleksi terbaru serta yang diperbarui, daftar peminjam. Menu ditampilkan pada header
templat, sehingga langsung terlihat oleh pengguna.
0.2. Pengenalan Menu pada OPAC SLiMS
Akses menu pada SLiMS 9 Bulian tidak lagi disembunyikan, seperti pada versi-versi
sebelumnya. Dengan templat OPAC Classic, menu-menu tersebut dapat diakses pada
bagian atas laman.
![image](https://user-images.githubusercontent.com/88962175/129471076-5e0617bc-7908-42b6-b9ec-544142e69205.png)
Gambar 8. Tampilan menu pada OPAC
Menu-menu yang tersedia pada umumnya sama dengan versi sebelumnya.
![image](https://user-images.githubusercontent.com/88962175/129471102-a20a68ae-b7dc-49ea-854e-583f2c186367.png)
0.2.1. Information
Gambar 9. Tampilan laman ​Information
menyediakan informasi singkat tentang perpustakaan. Mulai dari alamat, nomor
telepon, hingga jenis koleksi yang disediakan oleh perpustakaan tersebut. Untuk
mengubah konten laman ini, Anda harus memiliki akses ke laman administrasi SLiMS.
![image](https://user-images.githubusercontent.com/88962175/129471120-5a510fc0-85b9-4bee-9ac3-deed8b40d6c0.png)
0.2.2. News
Gambar 10. Tampilan laman ​News
Laman ini ditujukan sebagai laman untuk penyampaian berita kegiatan yang dilakukan
oleh Perpustakaan. Laman ini dapat digunakan untuk Content Management System
(CMS) secara sederhana. Dengan adanya fitur ini, perpustakaan dapat menulis liputan
tentang kegiatan perpustakaan.
![image](https://user-images.githubusercontent.com/88962175/129471139-72cf49e4-7378-4a79-b867-391fdc0aa255.png)
0.2.3. Help
Gambar 11. Tampilan laman ​Help
Menu ini memberikan penjelasan secara sederhana tentang bagaimana melakukan
pencarian.
![image](https://user-images.githubusercontent.com/88962175/129471180-9166d865-5130-4aea-a595-262487949e7a.png)
0.2.4. Librarian
Gambar 12. Tampilan laman ​Librarian
Menu ini menyajikan informasi profil diri pustakawan.
![image](https://user-images.githubusercontent.com/88962175/129471210-4a46d13b-4474-48d0-a039-d368397e8ac5.png)
0.2.5. Member Area
Gambar 13. Tampilan laman ​Member Area
Menu Member Area memberikan kemudahan bagi pengguna/pemustaka untuk dapat
memantau peminjaman yang masih aktif maupun sejarah peminjaman. Pada menu ini,
pengguna/pemustaka juga dapat melakukan ​booking​ (pemesanan) bahan pustaka.
![image](https://user-images.githubusercontent.com/88962175/129471225-9c160c5a-92c3-42b0-ae5a-c0bec9831ce9.png)
0.2.6. Bahasa Antarmuka
Gambar 14. Tampilan menu ubah bahasa
Pada bagian bawah kumpulan menu, terdapat menu untuk mengubah bahasa
antarmuka SLiMS. Adapun bahasa-bahasa yang secara baku tersedia adalah Bahasa
Arab, Bahasa Bengali, Bahasa Portugis Brasil, Bahasa Inggris, Bahasa Spanyol, Bahasa
Jerman, Bahasa Indonesia, Bahasa Jepang, Bahasa Thailand, Bahasa Melayu, Bahasa
Parsi, Bahasa Rusia, Bahasa Turki, Bahasa Urdu.

0.3. Bagian Lain pada OPAC
Selain menu-menu yang sudah dibahas tadi, beberapa bagian yang terdapat pada
templat baru SLiMS 9 Bulian adalah:
Gambar 15. Penapis bibliografi berdasarkan nomor klasifikasi
Pemustaka cukup memilih ikon sesuai dengan nomor klasifikasi yang diinginkan. Klik
pada tombol "​see more​" untuk melihat tampilan ikon klasifikasi lainnya.
Gambar 16. Daftar koleksi yang sering dipinjam
Dalam templat ini, dimunculkan daftar koleksi yang populer di kalangan pemustaka.
Semoga dapat dijadikan referensi oleh pemustaka lain ketika memutuskan ingin
membaca suatu buku.
![image](https://user-images.githubusercontent.com/88962175/129471249-dcb56991-edb2-4e19-bb90-bae32406ba15.png)
Gambar 17. Koleksi baru
Bagian ini menjadi etalase untuk buku-buku yang datanya baru dimasukkan. Serta
ditampilkan pula buku yang data bibliografinya mengalami perbaikan.
![image](https://user-images.githubusercontent.com/88962175/129471267-7263d497-72a1-4582-b917-aebb0091f26f.png)
Gambar 18. Pemustaka paling aktif
Untuk memfasilitasi informasi siapa pemustaka yang paling rajin dalam membaca,
disediakan bagian ini. Sebagai bentuk apresiasi bagi pemustaka karena telah
memanfaatkan perpustakaan sebagai media belajar.
![image](https://user-images.githubusercontent.com/88962175/129471273-e690a7e9-c856-4259-be9e-d6b1e4a51335.png)
Gambar 19. Informasi lokasi perpustakaan
Kalau pada versi sebelumnya, informasi ini disediakan pada menu ​Library Location​, saat
ini, informasi tersebut dimunculkan dalam tampilan yang lebih informatif, sehingga
pemustaka dapat langsung melihat lokasi serta informasi lainnya terkait perpustakaan.

Pemustaka dapat melihat sekilas informasi tentang SLiMS. Pada bagian ini, pemustaka
juga dapat melakukan pencarian (secara sederhana). Serta ditampilkan menu-menu
yang sudah disebutkan sebelumnya. Disediakan pula tombol donasi, apabila pemustaka
ingin memberikan donasi, mendukung kerja-kerja pengembangan SLiMS.
Bagian pada tema OPAC ini dapat diubah pada modul System sub-menu Theme​. Klik
pada tombol "​Customize​" di kolom ​Public Template​ untuk templat yang aktif.

0.4. Akses Login Laman Administrasi SLiMS
Pada versi SLiMS 9 Bulian, akses login ke laman administrasi SLiMS tidak ditampilkan
seperti pada versi sebelumnya. Namun jangan khawatir. Akses login masih bisa diakses
dengan memasukkan alamat seperti gambar berikut:
Gambar 21. Akses ​login ​ke laman Admin SLiMS
Atau, cara mudah tanpa harus mengingat pengalamatan, adalah dengan melakukan klik
pada tautan seperti ​"​Information​"​ yang akan memunculkan alamat
http://localhost/slims9_bulian/index.php?p=libinfo​. ​Ganti kalimat "libinfo" dengan
kalimat "login"​ sehingga menjadi seperti ini,
http://localhost/slims9_bulian/index.php?p=login​. Kemudian ​enter​ untuk memunculkan
akses ​login​.
![image](https://user-images.githubusercontent.com/88962175/129471289-095bef46-c7bd-43bd-b342-2a06b47bb84f.png)
Gambar 22. Tampilan akses ​login
Setelah akses login ini muncul, jangan lupa untuk melakukan bookmark pada akses
tersebut, sehingga bisa muncul pada bookmark bar di peramban yang Anda gunakan.
Dengan mem-​bookmark akses tersebut, maka selanjutnya, apabila Anda ingin login​,
Anda hanya ​melakukan klik pada ​bookmark​ tersebut​.

