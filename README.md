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

=====#Penjelasan Struktur/Hirarki Pemrograman#======

SENAYAN 3 Stable Branch
SLiMS 5
SLiMS 7
SLiMS 8
SLiMS 9
Changes Log

Developers :
Hendro Wicaksono (hendrowicaksono@yahoo.com, hendrowicaksono@gmail.com)
Arie Nugraha (dicarve@yahoo.com, dicarve@gmail.com)
Wardiyono (wynerst@gmail.com)
Purwoko (purgeologi@yahoo.com, tamanjiwa@gmail.com)
Arif Syamsudin (aarif.syamsudin@gmail.com)
Rasyid Ridho (rasyidridho@gmail.com, ridhoedogawa@yahoo.com)
Eddy Subratha (eddy.subratha@gmail.com, mucill@gmail.com) 
Indra Sutriadi (indra.sutriadi@gmail.com)
Waris Agung Widodo (idoalit@gmail.com, ido.alit@gmail.com)
Heru Subekti (heroe.soebekti@gmail.com)

Past Developers:
Sulfan Zayd (sulfan@gmail.com, sulfan.zayd@gmail.com)
Widianto Nugroho (wnugroho@gmail.com)

Localisation contributors :
Germany: Tobias Zeumer (tzeumer@verweisungsform.de)
Thai: Prasitichai เรารักในหลวง (eak.pras@facebook.com)
Bengali: A. K. M. Nurul Alam (nalamapu@gmail.com)
Persian: Mohammad Javad Mansourzadeh (info@mansourzadeh.ir)
Arabic: Rasyid Ridho (rasyidridho@gmail.com), Bounama Kouider (for full Arabic support)        
Malay: Jerry Mohd. Arif 
Brazilian Portuguese: Eduardo Koiti Kataoka (edukataoka@yahoo.com.br)
Spain: Jhon Urrego Felipe Mejia (ingenierofelipeurrego@gmail.com)
Urdu (Pakistan): Faheem Akbar (onlinevws@gmail.com), Aijaz Akhter Ahmadani (ritelibrarian@gmail.com)
Turkish: Ali Yasir Yılmaz (aliyasiryilmaz@gmail.com)
Russian: Igor Gaydyshev (https://sourceforge.net/projects/russiantranslationforsenayan/)

Other contributors:
Gettext support: Tobias Zeumer
Membercard modification: Jushadi Arman Saz (jushadi@unsulbar.ac.id)
English documentation: Jim Richardson
Code enhancement: Drajat Hasan (drajathasan20@gmail.com)
Code enhancement: John Antony (john.antony@iamplus.com)

THANKS TO OUR USERS AND COMMUNITIES, YOU ARE DEVELOPERS TOO!



=====#ChangLog SourceCode#=====
SLiMS 9.4.2 (Bulian)
========================================================================
Fixed : Stock take report detail
Update : Deactivate email debugger
Added : More method to see attachment
Added : Show detail for fines from Fines Report submenu
Added : Method to select group functions
Fixed : RSS feed
Update : More prevention with delete data if have relations
Fixed : Forbiden image thumbnail if modsecurity is on 

SLiMS 9.4.1 (Bulian)
========================================================================
Fixed : Hidden ajax list
Fixed : Hidden menu header for user not administrator
Update : Sub-menus view for dark mode admin template
Added : User other than (super) admin unable to change username
Fixed : Error when user try to save profile change

SLiMS 9.4.0 (Bulian)
========================================================================
Added : Option to not using email for reservation from Member Area
Added : Flexibility to add page content using plugin system
Added : More configuration for system migration
Added : Ctrl + Home (module) to access OPAC instantly from Administration page
Fixed : Member login when accessing protected attachments
Added : Option for reservation from Member Area without sending email (recorded in Reservation sub-menu)
Added : Stock take report detail per user
Fixed : Unknown host while install in paid hosting environment
Fixed : Barcode cut title
Fixed : Problem with mod_security when add some data in Bibliography Module in paid hosting environment
Fixed : Function to downlad attachment in paid hosting environment
Added : Support for load balanced environment

SLiMS 9.3.1 (Bulian)
========================================================================
Fix : upgrade error.

SLiMS 9.3.0 (Bulian)
========================================================================
Added : Print catalog option
Added : Bypass php limit on uploading file for shared hosting
Added : Button to download backup file
Added : Download counter detail and filter
Update : Dashboard data view improvement using AJAX
Added : New plugin system to make ease of pain when adding additional plugin
Added : MySQL port information in installer
Update : PHPMailer with new version and configuration
Fixed : Auto update and delete for UCS
Added : Show hide sub-menu by user group privileges
Added : Placement options for embedded link and video attachments

SLiMS 9.2.2 (Bulian)
========================================================================
Fixed : Missing mysqldump-php dependencies

SLiMS 9.2.1 (Bulian)
========================================================================
Added : Thumbnail and picture preview in Member List
Added : Using mysqldump-php for backup. Less dependency when installing SLiMS to shared hosting
Added : Hide and Promote to homepage filter in Bibliographic List
Fixed : Version tag for latest bulian's release
Fixed : Identifier for production within sysconfig
Fixed : Update information for minimum PHP version
Fixed : Blank page after upload file is failed

SLiMS 9.2.0 (Bulian)
========================================================================
Fixed : Invalid date on upgrade, especially upgrade from SLiMS 5 Cendana version and under 
Added : File attachment download counter report
Added : Biblio log preview
Added : Upload picture to and from local server in ckeditor
Updated : ckeditor to version 4
Added : Search cluster (on default template) for ElasticSearch indexing tool
Added : Easily change About Us information in OPAC (provided as footer). Available in theme customization
Added : GUI acccess to generate new field for Bibliography and Membership. Available in System menu
Added : Security enhancement for CRSF (Cross-Site Request Forgery)
Added : Download book cover directly using url or search through Duckduckgo Service
Added : Cover image thumbnail in Bibliographic List
Updated : Item batch detail in Item Code Batch Generator (Options Button)
Added : Captcha feature to forgot your password recovery mode (admin login)
Added : Procurement report in Reporting Modules
Added : Change logo personification in System Module. Available in System menu
Fixed : Flag icon when change translation. Available in System menu
Updated : Webcam access in HTML5
Added : Personalized backend user template. Available in theme customization
Added : Option for disabling voice in visitor log. Available in System menu
Added : First row information when exporting and importing bibliography and item data
Updated : Bahasa Indonesia translation
Added : Forgot your password recovery mode (admin login)
Added : Option to show or hide first column when export or import

SLiMS 9.1.1 (Bulian)
========================================================================
Added : Upgrade version tag

SLiMS 9.1.0 (Bulian)
========================================================================
Added : Option to activate mobile view in default theme customization
Added : Improve compatibility with PHP7.4 and MySQL5.7
Fixed : Membercard print view when default language is Bahasa Indonesia
Added : Ability to download book cover, when available, with MARC SRU copy cataloguing
Added : Updated translation for Urdu Language
Added : Environment mode for development and or production
Added : Other minor changes

SLiMS 9 (Bulian)
========================================================================
Added : New localisation for Urdu (Pakistan) language
Added : New localisation for Turkish language
Added : New localisation for Russian language
Added : New installer interface with optimized options
Added : New Admin template
Added : Optimized Classic Template
Added : New theme for member card (Classic card theme)
Added : MARC SRU as new copy cataloguing feature
Modified : Added new menu for adding copy cataloguing servers, including MARC SRU servers
Added : Voice synthesizer for visitor counter
Added : Feature to download cover and attachment files (if any) from P2P servers
Added : Configuration using ElasticSearch indexing tool
Fixed : Security enhancement for XSS (cross-site scripting)
Fixed : Security enhancement for SQLi (SQL injection)


SLiMS 8.3.1 (Akasia)
========================================================================
Added : Template changer for OPAC and Administration template in System Configuration replacing 
Modified : Optimized access for menu in OPAC
Added : Advanced search in OPAC
Added : Full Arabic Translation
Added : Biblio log system (for API)

SLiMS 8.3 (Akasia)
========================================================================
Added : Installer auto generate database
Added : Node server for UCS
Added : Node server for P2P
Added : Scope note in vocabulary control
Modified : Password change due to encryption method
Added : User ID in database
Fixed : Auto focus on current stock take menu
Fixed : Download access for PDF

SLiMS 8.2 (Akasia)
========================================================================
Fixed  : Installation problem due to SLiMS version naming
Update : Security access to some iframe scripts

SLiMS 8.1 (Akasia)
========================================================================
Added : New theme for SLiMS 8 OPAC interface, lightweight and classic

SLiMS 8 (Akasia)
========================================================================
Added : New editor in content menu (bye bye tinymce)
Added : Build-in chat
Added : New lightweight and classic template
Added : Citation style for each bibliographic record in OPAC
Added : shortcut settings implemented
Added : Vocabulary Control by Ido Alit (Waris Agung Widodo)
Added : RDA Content, Media and Carrier type input on Bibliography form
Added : Dashboard menu for admin
Update : Optimizing content menu to make a simple cms, delivering news from your library
Update : Re-modelled installer page 
Update : New method in upgrade version within installer page
Update : MARC Export for multiple records
Update : biblio record detail now available on JSON-LD format
Update : schema.org and RDFa microformat data on biblio record detail
Update : schema.org and RDFa microformat data on OPAC result list
Fixed : installer error because of SQL syntax in senayan.sql.php

SLiMS 7 (Cendana)
========================================================================
Added: Persian translation
Added: Cendana Responsive template
Added: Comment field in OPAC
Added: Membercard generator by Jushadi Arman Saz (jushadi@unsulbar.ac.id)
Added: Tooltip in New Bibliography field
Added: New theme for SLiMS 7 Cendana
Added: Label, barcode, and member card settings from within the SLiMS adminstration page
Added: Keyword suggestion using Enchant library
Added: Since Meranti, Google voice search in OPAC using Google Chrome browser
Added: Google voice search for search in OPAC with Google Chrome browser using mobile device
Fixed: Bugs in Custom Reports
Fixed: LDAP auth error
Modified: Type ahead value for Publisher, Publishing Place, Classification


SLIMS 5 (Meranti)
========================================================================
Added: Web-based SLiMS installer
Added: New Template for Admin and OPAC. For old templates can be downloaded from https://github.com/slimstemplate.
Added: Z39.50 SRU: Search/Retrieval via URL
Added: OAI/PMH support (server).
Added: Statement of Responbility field in bibliographic form.
Added: Item(s) code generator
Added: Integrated Classification in Subject field
Added: Catalog card printing
Added: Search result clustering :)
Added: Brazilian Portuguise language
Added: remove orphaned publisher and place
Added: Import MARC data
Added: Member photo capture foto directly from membership form.
Added: keyboard shortcut to modules and submodules.
Added: option to not counting fines in holiday.
Added: Alternative to barcode printing using zend barcode
Added: Improvised mobile apps view
Fixed: Bugs in import/export of bibliographic and item data.
Fixed: Missing filter in item usage statistics on Reporting module
Fixed: Bugs in XML result

