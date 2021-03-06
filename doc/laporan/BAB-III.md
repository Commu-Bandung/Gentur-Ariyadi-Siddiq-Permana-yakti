<h1 align="center"><strong> BAB III </br>
ANALISIS DAN PERANCANGAN</strong></h1>
<h3 align="justify"><strong>3.1 Analisis</strong></br></h3>
<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp;Analisis adalah proses untuk menentukan kebutuhan suatu system/aplikasi/alat yang dapat berupa kebutuhan ketika membangun ataupun ketika implementasi. Pada tahap ini bertujuan untuk menganalisis system aplikasi tersebut, prosses-proses yang ada pada aplikasi dan hubungan antar proses. Analisis juga bertugas untuk menguraikan dan menjelaskan komponen –komponen dari sebuah aplikasi yang utuh dengan maksud identifikasi dan evaluasi dari masalah-masalah, hambatan-hambatan, kesemmpatan-kesempatan, yang sudah terjadi dan kebutuhan yang diharapkan sehingga mendapat usulan untuk perbaikan.</p>
<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp;Analisis merupakan langkah awal dari pengembangan atau pembangunan suatu aplikasi, karena  perancangan dan pengembangan aplikasi tidak bisa berjalan dengan baik apabila tidak disertai dengan analisa terhadap aplikasi yang akan digunakan.
&nbsp;&nbsp;&nbsp;&nbsp;Langkah-langkah yang harus dilakukan untuk menganalisis system yaitu:</p>
1.	Identifikasi masalah, langkah ini dilakukan dengan cara mengidentifikasi permasalahan yang ada sehingga sasaran yang diharapkan dapat terlaksana.</br>
2.	Mempelajari kerja dari system yang sedang berjalan, pada langkah ini dilakukan dengan cara mempelajari secara detail jalanya system yang sedang berjalan.</br>
3.	Menganalisis hasil dari penelitian, hal yang harus diperhatikan dalam langkah ini yaitu menganalisis kebutuhan informasi user system berdasarkan data yang didapatkan dari proses penelitian.</br>
4.	Membuat laporan penelitian, langkah ini merupakan langkah akhir dari analisis system, laporan disusun dalam suatu rangkuman dari langkah-langkah sebelumnya.</br>
<h3 align="justify"><strong>3.1.1 Analisis System yang Sedang Berjalan</br>
3.1.1.1	 Analisis Prosedur/Flowmap yang berjalan</strong></h3>
<p align="center"><img src="../../img/laporan/bab 3/sedang berjalan/bpmn bisnis proses yg sedang berjalan.PNG"></br></p>
<p align="center"><i>Gambar 3.1 Bisnis prosses yang sedang berjalan<br>
( bpmn – bizagi modeler – 2016)</i></p></br>

<p align="center"><img src="../../img/laporan/bab 3/sedang berjalan/Sub proses pengajuan proposal.PNG"></br></p>
<p align="center"><i>Gambar 3.2 Sub proses pengajuan proposal<br> 
( bpmn – bizagi modeler – 2016)</i></p></br>

<p align="center"><img src="../../img/laporan/bab 3/sedang berjalan/sub proses review proposal.PNG"></br></p>
<p align="center"><i>Gambar 3.3 Sub Proses review proposal<br>
( bpmn – bizagi modeler – 2016)</i></p></br>

<p align="center"><img src="../../img/laporan/bab 3/sedang berjalan/sub proses partnership.PNG"></br></p>
<p align="center"><i>Gambar 3.4 Sub proses partnership<br>
( bpmn – bizagi modeler – 2016)</i></p></br>


<h3 align="justify"><strong>3.1.1.2 Analisis Dokumen yang digunakan </strong></h3>
<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp; Dalam proses pembuatan aplikasi pencarian sponsor dan partnership ada beberapa document yang digunakan oleh HIMATIF Politeknik Pos Indonesia yaitu:</p>
1.	Dokumen proposal</br>
2.	Dokumen media partner</br>

