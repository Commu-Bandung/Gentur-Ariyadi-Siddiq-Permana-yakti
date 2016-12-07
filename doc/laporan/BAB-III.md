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
Identifikasi | ...
------------- | -------------
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
Identifikasi| 
------------- | -------------
Nomor | UC-02
Nama | View hasil review proposal
Tujuan | Melihat diterima/ditolaknya proposal dari perusahaan
Deskripsi | Melihat hasil review proposal dari perusahaan
Aktor | Anggota
Skenario | ...
Kondisi awal | Menampilkan hal.utama anggota pilih review proposal
Aksi Aktor | Reaksi Sistem
1.	Meminta halaman view hasil review proposal | 2.	Menampilkan halaman view hasil review proposal 