SENAYAN 3 Stable 15 (Matoa)
========================================================================
- Fixed: Loan receipt always pop even when there are no circulation transactions
- Added: User no need to modify sysconfig.inc.php to make local customization. It is also not recommended. Use sysconfig.local.inc.php instead.
- Added: Download Loan History and current loan for member (in member login).
- Fixed: improve image viewer handling using OpenHTMLpop.
- Added: lib/minigalnano/createthumb.php for alternative in thumbnail generating to phpThumb. Including modify it to meet slims need: flexible width/height resize and caching.
- Added: UCS is now separated package from SLiMS distribution.
- Fixed: remove UCS variables from SLiMS distribution.
- Added: Author and Topic/Subject structure changes.
- Fixed: change unique key for master topic table.
- Fixed: add author year field for author master table in SQL install script.
- Fixed: install and upgrade script fix.
- Fixed: change classification to call number in item list.
- Fixed: update SQL statement in biblio for publish_year and year in search_biblio.
- Fixed: change 'series' to series_title in install/senayan/sql for search_biblio Table.
- Fixed: biblio index error on series title search.
- Fixed: upgrade script for stable15.
- Fixed: search error on publisher.
- Fixed: ajax history error after saving data and causing wrong page to display.
- Fixed: error on system backup because of already defined constant.
- Fixed: removing urlencode function usage.
- Fixed: bugs fixing for series_title in custom frontpage.
- Added: improve XML mods based support in SLiMS.
- Added: Add tools for searching orphaned topic/author in masterfile module.
- Added: Add Email support for sending notification in due date warning and overdue list (using PHPMailer Library).
- Added: Thai language support (Prasitichai เรารักในหลวง).
- Added: 74% arabic translation.
- Fixed: terrafirma template and language file (id_ID).
- Fixed: AJAX circuation error on circulation transaction.
- Fixed: birthdate exp on membership.
- Added: update security.
- Added: set item status to missing when finishing stocktake.
- Added: Bengali language support (A. K. M. Nurul Alam).
- Added: two database connection (security. least privilege for database connection)
- Added: Integrated IP based access limitation
- Added: Security patch from Indra Sutriadi (sutriadi.web.id) to avoid barcode.php exploitation.
- Added: Option $_SERVER['LOCAL_ADDR'] besides $_SERVER['SERVER_ADDR'] for compatibility reason with IIS (Indra Sutriadi)
- Fixed: change "prototype" word menjadi to "jQuery" (Indra Sutriadi)
- Added: Port Reference to checkref function in phpbarcode library (Indra Sutriadi)