<h3 align="justify"><strong>3.1.2 Analisis Sistem yang akan dibangun</strong></h3>
<h4 align="justify"><strong> 3.1.2.1 Analisis Prosedur/Flowmap yang akan dibangun </strong></h4>
<p align="center"><img src="../../img/laporan/bab 3/akan dibangun/bisnis proses yang akan dibangun.PNG"></br></p>
<p align="center"><i>Gambar 3.5  Bisnis proses yang akan dibangun</i></p></br>


<h4 align="justify"><strong> 3.1.2.2 Analisis kebutuhan Aplikasi</strong></h4>
<p align="justify"> Aplikasi pencarian sponsor dan partnership ini memudahkan anggota komunitas/ organisasi kampus untuk pengajuan dan penyebaran proposal sponsor. Aplikasi yang dibuat ini dapat memberikan :</p>
1.	Pengelolaan data perusahaan</p>
2.	Pengelolaan data anggota</p>
<h3 align="justify"><strong>3.1.2.2 Analisis Kebutuhan Perangkat Lunak dan Perangkat Keras</strong></h3>
<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp; Spesifikasi perangkat lunak yang dibutuhkan adalah sebagai berikut:</p>
Tabel 3.1 Spesifikasi Perangkat Lunak</br>
<p align="center"><img src="../../img/laporan/bab 3/spesifikasi-p-l.PNG"></br></p>
<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp; Pembuatan aplikasi ini menggunakan perangkat kereas sebagai berikut:</p>
Tabel 3.2 Spesifikasi Perangkat Keras</br>
<p align="center"><img src="../../img/laporan/bab 3/spesifikasi-p-k.PNG"></br></p>
<h3 align="justify"><strong> 3.2 Perancangan</br> 
3.2.1 Use Case Diagram</strong></h3>
<p align="justify">&nbsp;&nbsp;&nbsp;&nbsp;Diagram use case dari aplikasi ini adalah sebagai berikut:</p>
<p align="center"><img src="../../img/laporan/bab 3/uml/usecase.PNG"></br></p>
<p align="center"><i>Gambar 3.6 Use Case Diagram</i></p></br>
Tabel 3.3 Definisi aktor</br>

No| Aktor| Keterangan
------------ | ------------- | -------------
1 | Anggota komunitas | Pengguna apllikasi yang dapat mengakses menu pengajuan proposal pada aplikasi.
2 | Admin | Pengurus aplikasi yang dapat mengakses tindakan pada proposal
3 | Perusahaan | Pengguna aplikasi yang dapat menerima dan menolak pemberian dana sponsor melalui aplikasi
<br>

Tabel 3.4. Definisi Use Case<br>

No| Aktor| Keterangan
------------ | ------------- | -------------
1 | UC-01 Registrasi | Mendaftar menjadi anggota di aplikasi
2 | UC-02 View hasil review proposal | Melihat hasil review proposal dari perusahaan
3 | UC-03 Pengajuan proposal | Proses mengajukan proposal 
4 | UC-04 menerima dana | Menerima dana sponsor dari perusahaan
5 | UC-05 melaksanakan event | Proses melaksanakan event
6 | UC-06  Validasi persyaratan | Mengecek persyaratan proposal
7 | UC-07 Mendistribusikan proposal | Menyebarkan proposal ke perusahaan-perusahaan melalui aplikasi
8 | UC-08 Review proposal | Mereview proposal yang diajukan
9 | UC-09 Memberikan dana | Memberikan dana sponsor kepada organisasi  / komunitas 
10 | UC-10 Menerima feedback | Menerima feedback partnership dari komunitas
11 | UC-11 Partnership | Melakukan kerjasama dengan perusahaan
12 | UC-12 login | Masuk kedalam sistem 
<br>



<h4 align="justify"><strong> 3.2.1.1 Skenario Use Case</strong></h4>
Tabel 3.5 Skenario Use Case Registrasi<br>

