# Skrip
Implementasi Data Mining Pada Persediaan Bahan Baku Pembuatan pizza dengan Metode Association Rule 
(Studi Kasus : PHD Karawitan) 


Disusun untuk Sidang Proposal Skripsi
Semester Genap Tahun Akademik 2014/2015


OLEH:
Asep Ahadiaturrohman Nuroja
10111391



 





Program Studi Teknik Informatika
Fakultas Teknik Dan Ilmu Komputer
Universitas Komputer Indonesia
2014
 
HALAMAN PENGAJUAN PEMBIMBING




Implementasi Data Mining Pada Persediaan Bahan Baku Pembuatan pizza dengan Metode Association Rule 
(Studi Kasus : PHD Karawitan) 



NIM: 10111391
Nama: Asep Ahadiaturrohman Nuroja


 






Pembimbing Usulan:
1.	Adam Mukharil Bachtiar, S.Kom., M.T.
2.	Alif Finandhita, S.Kom 

 
DAFTAR ISI
1	
DAFTAR ISI	ii
DAFTAR TABEL	iii
DAFTAR GAMBAR	iv
1.	Latar Belakang Masalah	1
2.	Identifikasi Masalah	1
3.	Maksud dan Tujuan	2
4.	Batasan Masalah	2
5.	Metodologi Penelitian	2
5.1	Metode Pengumpulan Data	2
5.2	Metode Pembangunan Perangkat Lunak	3
6.	Deskripsi Umum Sistem	4
7.	Review Literatur	6
8.	Jadwal dan Tempat Penelitian	8
9.	Sistematika Penulisan	9
10.	Daftar Pustaka	9





 
DAFTAR TABEL

Tabel 1 Jadwal Penelitian	8




 
DAFTAR GAMBAR

Gambar 1 Tahapan Waterfall Model	3
Gambar 2 Deskripsi Umum Sistem	4


 
BAB I 
PENDAHULUAN

1.1	Latar Belakang Masalah
PHD (Pizza Hut Delivery) adalah franchise bagian dari franchise Pizza Hut yang merupakan restoran berantai dan waralaba yang mengkhususkan dalam penyajian pizza. Yang membedakan dari kedua franchise ini adalah konsep yang digunakan, dimana PHD merupakan konsep baru dari Pizza Hut yang terfokus dalam delivery (pesan antar) dan take away (pesan bawa). Sementara Pizza Hut terfokus kepada pelanggan yang ingin menikmati suasana di restoran bersama keluarga serta juga menyediakan take away (pesan bawa).

Di PHD yang terletak di Jalan Karawitan No. 59 Buah Batu Bandung, informasi persedian bahan baku  sangat dibutuhkan. Pembelian bahan baku dilakukan setiap minggu, bahan baku yang dibeli dilihat berdasarkan stok yang dianggap akan habis. Setiap bahan baku yang digunakan mempunyai masa kadaluarsa yang relatif pendek sehingga  dibutuhkan strategi untuk bisa mengurangi kerugian yang diakibatkan karena bahan baku yang sudah masuk masa kadaluarsa. 

Dengan mengaitkan bahan baku pembuatan pizza dengan penjualan tiap produk bisa didapatkan bahan baku apa saja yang menjadi prioritas tersebut. Solusi yang diusulkan adalah dengan pengguanaan konsep data mining dengan metode association rule. Metode associastion rule digunakan untuk bisa mengolah informasi mengenai kombinasi  bahan baku yang sering digunakan  pada suatu waktu.

1.2	Identifikasi Masalah
Berdasarkan paparan latar belakang yang telah dijelaskan diatas, berikut adalah identifikasi masalah tersebut antara lain :
1.	Kurangnya informasi tentang persediaan bahan baku
2.	Kurangnya informasi bahan baku apa saja yang menjadi prioritas yang harus di stok.
3.	Belum adanya implementasi data mining untuk mendapatkan informasi mengenai bahan baku pizza

1.3	Maksud dan Tujuan
Maksud dari penelitian ini adalah untuk mengimplementasikan data mining menggunakan metode association rule untuk melihat hubungan penjualan produk dengan bahan baku di phd karawitan dengan tujuan memberikan informasi / pengetahuan tentang bahan baku yang menjadi prioritas utama yang harus di stok.

1.4	Batasan Masalah
Adapun batasan masalah yang ditemukan dalam penelitian ini antara lain :
4.	Menggunakan data transaksi penjualan pizza
5.	Bahan baku pizza merupakan bahan baku jadi seperti irisan tuna, keju, dan lain lain.
6.	Data penjualan produk yang digunakan merupakan data bulan
7.	Algoritma yang digunakan yaitu algoritma Fp-Growth
8.	Aplikasi yang akan dibangun merupakan aplikasi desktop 
9.	Pembangunan aplikasi menggunakan tools visual studio
10.	Pengolahan basis data dibangun dengan menggunakan  MySql