SENAYAN 3 Stable 14 (Seulanga)
========================================================================
- Fixed : Expiration date checking in membership management & circulation transaction.
- Fixed : Print receipt in circulation transaction.
- Added : Union Catalogue Server (more stable for production use)
- Added : Peer-to-peer cataloging service
- Added : Custom fields for bibliographic data/Bibliography module (experimental)
- Added : Custom fields for membership data/Membership module (experimental)


SENAYAN 3 Stable 13
========================================================================
- Fixed : Loan by classification reporting for non-decimal class
- Fixed : OPAC search error when searching with GMD or Collection type containing more than one word
- Fixed : Non-decimal class total titles and items in Custom Recapitulation reporting
- Fixed : Holiday calculation bugs in Circulation (critical)
- Added : Espanol/Spanish translation (John Urrego Felipe Mejia)
- Added : Arabic translation (Rasyid Ridho)
- Added : SWF Document Viewer
- Added : Circulation transaction receipt when transaction is finished
- Added : Bibliographic item data export and import features
- Added : Union Catalogue Server (experimental)


SENAYAN 3 Stable 12
========================================================================
- Added : Member login in OPAC
- Added : File download limitation based on Member type
- Added : new public template (igos & terrafirma)
- Added : new admin template (igos)


SENAYAN 3 Stable 11
========================================================================
- Added : Change Loan Date and Due Date manually in circulation transaction (if enabled)
- Added : Replaced language constants with gettext (thanks a lot to Tobias Zeumer).
- Added : German SQL (translates all default data).
- Added : Stock Take, List only item for current logged in user in current stock take and Upload item code list.
- Added : Label on Bibliographic records can have URL.
- Added : German translations from Tobias Zeumer.
- Added : security enhancement for language switch in sysconfig.
- Fixed : Some Javascripts code optimized.
- Fixed : date handling on holiday settings.
- Fixed : Biblio detail metadata notes field is now HTML stripped in OPAC's record detail
- Fixed : Skip stock take on item status not working when Stock take initialize.
- Fixed : Paging in loan rules.
- Fixed : Forcing UTF8 for MySQL/HTTP
- Fixed : Session cookies revision.
- Fixed : Simbio Form Table.
- Fixed : Fines list bugs in circulation.
- Fixed : Optimized OPAC's search engine.
- Fixed : Custom reports date filter.
- Fixed : AJAX error in Item Barcode Generator.
- Fixed : Mobile browser detection utility
- Fixed : many untranslated string, thanks to Tobias Zeumer


STABLE 10
========================================================================
- Fixed : Backup module
- Added : MODS (Metadata Object Description Schema) XML format
- Added : Z3950 bibliographic data service
- Added : Multimedia viewer
- Added : multiple file upload
- Added : booleans operator in OPAC and bibliography
- Added : Enhanced advanced search
- Fixed : duplicate item code warning in Item data form
- Added : Improvement on New Custom Report - Item Usage and Loan By Class
- Added : Improvement on Record number to show option in custom reports
- Added : PHP-based template system
- Added : Robots support for third-party indexing engine
- Added : Serial control management
- Fixed : in stocktaking for location filter


STABLE 9
========================================================================
- Added : A lot of improvements related with security issues.
- Added : security patch using Apache .htaccess. So it means that it only works with Apache web
  server. So it is recomended to use Senayan with Apache web server.
- Added : security patches in AJAX request in item_list.
- Added : Some options to add more advanced AJAX Security
- Added : Option to custom base url on search result (useful to implement filesystem-based web caching)
- Added : Simple content management system to create non-collection information
- Added : Options to customize senayan OPAC frontpage
- Added : Features to promote collections to frontpage
- Added : Feature to add header info only in frontpage
- Fixed : printing customization
- Fixed : displaying background image for some template
- Added : template (invention)


STABLE 8 - Saturday, 2009-03-14
========================================================================
- Added : custom result field in OPAC search result
- Fixed : security vulnerability, enable attacker to inject HTML in OPAC search query and XSS attack
- Added : New reporting summary based on class and staff activities
- Added : Feature for duplicating call number to data item.
- Added : Printing membership card.
- Added : Configurable label, barcode, and membership card printing per template.
- Fixed : expiry of collection reservation.