Identifikasi| ...
------------ | -------------
Nomor | UC-01 
Nama | Registrasi
Tujuan | Mendata dan membatas pengguna sistem 
Deskripsi | Mendaftar sebagai anggota komunitas disistem
Aktor | Anggota komunitas / organisasi kampus
Skenario |
Kondisi awal | Menampilkan halaman umum, lalu pilih registrasi
Aksi | Reaksi Sistem
1.Actor meminta halaman registrasi | 2.	Menampilkan halaman registrasi
3.	Memasukan identitas diri | 4.	Melakukan proses validasi
<br> 

Tabel 3.6  Skenario Use Case View hasil review proposal<br>

Identifikasi| ...
------------ | -------------
Nomor | UC-02
Nama | View hasil review proposal
Tujuan | Melihat diterima/ditolaknya proposal dari perusahaan
Deskripsi | Melihat hasil review proposal dari perusahaan
Aktor | Anggota
Skenario | ...
Kondisi awal | Menampilkan hal.utama anggota pilih review proposal
Aksi Aktor | Reaksi Sistem
1.	Meminta halaman view hasil review proposal | 2.	Menampilkan halaman view hasil review proposal 
<br>

Tabel 3.7  Skenario Use Case Pengajuan proposal<br>

Identifikasi| ...
------------ | -------------
Nomor | UC-03
Nama | Pengajuan proposal
Tujuan | Mengajukan proposal untuk mengadakan event
Deskripsi | Mengirimkan proposal ke admin untuk di validasi syarat-syaratnya, apabila valid maka dikirim ke perusahaan untuk direview.
Aktor | Anggota
Skenario | ...
Kondisi awal | Menampilkan hal.utama anggota pilih ajukan proposal
Aksi Aktor | Reaksi Sistem
1.	Meminta halaman ajukan proposal | 2.	Menampilkan halaman yang diminta
3.	Masukan proposal | 4.	Menampilkan notifikasi proposal sudah dikirim 
<br>

Tabel 3.8 Skenario Use Case Validasi persyaratan<br>

Identifikasi| ...
------------ | -------------
Nomor | UC-06
Nama | Validasi persyaratan
Tujuan | Mengecek kelengkapan proposal
Deskripsi | Admin mengecek kelengkapan proposal yang diajukan anggota
Aktor | Anggota
Skenario | ...
Kondisi awal | Menampilkan halaman utama aplikasi, lalu mucul notifikasi
Aksi Aktor | Reaksi Sistem
1.	Periksa kelengkaapan, pilih button tolak | 2.	Menampilkan notifikasi ke anggota, dan mengirim pesan bahwa proposal anda tidak lengkap serta alasannya.
3.	Apabila lengkap, pilih button terima | 4.	Masuk ke menu distribusi proposal
<br>

Tabel 3.9 Skenario Use Case distribusi proposal<br>

Identifikasi| ...
------------ | -------------
Nomor | UC-07
Nama | Mendistribusikan proposal
Tujuan | Mengirimkan proposal ke perusahaan
Deskripsi | Admin memilih perusahaan yang akan dikirim proposal 
Aktor | Admin
Skenario | ...
Kondisi awal | menu distribusi proposal
Aksi Aktor | Reaksi Sistem
1.	Pilih perusahaan yang akan dikirim proposal, lalu kirimkan | 2.	Mengirimkan file proposal ke perusahaan yang dituju.
<br>

Tabel 3.10 Skenario Use Case Review proposal<br>

Identifikasi| ...
------------ | -------------
Nomor | UC-08
Nama | Review proposal
Tujuan | Mereview proposal
Deskripsi | Perusahaan menentukan proposal itu diterima atau ditolak 
Aktor | Perusahaan
Skenario | ...
Kondisi awal | Menu utama aplikasi, lalu muncul notifikasi
Aksi Aktor | Reaksi Sistem
1.	Apabila diterima maka tekan tombol terima | 2.	Mengirim notifikasi dan pesan ke anggota bahwa proposal diterima
3.	Apabila ditolak, maka tekan tombol tolak | 4.	Mengirim notifikasi dan pesan ke anggota bahwa proposal ditolak
<br>

