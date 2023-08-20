# BelaJar Layer Network

## Model referensi Open System Interconnection (OSI) berfungsi sebagai elemen paling dasar dari jaringan komputer di awal tahub 1984.

###Osi Model###

###Application###
 ###|###
 ###v###
###Presentation###
 ###|###
 ###v###
Session
 ###|###
    v
Transport
    |
    v
Network 
    |
    v
Data Link
    |
    v
Physical 

Aplication layer adalah  lapisan paling atas yang menyediakan satu set antarmuka untuk aplikas, dimana mendapatkan akases  layanan jaringan serta akses ke layanan jaringan yang mendukung aplikasi secara langsung.

fugsi yang disediakan : 
1. File Transfer Access dan Management (FTAM) layanan dalam pengolahan data  yaitu perpindahan file antar sistem yang berbeda, mebaca, menulis, dan menghapus file jarak jauh, dan pengelolaan penyimpanan file jarak jauh.
2. Virtual Terminal (VT): layanan untuk melakukan akases aplikasi di sistem komputer jarak jauh yang berbeda melaui stimulasi terminal nyata.
3. Electronik Mail and Messagin Handling (MHS) : Memfasilitasi pertukaran dokumen secara elektronik.
4. Layanan Direktori (DS): Meyediakan layanan dengan kemampuan untuk mencocokkan nama dengan informasi pengalamatan.
5. Common Management Information Protocol (CMIP) : Layanan untuk manajemen jaringan.

Layanan Aplikasi terdistribusi, baik berbasis OSI atau TCP/IP, Memiliki karakteristik :
1. menyediakan manusia atua aplikasi lain dengan sarana untuk memmasukan perintah
2. mengarahkan aplikasi untuk mengirim file ke   pengirim file dari host jarak jauh,ubah direktori, daftar atau hapus file, dll.
3. Melakukan input ke output dari perangkat penyimapanan public
4. Melakukan file dan informasi terkati file antar host

Persentation Layer adalah layer bertangung jawab atas format data yang ditransfer selama komunikasi jaringan. dimana layer ini mengubah pesan data  dari bentuk umum ke  format yang dapat dimengerti oleh aplikasi penerma yaitu mengubah data menjadi bit atau byte. meskipun komputer tujuan berbeda presentation layer memungkinkan berkomunikasi dengan representasi yang berbeda. layanan komunikasi umum seperti enkripsi, kompresi teks, dan pemformatan ulang. kompresi data digunakan pada layer ini untuk mengurangi jumblah bit yang dimiliki untuk ditransmikan. Kriptografi sering diperlukan untuk privasi dan otentikasi.

 
Session layer : menangani pengaturan sesi, pertukaran data atau pesan, dan penghancuran saat sesi berakhir.dan menjaga hanya pihak yang dituju yang dapat berpartisiasi. memungkinkan pengguna masuk ke sistem pembagian mentrasfer file antara 2 mesin. menyedikan komunikasi 1 atau 2 arah. Manajemen token dapat digunakan untuk memisahakan oprasi yang sama sehingga tidak saling bertabrakan. 

Transportasi Layer : neberima data dari lapisan sesi, membaginya menjadi  lebih kecil, menyebarkan ke lapisan jaringan, dab memeastikan bit yang dikirmkan ditransmisikan tanpa modifikasi, kehilangan atu duplikasi.

network layer : mengontrol pengoperasian sub-net, menyediakan perouteran, kontrol kemacetan, dan akutansi. dimana desain jaringan menetukan bagaimana paket dirutekan dari sumber tujuan. kontrol jaringan  tas koneksi jaringan, saluran logis, segmentasi dan pengurutan, dan aliran data dapat ditempatkan di lapisan ini

Lapisan data link : mengambil transmisi meta dan mengubanya baris yang bebas kesalahan pada lapisan jaringan. data link memecah  data input menjadi bagian kecil, mengirimkan bingkai berurutan, dan memproses protokol digunakan komunikasi natar pernagkat melau ethernet atau protokol wifi. Mengatur flow Contror mengatur kecepatan pengiriman data untuk mencegah kemacetan dan memastikan penerima dapat menangani data yang masuk. Melakukan deteksi dan koreksi kesalahan teknik ynag digunakan termasuk CRC dan bit paritas  

phiysical layer dimana pada layer pengiriman bit dilakukan oada saluran komunikasi. desain jaringan menetukan bagaimana phiysical layer berkerja dengan sistem kabel yang digunakan seperti topologi bus, bintang, ring.


Konsep Osi layer
- layanan
- Antarmuka
- Protokol     

OSI vs TCP/IP

OSI
- Aplikasi
- Presentasi
- Sesi
- Transportasi
- Jaringan
- Data Link
- Fisik

TCP/IP
- Aplikasi perwakilan layer OSI 7,6,5
- Transport perwakilan laye Osi 4
- Internet perwakilan layer Osi 3
- Subnet Perwakilan layer Osi 2,1






                                                                                                                                                                               
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          