STABLE 7 - Wednesday, 2009-01-12
========================================================================
- Added : holiday date range in Holiday Setting
- Added : CLEAR LOGS for clearing full/bloated System Log
- Added : Inventory Code field in item data form
- Added : Currency field in item data form
- Added : Improved document label and barcode printing
- Fixed : Javascript AJAX Drop down menu
- Added : Feature of for saving logs
- Fixed : searching item for checked-out item list.
- Fixed : importing bibliographic data
- Fixed : printing call number label
- Added : filter in reporting
- Added : reservation list (circulation)


STABLE 6 - Sunday, 2008-09-21
========================================================================
- Fixed : change template from global configuration interface


STABLE 5 - Tuesday, 2008-06-20
========================================================================
- Added : Improvement in javascript codes
- Added : Template file and CSS refinements
- Added : Improvement in record detail for showing item list and its due date
- Added : Improvement on bootstrap file (index.php) behaviour
- Added : template "blue" by Eddy Subratha
- Added : Improvement holiday count in overdue
- Added : Implementation of overdue grace periode for circulation
- Fixed : backup proccess for wrong paging library inclusion
- Added : Update in translation by Wardiyono (wynerst@gmail.com)
- Added : version information
- Added : Improvement in AJAX handling for drop down box
- Added : Grace Periode for overdue on circulation
- Added : Language selection in OPAC
- Added : OPAC template "blue" by Eddy Subratha
- Added : Improvement in default templates


STABLE 4 - Monday, 2008-05-09
========================================================================
- Added : Multi-language support
- Fixed : paging
- Added : Improved login sessions handling
- Fixed : search at overdue list on circulation module


STABLE 3 - Monday, 2008-03-25
========================================================================
- Fixed : changing user profile for administrator
- Fixed : overdue warnings at admin home page for not showing the right counts
- Fixed : sessions timeout handling
- Fixed : upload error because of filename contain single or double quote characters
- Fixed : checking ID field for showing FORBIDDEN ACCESS when others computer trying set ID Field in form
- Fixed : print counters for Label Prints and Item Barcodes Print
- Fixed : deleting collection type
- Fixed : string handling
- Added : in Circulation transaction, Fines values automatically displayed in Loan List, without having to return
  or extend loan first
- Added : Subject, Series Title in OPAC's Record Detail
- Added : in OPAC's Record Detail, Each Author Name and Subject Term are hyperlinked to related document
- Added : master file document language
- Added : expired member list in membership module
- Added : improvement in security handling
- Added : authority level for Author and Topic/Subject
- Added : improvement on bibliographic import and export tools
- Added : improvement on stock take modules


STABLE 2 - Friday, 2008-03-22
========================================================================
- Fixed : changing user profile for empty password
- Fixed : record detail for not showing GMD/Medium data
- Fixed : green OPAC template
- Fixed : Reporting module at Membership section
- Fixed : login proccess for User that belongs to any User Group
- Fixed : System Logs's searching
- Fixed : Stock Take's searching
- Added : overdue warnings at admin home page
- Added : warnings for ON LOAN or INVALID item code
- Added : Detail for stock take history


STABLE 1
========================================================================
- Added : New built-in system logs.
- Fixed : templating system.
- Added : New Document Labels printing on "bibliographic" module, based on Call Number.
- Added : New Item barcode generator printing on "bibliographic" module.
- Added : New Partial stock taking proccess on "stock_take" module.
- Added : New overdue detail in Overdue list on "circulation" module.
- Added : New Item Status mode allow you to set certain action for some Item Status, such as "Loan Forbid".
- Added : New Login Session timeout.
- Added : Few new options in global configuration options.
- Added : Warning system in admin home for some application settings.
- Fixed : "master_file" module.
- Fixed : "stock_take" module.
- Fixed : "system" module.
- Fixed : security issues.
- Fixed : many part of circulation module.
- Added : "Location" and "Availaibility" field in OPACs record detail.
- Added : "location" field for advanced search in OPAC to narrow search scope in specific location.
- Added : "size" option in Barcode generator.
- Added : "member_since_date" field in "member" table.
- Added : "source" field in "item" table.
- Added : "report_file" field in "stock_take" table.
- Added : New table "system_log" in database for storing system logs.
- Fixed : "publish_place" field changed to "publish_place_id" (foreign key to mst_place table) field in "biblio" table.
- Fixed : Re-ordering of "input_date" and "last_update" fields in "biblio" table.


======# Informasi hak Cipta dan perizinan menggunakan perangkat Lunak#======
GNU GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007

 Copyright (C) 2007 Free Software Foundation, Inc. <http://fsf.org/>
 Everyone is permitted to copy and distribute verbatim copies
 of this license document, but changing it is not allowed.

                            Preamble

  The GNU General Public License is a free, copyleft license for
software and other kinds of works.

  The licenses for most software and other practical works are designed
to take away your freedom to share and change the works.  By contrast,
the GNU General Public License is intended to guarantee your freedom to
share and change all versions of a program--to make sure it remains free
software for all its users.  We, the Free Software Foundation, use the
GNU General Public License for most of our software; it applies also to
any other work released this way by its authors.  You can apply it to
your programs, too.

  When we speak of free software, we are referring to freedom, not
price.  Our General Public Licenses are designed to make sure that you
have the freedom to distribute copies of free software (and charge for
them if you wish), that you receive source code or can get it if you
want it, that you can change the software or use pieces of it in new
free programs, and that you know you can do these things.

  To protect your rights, we need to prevent others from denying you
these rights or asking you to surrender the rights.  Therefore, you have
certain responsibilities if you distribute copies of the software, or if
you modify it: responsibilities to respect the freedom of others.

  For example, if you distribute copies of such a program, whether
gratis or for a fee, you must pass on to the recipients the same
freedoms that you received.  You must make sure that they, too, receive
or can get the source code.  And you must show them these terms so they
know their rights.

  Developers that use the GNU GPL protect your rights with two steps:
(1) assert copyright on the software, and (2) offer you this License
giving you legal permission to copy, distribute and/or modify it.

  For the developers' and authors' protection, the GPL clearly explains
that there is no warranty for this free software.  For both users' and
authors' sake, the GPL requires that modified versions be marked as
changed, so that their problems will not be attributed erroneously to
authors of previous versions.

  Some devices are designed to deny users access to install or run
modified versions of the software inside them, although the manufacturer
can do so.  This is fundamentally incompatible with the aim of
protecting users' freedom to change the software.  The systematic
pattern of such abuse occurs in the area of products for individuals to
use, which is precisely where it is most unacceptable.  Therefore, we
have designed this version of the GPL to prohibit the practice for those
products.  If such problems arise substantially in other domains, we
stand ready to extend this provision to those domains in future versions
of the GPL, as needed to protect the freedom of users.

  Finally, every program is threatened constantly by software patents.
States should not allow patents to restrict development and use of
software on general-purpose computers, but in those that do, we wish to
avoid the special danger that patents applied to a free program could
make it effectively proprietary.  To prevent this, the GPL assures that
patents cannot be used to render the program non-free.

  The precise terms and conditions for copying, distribution and
modification follow.

                       TERMS AND CONDITIONS

  0. Definitions.

  "This License" refers to version 3 of the GNU General Public License.

  "Copyright" also means copyright-like laws that apply to other kinds of
works, such as semiconductor masks.

  "The Program" refers to any copyrightable work licensed under this
License.  Each licensee is addressed as "you".  "Licensees" and
"recipients" may be individuals or organizations.

  To "modify" a work means to copy from or adapt all or part of the work
in a fashion requiring copyright permission, other than the making of an
exact copy.  The resulting work is called a "modified version" of the
earlier work or a work "based on" the earlier work.

  A "covered work" means either the unmodified Program or a work based
on the Program.

  To "propagate" a work means to do anything with it that, without
permission, would make you directly or secondarily liable for
infringement under applicable copyright law, except executing it on a
computer or modifying a private copy.  Propagation includes copying,
distribution (with or without modification), making available to the
public, and in some countries other activities as well.

  To "convey" a work means any kind of propagation that enables other
parties to make or receive copies.  Mere interaction with a user through
a computer network, with no transfer of a copy, is not conveying.

  An interactive user interface displays "Appropriate Legal Notices"
to the extent that it includes a convenient and prominently visible
feature that (1) displays an appropriate copyright notice, and (2)
tells the user that there is no warranty for the work (except to the
extent that warranties are provided), that licensees may convey the
work under this License, and how to view a copy of this License.  If
the interface presents a list of user commands or options, such as a
menu, a prominent item in the list meets this criterion.

  1. Source Code.

  The "source code" for a work means the preferred form of the work
for making modifications to it.  "Object code" means any non-source
form of a work.

  A "Standard Interface" means an interface that either is an official
standard defined by a recognized standards body, or, in the case of
interfaces specified for a particular programming language, one that
is widely used among developers working in that language.

  The "System Libraries" of an executable work include anything, other
than the work as a whole, that (a) is included in the normal form of
packaging a Major Component, but which is not part of that Major
Component, and (b) serves only to enable use of the work with that
Major Component, or to implement a Standard Interface for which an
implementation is available to the public in source code form.  A
"Major Component", in this context, means a major essential component
(kernel, window system, and so on) of the specific operating system
(if any) on which the executable work runs, or a compiler used to
produce the work, or an object code interpreter used to run it.

  The "Corresponding Source" for a work in object code form means all
the source code needed to generate, install, and (for an executable
work) run the object code and to modify the work, including scripts to
control those activities.  However, it does not include the work's
System Libraries, or general-purpose tools or generally available free
programs which are used unmodified in performing those activities but
which are not part of the work.  For example, Corresponding Source
includes interface definition files associated with source files for
the work, and the source code for shared libraries and dynamically
linked subprograms that the work is specifically designed to require,
such as by intimate data communication or control flow between those
subprograms and other parts of the work.

  The Corresponding Source need not include anything that users
can regenerate automatically from other parts of the Corresponding
Source.

  The Corresponding Source for a work in source code form is that
same work.

  2. Basic Permissions.

  All rights granted under this License are granted for the term of
copyright on the Program, and are irrevocable provided the stated
conditions are met.  This License explicitly affirms your unlimited
permission to run the unmodified Program.  The output from running a
covered work is covered by this License only if the output, given its
content, constitutes a covered work.  This License acknowledges your
rights of fair use or other equivalent, as provided by copyright law.

  You may make, run and propagate covered works that you do not
convey, without conditions so long as your license otherwise remains
in force.  You may convey covered works to others for the sole purpose
of having them make modifications exclusively for you, or provide you
with facilities for running those works, provided that you comply with
the terms of this License in conveying all material for which you do
not control copyright.  Those thus making or running the covered works
for you must do so exclusively on your behalf, under your direction
and control, on terms that prohibit them from making any copies of
your copyrighted material outside their relationship with you.

  Conveying under any other circumstances is permitted solely under
the conditions stated below.  Sublicensing is not allowed; section 10
makes it unnecessary.

  3. Protecting Users' Legal Rights From Anti-Circumvention Law.

  No covered work shall be deemed part of an effective technological
measure under any applicable law fulfilling obligations under article
11 of the WIPO copyright treaty adopted on 20 December 1996, or
similar laws prohibiting or restricting circumvention of such
measures.

  When you convey a covered work, you waive any legal power to forbid
circumvention of technological measures to the extent such circumvention
is effected by exercising rights under this License with respect to
the covered work, and you disclaim any intention to limit operation or
modification of the work as a means of enforcing, against the work's
users, your or third parties' legal rights to forbid circumvention of
technological measures.

  4. Conveying Verbatim Copies.

  You may convey verbatim copies of the Program's source code as you