Tabel 3.11 Skenario Use Case Login<br>

Identifikasi| ...
------------ | -------------
Nomor | UC-12
Nama | Login
Tujuan | Masuk kedalam system
Deskripsi | Untuk masuk kedalam aplikasi 
Aktor | Perusahaan, admin, anggota
Skenario | ...
Kondisi awal | Halaman umum, pilih login
Aksi Aktor | Reaksi Sistem
1.	User mengisi username dan password | 2.	Menvalidasi, jika benar akan masuk sesuai usernya, apabila salah muncul notifikasi “your account didn’t match”
3.	Apabila ditolak, maka tekan tombol tolak | 4.	Mengirim notifikasi dan pesan ke anggota bahwa proposal ditolak
<br>

<h3><strong>3.2.2 Class Diagram</strong></h3>
&nbsp;&nbsp;&nbsp;&nbsp;<p align="justify">Class Diagram adalah diagram UML yang menggambarkan kelas-kelas 
dalam sebuah sistem dan hubungannya antara satu proses dengan proses yang lain, serta dimasukkan pula atribut 
dan operasi. Class Diagram pada aplikasi sebagai berikut:</p>
<p align="center"><img src="../../img/laporan/bab 3/uml/class diagram.PNG"></br></p>
<p align="center"><i>Gambar 3.6 class diagram</i></p>
<h3><strong>3.2.3 Sequence Diagram</strong></h3>
&nbsp;&nbsp;&nbsp;&nbsp;<p align="justify">Sequence Diagram merupakan penggambaran keterhubungan atau interaksi 
antar objek dalam suatu jangka waktu. Sequence Diagram terutama menampilkan interaksi antara pengguna (user) dengan sistem.</p>
<h4><strong>3.2.3.1 Sequence Diagram Login</strong></h4>
<p align="center"><img src="../../img/laporan/bab 3/uml/sequence diagram/1.Login.jpg"></br></p>
<p align="center"><i>Gambar 3.7 sequence diagram login</i></p>
<p align="justify">Tabel 3.12 Sequence Diagram Login</p>

No| Nama Operasi| Keterangan
------------ | ------------- | -------------
1. |Open |	Membuka system
2. |Tampil form login | 	Sistem menampilkan form login kepada actor
3. |Input username dan password |Aktor mengisikan username dan password yang sudah dibuat
4. |Request |Sistem merequest kepada API
5. |Response |Sistem mendapatkan response dari API
6. |Send form UI utama |Sistem mengirimkan userinterface utama
<br> 

<h4><strong>3.2.3.2 Sequence Diagram Registrasi</strong></h4>
<p align="center"><img src="../../img/laporan/bab 3/uml/sequence diagram/2.registrasi.jpg"></br></p>
<p align="center"><i>Gambar 3.8 sequence diagram registrasi</i></p>
<p align="justify">Tabel 3.13 Sequence Diagram Registrasi</p>

No| Nama Operasi| Keterangan
------------ | ------------- | -------------
1. |Open |	Membuka system
2. |Tampil form registrasi | Sistem menampilkan form registrasi kepada actor
3. |Input identitas |Aktor mengisikan identitas didalam form
4. |Request |Sistem merequest kepada API
5. |Response |Sistem mendapatkan response dari API
6. |Send form UI utama |Sistem mengirimkan userinterface utama
<br> 

<h4><strong>3.2.3.3 Sequence Diagram Pengajuan Proposal</strong></h4>
<p align="center"><img src="../../img/laporan/bab 3/uml/sequence diagram/3.pengajuan proposal.jpg"></br></p>
<p align="center"><i>Gambar 3.9 sequence diagram pengajuan proposal</i></p>
<p align="justify">Tabel 3.14 Sequence Diagram pengajuan proposal</p>