1.5	Metodologi Penelitian
Metode penelitian yang akan digunakan dalam penelitian ini ada dua metode yaitu : metode pengumpulan data dan metode pembangunan perangkat lunak.
1.5.1	Metode Pengumpulan Data
Teknik pengumpulan data yang digunakan dalam penelitian ini yaitu :
1.	Studi Literatur
Pengumpulan data dilakukan dengan cara mempelajari, meneliti dan menelaah berbagai leteratur yang bersumber dari buku, jurnal ilmiah, situs internet dan bacaan lainya yang berkaitan dengan penelitian yang dilakukan.
2.	Wawancara
Pengambilan data melalui tanya jawab langsung dengan narasumber / pegawai PHD tentang sistem persedian bahan baku pembauatan pizza.

1.5.2	Metode Pembangunan Perangkat Lunak 
Pada tahap pembangunan perangkat lunak ini dilakukan dengan menggunakan metode Waterfall menurut Ian Sommerville. Terdapat 5 tahapan pada Waterfall model yang dapat dilihat pada gambar 1, yaitu requirement analysis and definition, system and software design, implementation and unit testing, integration and system testing, dan operation and maintenance. [1]

 

Gambar 1 Tahapan Waterfall Model

1.	Requirement Analysis And Definition
Merupakan tahapan penetapan fitur, kendala dan tujuan sistem melalui konsultasi dengan pengguna sistem. Semua hal tersebut akan ditetapkan secara rinci dan akan berfungsi sebagai spesifikasi sistem.
2.	System And Software Design
Merupakan tahapan pembentukan arsitektur sistem berdasarkan persyaratan yang telah ditetapkan dan juga mengidentifikasi dan menggambarkan kerangka dasar dari sistem perangkat lunak serta hubungan – hubunganya.


3.	Implementation And Unit Testing
Pada tahapan ini, hasil dari desain perangkat lunak akan direalisasikan menjadi unit program. Setiap unit program akan diuji apakah apakah sudah memenuhi kebutuhan atau spesifikasinya.
4.	Integration And System Testing
Dalam tahapan ini, setiap unit program akan diintegrasikan satu sama lain dan diuji. Ini dilakukan untuk memastikan bahwa sistem yang dibuat sudah memenuhi persyaratan yang ada. Setelah itu sistem akan dikirim ke pengguna sistem.
5.	Operation Maintenance
Pada tahap ini sistem sudah diinstal dan mulai digunakan. Selain itu juga apabila ditemukan kesalahan, software engineer akan melakukan perbaikan terhadap kesalahan yang ada. Dalam tahap ini juga dilakukan pengembangan sistem seperti penambahan fitur dan fungsi baru.

1.6	Sistematika Penulisan
Sistematika penulisan skripsi ini disusun untuk memberikan gambaran umum mengenai penelitian yang dikerjakan. Sistematika penulisan dalam proposal tugas akhir ini adalah sebagai berikut :  

BAB I PENDAHULUAN
Menguraikan tentang latar belakang masalah, menentukan tujuan dan kegunaan penelitian, yang kemudian diikuti dengan batasan masalah, asumsi, serta sistematika penulisan.


BAB II LANDASAN  TEORI
Membahas konsep dasar dari dan teori – teori yang berkaitan dengan topik penelitian yang dilakukan.

BAB III ANALISIS DAN PERANCANGAN SISTEM
Pada bab ini berisi tentang analisis dan perancangan aplikasi data mining.

BAB IV IMPLEMENTASI PROGRAM DAN PENGUJIAN
Pada bab ini berisi pengujian dan pembahasan tentang implementasi dari penerapan teknik data mining serta validasi aplikasi.

BAB V SIMPULAN DAN SARAN
Berisi kesimpulan dan saran yang sudah diperoleh dari hasil penulisan tugas akhir.

 
Daftar Pustaka

[1] 	I. Sommerville, Software Engineering, Eight Edition ed., Addison Wesley, 2007. 
[2] 	S. M. Veronica, “Data Mining Sebagai Solusi Bisnis,” Integral, vol. 7 no. 1, 2002. 
[3] 	D. K. Pane, “IMPLEMENTASI DATA MINING PADA PENJUALAN PRODUK,” Pelita Informatika Budi Darma, vol. IV, no. 3, 2013. 
[4] 	Kennedi Tampubolon,Hoga Saragih,Bobby Reza, "IMPLEMENTASI DATA MINING ALGORITMA APRIORI PADA SISTEM PERSEDIAAN ALAT-ALAT KESEHATAN," Informasi dan Teknologi Ilmiah (INTI), vol. 1, no. 1, 2013. 
[5] 	Jiawei Han, Michelin Kamber, Jian Pei, Data Mining - Concepts and Techniques (3rd Ed), Elsevier Inc, 2012. 