receive it, in any medium, provided that you conspicuously and
appropriately publish on each copy an appropriate copyright notice;
keep intact all notices stating that this License and any
non-permissive terms added in accord with section 7 apply to the code;
keep intact all notices of the absence of any warranty; and give all
recipients a copy of this License along with the Program.

  You may charge any price or no price for each copy that you convey,
and you may offer support or warranty protection for a fee.

  5. Conveying Modified Source Versions.

  You may convey a work based on the Program, or the modifications to
produce it from the Program, in the form of source code under the
terms of section 4, provided that you also meet all of these conditions:

    a) The work must carry prominent notices stating that you modified
    it, and giving a relevant date.

    b) The work must carry prominent notices stating that it is
    released under this License and any conditions added under section
    7.  This requirement modifies the requirement in section 4 to
    "keep intact all notices".

    c) You must license the entire work, as a whole, under this
    License to anyone who comes into possession of a copy.  This
    License will therefore apply, along with any applicable section 7
    additional terms, to the whole of the work, and all its parts,
    regardless of how they are packaged.  This License gives no
    permission to license the work in any other way, but it does not
    invalidate such permission if you have separately received it.

    d) If the work has interactive user interfaces, each must display
    Appropriate Legal Notices; however, if the Program has interactive
    interfaces that do not display Appropriate Legal Notices, your
    work need not make them do so.

  A compilation of a covered work with other separate and independent
works, which are not by their nature extensions of the covered work,
and which are not combined with it such as to form a larger program,
in or on a volume of a storage or distribution medium, is called an
"aggregate" if the compilation and its resulting copyright are not
used to limit the access or legal rights of the compilation's users
beyond what the individual works permit.  Inclusion of a covered work
in an aggregate does not cause this License to apply to the other
parts of the aggregate.

  6. Conveying Non-Source Forms.

  You may convey a covered work in object code form under the terms
of sections 4 and 5, provided that you also convey the
machine-readable Corresponding Source under the terms of this License,
in one of these ways:

    a) Convey the object code in, or embodied in, a physical product
    (including a physical distribution medium), accompanied by the
    Corresponding Source fixed on a durable physical medium
    customarily used for software interchange.

    b) Convey the object code in, or embodied in, a physical product
    (including a physical distribution medium), accompanied by a
    written offer, valid for at least three years and valid for as
    long as you offer spare parts or customer support for that product
    model, to give anyone who possesses the object code either (1) a
    copy of the Corresponding Source for all the software in the
    product that is covered by this License, on a durable physical
    medium customarily used for software interchange, for a price no
    more than your reasonable cost of physically performing this
    conveying of source, or (2) access to copy the
    Corresponding Source from a network server at no charge.

    c) Convey individual copies of the object code with a copy of the
    written offer to provide the Corresponding Source.  This
    alternative is allowed only occasionally and noncommercially, and
    only if you received the object code with such an offer, in accord
    with subsection 6b.

    d) Convey the object code by offering access from a designated
    place (gratis or for a charge), and offer equivalent access to the
    Corresponding Source in the same way through the same place at no
    further charge.  You need not require recipients to copy the
    Corresponding Source along with the object code.  If the place to
    copy the object code is a network server, the Corresponding Source
    may be on a different server (operated by you or a third party)
    that supports equivalent copying facilities, provided you maintain
    clear directions next to the object code saying where to find the
    Corresponding Source.  Regardless of what server hosts the
    Corresponding Source, you remain obligated to ensure that it is
    available for as long as needed to satisfy these requirements.

    e) Convey the object code using peer-to-peer transmission, provided
    you inform other peers where the object code and Corresponding
    Source of the work are being offered to the general public at no
    charge under subsection 6d.

  A separable portion of the object code, whose source code is excluded
from the Corresponding Source as a System Library, need not be
included in conveying the object code work.

  A "User Product" is either (1) a "consumer product", which means any
tangible personal property which is normally used for personal, family,
or household purposes, or (2) anything designed or sold for incorporation
into a dwelling.  In determining whether a product is a consumer product,
doubtful cases shall be resolved in favor of coverage.  For a particular
product received by a particular user, "normally used" refers to a
typical or common use of that class of product, regardless of the status
of the particular user or of the way in which the particular user
actually uses, or expects or is expected to use, the product.  A product
is a consumer product regardless of whether the product has substantial
commercial, industrial or non-consumer uses, unless such uses represent
the only significant mode of use of the product.

  "Installation Information" for a User Product means any methods,
procedures, authorization keys, or other information required to install
and execute modified versions of a covered work in that User Product from
a modified version of its Corresponding Source.  The information must
suffice to ensure that the continued functioning of the modified object
code is in no case prevented or interfered with solely because
modification has been made.

  If you convey an object code work under this section in, or with, or
specifically for use in, a User Product, and the conveying occurs as
part of a transaction in which the right of possession and use of the
User Product is transferred to the recipient in perpetuity or for a
fixed term (regardless of how the transaction is characterized), the
Corresponding Source conveyed under this section must be accompanied
by the Installation Information.  But this requirement does not apply
if neither you nor any third party retains the ability to install
modified object code on the User Product (for example, the work has
been installed in ROM).

  The requirement to provide Installation Information does not include a
requirement to continue to provide support service, warranty, or updates
for a work that has been modified or installed by the recipient, or for
the User Product in which it has been modified or installed.  Access to a
network may be denied when the modification itself materially and
adversely affects the operation of the network or violates the rules and
protocols for communication across the network.

  Corresponding Source conveyed, and Installation Information provided,
in accord with this section must be in a format that is publicly
documented (and with an implementation available to the public in
source code form), and must require no special password or key for
unpacking, reading or copying.

  7. Additional Terms.

  "Additional permissions" are terms that supplement the terms of this
License by making exceptions from one or more of its conditions.
Additional permissions that are applicable to the entire Program shall
be treated as though they were included in this License, to the extent
that they are valid under applicable law.  If additional permissions
apply only to part of the Program, that part may be used separately
under those permissions, but the entire Program remains governed by
this License without regard to the additional permissions.

  When you convey a copy of a covered work, you may at your option