No| Nama Operasi| Keterangan
------------ | ------------- | -------------
1. |Open |	Membuka system
2. |Tampil UI | Sistem menampilkan UI pengajuan proposal kepada actor
3. |Input data |Aktor mengisikan data ke dalam form
4. |Request |Sistem merequest kepada API
5. |Response |Sistem mendapatkan response dari API
6. |Send form UI utama |Sistem mengirimkan userinterface utama
<br> 

<h4><strong>3.2.3.4 Sequence Validasi Persyaratan</strong></h4>
<p align="center"><img src="../../img/laporan/bab 3/uml/sequence diagram/4.validasi persyaratan.jpg"></br></p>
<p align="center"><i>Gambar 3.10 sequence diagram validasi persyaratan</i></p>
<p align="justify">Tabel 3.15 Sequence Diagram validasi persyaratan</p>

No| Nama Operasi| Keterangan
------------ | ------------- | -------------
1.	|Open 	|Membuka system
2.	|Request 	|Sistem melakukan request kepada API
3.	|Response	|System mendapatkan response dari API
4.	|Tampil data pengajuan	|Sistem menampilkan data pengajuan proposal kepada admin
5.	|Pilih aksi 	|Admin memilih aksi untuk menvalidasi persyaratan proposal
6.	|Request	|Sistem mengirimkan request ke API
7.	|Response 	|System mendapatkan response dari API
8.	|Tampilkan data	|System menampilkan data setelah aksi
<br> 

<h4><strong>3.2.3.5 Sequence Distribusi Proposal</strong></h4>
<p align="center"><img src="../../img/laporan/bab 3/uml/sequence diagram/5.distribusi proposal.jpg"></br></p>
<p align="center"><i>Gambar 3.11 sequence diagram distribusi proposal</i></p>
<p align="justify">Tabel 3.16 Sequence Diagram Distribusi proposal</p>

No| Nama Operasi| Keterangan
------------ | ------------- | -------------
1.	|Open 	|Membuka system
2.	|Request 	|Sistem melakukan request kepada API
3.	|Response	|System mendapatkan response dari API
4.	|Tampil data 	|Sistem menampilkan data proposal kepada admin
5.	|Pilih perusahaan 	|Admin memilih perusahaan untuk dikirim proposal
6.	|Request	|Sistem mengirimkan request ke API
7.	|Response 	|System mendapatkan response dari API
8.	|Tampilkan data	|System menampilkan data 
<br> 

<h4><strong>3.2.3.6 Sequence Diagram Review Proposal</strong></h4>
<p align="center"><img src="../../img/laporan/bab 3/uml/sequence diagram/6.review proposal.jpg"></br></p>
<p align="center"><i>Gambar 3.12 sequence diagram review proposal</i></p>
<p align="justify">Tabel 3.17 Sequence Diagram review proposal</p>

No| Nama Operasi| Keterangan
------------ | ------------- | -------------
1.	|Open 	|Membuka system
2.	|Request 	|Sistem melakukan request kepada API
3.	|Response	|System mendapatkan response dari API
4.	|Tampil data 	|Sistem menampilkan data proposal kepada perusahaan
5.	|Pilih aksi 	|perusahaan memilih aksi ke proposal yang diterima
6.	|Request	|Sistem mengirimkan request ke API
7.	|Response 	|System mendapatkan response dari API
8.	|Tampilkan data	|System menampilkan data 
<br> 

<h4><strong>3.2.3.7 Sequence Diagram View Hasil Review Proposal</strong></h4>
<p align="center"><img src="../../img/laporan/bab 3/uml/sequence diagram/7.view hasil review proposal.jpg"></br></p>
<p align="center"><i>Gambar 3.13 sequence diagram view review proposal</i></p>
<p align="justify">Tabel 3.18 Sequence Diagram view review proposal</p>

No| Nama Operasi| Keterangan
------------ | ------------- | -------------
1.	|Open 	|Membuka system
2.	|Request 	|Sistem melakukan request kepada API
3.	|Response	|System mendapatkan response dari API
4.	|Tampil data 	|Sistem menampilkan data hasil review proposal kepada anggota
<br> 