remove any additional permissions from that copy, or from any part of
it.  (Additional permissions may be written to require their own
removal in certain cases when you modify the work.)  You may place
additional permissions on material, added by you to a covered work,
for which you have or can give appropriate copyright permission.

  Notwithstanding any other provision of this License, for material you
add to a covered work, you may (if authorized by the copyright holders of
that material) supplement the terms of this License with terms:

    a) Disclaiming warranty or limiting liability differently from the
    terms of sections 15 and 16 of this License; or

    b) Requiring preservation of specified reasonable legal notices or
    author attributions in that material or in the Appropriate Legal
    Notices displayed by works containing it; or

    c) Prohibiting misrepresentation of the origin of that material, or
    requiring that modified versions of such material be marked in
    reasonable ways as different from the original version; or

    d) Limiting the use for publicity purposes of names of licensors or
    authors of the material; or

    e) Declining to grant rights under trademark law for use of some
    trade names, trademarks, or service marks; or

    f) Requiring indemnification of licensors and authors of that
    material by anyone who conveys the material (or modified versions of
    it) with contractual assumptions of liability to the recipient, for
    any liability that these contractual assumptions directly impose on
    those licensors and authors.

  All other non-permissive additional terms are considered "further
restrictions" within the meaning of section 10.  If the Program as you
received it, or any part of it, contains a notice stating that it is
governed by this License along with a term that is a further
restriction, you may remove that term.  If a license document contains
a further restriction but permits relicensing or conveying under this
License, you may add to a covered work material governed by the terms
of that license document, provided that the further restriction does
not survive such relicensing or conveying.

  If you add terms to a covered work in accord with this section, you
must place, in the relevant source files, a statement of the
additional terms that apply to those files, or a notice indicating
where to find the applicable terms.

  Additional terms, permissive or non-permissive, may be stated in the
form of a separately written license, or stated as exceptions;
the above requirements apply either way.

  8. Termination.

  You may not propagate or modify a covered work except as expressly
provided under this License.  Any attempt otherwise to propagate or
modify it is void, and will automatically terminate your rights under
this License (including any patent licenses granted under the third
paragraph of section 11).

  However, if you cease all violation of this License, then your
license from a particular copyright holder is reinstated (a)
provisionally, unless and until the copyright holder explicitly and
finally terminates your license, and (b) permanently, if the copyright
holder fails to notify you of the violation by some reasonable means
prior to 60 days after the cessation.

  Moreover, your license from a particular copyright holder is
reinstated permanently if the copyright holder notifies you of the
violation by some reasonable means, this is the first time you have
received notice of violation of this License (for any work) from that
copyright holder, and you cure the violation prior to 30 days after
your receipt of the notice.

  Termination of your rights under this section does not terminate the
licenses of parties who have received copies or rights from you under
this License.  If your rights have been terminated and not permanently
reinstated, you do not qualify to receive new licenses for the same
material under section 10.

  9. Acceptance Not Required for Having Copies.

  You are not required to accept this License in order to receive or
run a copy of the Program.  Ancillary propagation of a covered work
occurring solely as a consequence of using peer-to-peer transmission
to receive a copy likewise does not require acceptance.  However,
nothing other than this License grants you permission to propagate or
modify any covered work.  These actions infringe copyright if you do
not accept this License.  Therefore, by modifying or propagating a
covered work, you indicate your acceptance of this License to do so.

  10. Automatic Licensing of Downstream Recipients.

  Each time you convey a covered work, the recipient automatically
receives a license from the original licensors, to run, modify and
propagate that work, subject to this License.  You are not responsible
for enforcing compliance by third parties with this License.

  An "entity transaction" is a transaction transferring control of an
organization, or substantially all assets of one, or subdividing an
organization, or merging organizations.  If propagation of a covered
work results from an entity transaction, each party to that
transaction who receives a copy of the work also receives whatever
licenses to the work the party's predecessor in interest had or could
give under the previous paragraph, plus a right to possession of the
Corresponding Source of the work from the predecessor in interest, if
the predecessor has it or can get it with reasonable efforts.

  You may not impose any further restrictions on the exercise of the
rights granted or affirmed under this License.  For example, you may
not impose a license fee, royalty, or other charge for exercise of
rights granted under this License, and you may not initiate litigation
(including a cross-claim or counterclaim in a lawsuit) alleging that
any patent claim is infringed by making, using, selling, offering for
sale, or importing the Program or any portion of it.

  11. Patents.

  A "contributor" is a copyright holder who authorizes use under this
License of the Program or a work on which the Program is based.  The
work thus licensed is called the contributor's "contributor version".

  A contributor's "essential patent claims" are all patent claims
owned or controlled by the contributor, whether already acquired or
hereafter acquired, that would be infringed by some manner, permitted
by this License, of making, using, or selling its contributor version,
but do not include claims that would be infringed only as a
consequence of further modification of the contributor version.  For
purposes of this definition, "control" includes the right to grant
patent sublicenses in a manner consistent with the requirements of
this License.

  Each contributor grants you a non-exclusive, worldwide, royalty-free
patent license under the contributor's essential patent claims, to
make, use, sell, offer for sale, import and otherwise run, modify and
propagate the contents of its contributor version.

  In the following three paragraphs, a "patent license" is any express
agreement or commitment, however denominated, not to enforce a patent
(such as an express permission to practice a patent or covenant not to
sue for patent infringement).  To "grant" such a patent license to a
party means to make such an agreement or commitment not to enforce a
patent against the party.

  If you convey a covered work, knowingly relying on a patent license,
and the Corresponding Source of the work is not available for anyone
to copy, free of charge and under the terms of this License, through a
publicly available network server or other readily accessible means,
then you must either (1) cause the Corresponding Source to be so
available, or (2) arrange to deprive yourself of the benefit of the
patent license for this particular work, or (3) arrange, in a manner
consistent with the requirements of this License, to extend the patent
license to downstream recipients.  "Knowingly relying" means you have
actual knowledge that, but for the patent license, your conveying the
covered work in a country, or your recipient's use of the covered work
in a country, would infringe one or more identifiable patents in that
country that you have reason to believe are valid.

  If, pursuant to or in connection with a single transaction or
arrangement, you convey, or propagate by procuring conveyance of, a
covered work, and grant a patent license to some of the parties
receiving the covered work authorizing them to use, propagate, modify
or convey a specific copy of the covered work, then the patent license
you grant is automatically extended to all recipients of the covered
work and works based on it.

  A patent license is "discriminatory" if it does not include within
the scope of its coverage, prohibits the exercise of, or is
conditioned on the non-exercise of one or more of the rights that are
specifically granted under this License.  You may not convey a covered
work if you are a party to an arrangement with a third party that is
in the business of distributing software, under which you make payment
to the third party based on the extent of your activity of conveying
the work, and under which the third party grants, to any of the
parties who would receive the covered work from you, a discriminatory
patent license (a) in connection with copies of the covered work
conveyed by you (or copies made from those copies), or (b) primarily
for and in connection with specific products or compilations that
contain the covered work, unless you entered into that arrangement,
or that patent license was granted, prior to 28 March 2007.

  Nothing in this License shall be construed as excluding or limiting
any implied license or other defenses to infringement that may
otherwise be available to you under applicable patent law.

  12. No Surrender of Others' Freedom.

  If conditions are imposed on you (whether by court order, agreement or
otherwise) that contradict the conditions of this License, they do not
excuse you from the conditions of this License.  If you cannot convey a
covered work so as to satisfy simultaneously your obligations under this
License and any other pertinent obligations, then as a consequence you may
not convey it at all.  For example, if you agree to terms that obligate you
to collect a royalty for further conveying from those to whom you convey
the Program, the only way you could satisfy both those terms and this
License would be to refrain entirely from conveying the Program.

  13. Use with the GNU Affero General Public License.

  Notwithstanding any other provision of this License, you have
permission to link or combine any covered work with a work licensed
under version 3 of the GNU Affero General Public License into a single
combined work, and to convey the resulting work.  The terms of this
License will continue to apply to the part which is the covered work,
but the special requirements of the GNU Affero General Public License,
section 13, concerning interaction through a network will apply to the
combination as such.

  14. Revised Versions of this License.

  The Free Software Foundation may publish revised and/or new versions of
the GNU General Public License from time to time.  Such new versions will
be similar in spirit to the present version, but may differ in detail to
address new problems or concerns.

  Each version is given a distinguishing version number.  If the
Program specifies that a certain numbered version of the GNU General
Public License "or any later version" applies to it, you have the
option of following the terms and conditions either of that numbered
version or of any later version published by the Free Software
Foundation.  If the Program does not specify a version number of the
GNU General Public License, you may choose any version ever published
by the Free Software Foundation.

  If the Program specifies that a proxy can decide which future
versions of the GNU General Public License can be used, that proxy's
public statement of acceptance of a version permanently authorizes you
to choose that version for the Program.

  Later license versions may give you additional or different
permissions.  However, no additional obligations are imposed on any
author or copyright holder as a result of your choosing to follow a
later version.

  15. Disclaimer of Warranty.

  THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY
APPLICABLE LAW.  EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT
HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM "AS IS" WITHOUT WARRANTY
OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO,
THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
PURPOSE.  THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM
IS WITH YOU.  SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF
ALL NECESSARY SERVICING, REPAIR OR CORRECTION.

  16. Limitation of Liability.

  IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING
WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR CONVEYS
THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES, INCLUDING ANY
GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE
USE OR INABILITY TO USE THE PROGRAM (INCLUDING BUT NOT LIMITED TO LOSS OF
DATA OR DATA BEING RENDERED INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD
PARTIES OR A FAILURE OF THE PROGRAM TO OPERATE WITH ANY OTHER PROGRAMS),
EVEN IF SUCH HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF
SUCH DAMAGES.

  17. Interpretation of Sections 15 and 16.

  If the disclaimer of warranty and limitation of liability provided
above cannot be given local legal effect according to their terms,
reviewing courts shall apply local law that most closely approximates
an absolute waiver of all civil liability in connection with the
Program, unless a warranty or assumption of liability accompanies a
copy of the Program in return for a fee.

                     END OF TERMS AND CONDITIONS

            How to Apply These Terms to Your New Programs

  If you develop a new program, and you want it to be of the greatest
possible use to the public, the best way to achieve this is to make it
free software which everyone can redistribute and change under these terms.

  To do so, attach the following notices to the program.  It is safest
to attach them to the start of each source file to most effectively
state the exclusion of warranty; and each file should have at least
the "copyright" line and a pointer to where the full notice is found.

    {one line to give the program's name and a brief idea of what it does.}
    Copyright (C) {year}  {name of author}

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

Also add information on how to contact you by electronic and paper mail.

  If the program does terminal interaction, make it output a short
notice like this when it starts in an interactive mode:

    {project}  Copyright (C) {year}  {fullname}
    This program comes with ABSOLUTELY NO WARRANTY; for details type `show w'.
    This is free software, and you are welcome to redistribute it
    under certain conditions; type `show c' for details.

The hypothetical commands `show w' and `show c' should show the appropriate
parts of the General Public License.  Of course, your program's commands
might be different; for a GUI interface, you would use an "about box".

  You should also get your employer (if you work as a programmer) or school,
if any, to sign a "copyright disclaimer" for the program, if necessary.
For more information on this, and how to apply and follow the GNU GPL, see
<http://www.gnu.org/licenses/>.

  The GNU General Public License does not permit incorporating your program
into proprietary programs.  If your program is a subroutine library, you
may consider it more useful to permit linking proprietary applications with
the library.  If this is what you want to do, use the GNU Lesser General
Public License instead of this License.  But first, please read
<http://www.gnu.org/philosophy/why-not-lgpl.html>.

