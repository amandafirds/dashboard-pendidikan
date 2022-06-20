<h1 align="center"> Implementasi Dashboard Pendidikan Kota Bekasi Dalam Angka </h1>

<p align="justify"> Kota Bekasi Dalam Angka merupakan salah satu publikasi tahunan yang diterbitkan oleh BPS Kota Bekasi. Publikasi ini memuat data dan informasi mulai dari keadaan geografi dan iklim, pemerintahan, perkembangan sosial-demografi sampai dengan keadaan perekonomian Kota Bekasi. Namun, sebagian besar data masih berbentuk tabel, sehingga perlu di visualisasikan lebih lanjut. Visualisasi data adalah teknik mengubah data menjadi bentuk visual. Visualisasi data penting dilakukan agar infirmasi yang terdapat dalam pada data dapat tersampaikan dengan baik kepada orang lain. Dalam penelitian ini dilakukan pembuatan dashboard pendidikan Kota Bekasi dalam angka. Software yang digunakan untuk visualisasi adalah Tableau. Hasil akhir dari penelitian ini berupa publikasi dashboard yang telah dibuat berdasarkan data yang ada. </p>
 
## Data yang digunakan
<p align="justify"> Data yang digunakan adalah data dari publikasi Kota Bekasi Dalam Angka Tahun 2019, 2020, dan 2021 juga data Pendidikan dan indikator IPM yang diperoleh dari BPS Kota Bekasi juga Dinas Pendidikan Kota Bekasi. Dalam membuat dashboard ini dibutuhkan 3 publikasi Kota Bekasi Dalam Angka untuk tahun 2019, 2020, dan 2021 karena publikasi ini diterbitkan setiap tahunnya. Selain Kota Bekasi Dalam Angka, dikumpulkan pula data nilai Angka Partisipasi Murni (APM) dan Angka Partisipasi Kasar (APK) dari tahun 2018 sampai dengan 2020. Kemudian, dikumpulkan pula data Rata-Rata Lama Sekolah yang merupakan salah satu indikator Indeks Pembangunan Manusia (IPM) selama 12 tahun terakhir yaitu dari tahun 2010 sampai dengan 2021.  Publikasi Kota Bekasi Dalam Angka dan juga statistik Pendidikan yakni APM dan APK diunduh dari website resmi BPS Kota Bekasi yaitu https://bekasikota.bps.go.id/. Sedangkan Rata-Rata Lama Sekolah selama 12 tahun terakhir diunduh dari website resmi Dinas Pendidikan Provinsi Jawa Barat yaitu https://sync.disdik.jabarprov.go.id/index.php. </p>

## Tahapan Pembuatan Dashboard
#### Pengumpulan dan Pengelompokan Data
<p align="justify">
Pada tahap ini data APM, APK, dan Jumlah Sekolah yang telah dikumpulkan seperti yang sudah dijelaskan, digabungkan menjadi satu berdasarkan jenjang pendidikan. Kemudian, data RLS dipisahkan karena merupakan data time series. Dalam hal ini, peneliti menggunakan software Mircosoft Excel sebagai sarana untuk pengelompokkan data. Data dikelompokkan berdasarkan jenis data dan tahunnya. Berikut tampilan data yang digunakan: </p>

* Data APM, APK, dan Jumlah Sekolah 
<p align="center">
<img src = "https://github.com/amandafirds/dashboard-pendidikan/blob/master/DataAPKAPM%26JmlSekolah.png" width="350" height="250" />
</p>

* Data Rata-Rata Lama Sekolah (RLS)
<p align="center">
<img src = "https://github.com/amandafirds/dashboard-pendidikan/blob/master/DataRLS.png" width="350" height="250" />
</p>

#### Seleksi Data
<p align="justify">
Seleksi data dilakukan untuk menghilangkan informasi yang tidak dibutuhkan. Terdapat kolom yang tidak dibutuhkan dalam visualisasi yang akan dilakukan. Peneliti juga membuat kolom tahun yang akan digunakan sebagai fitur filter pada dashboard yang akan dibuat. </p>

#### Visualisasi Data
<p align="justify">
Data yang telah melewati tahap seleksi data kemudian dilanjutkan dengan proses visualisasi. Visualisasi dilakukan dengan menggunakan software Tableu. Masing-masing data divisualisasikan ke dalam bentuk yang berbeda-beda. Untuk data pertama yaitu data Angka Partisipasi Murni (APM) dan Angka Partisipasi Kasar (APK) dengan double bar chart. Kemudian untuk data kedua yaitu data jumlah sekolah di Kota Bekasi menurut jenjang pendidikan, divisualisasikan dengan horizontal bar chart. Terakhir, untuk data ketiga yaitu data Rata-Rata Lama Sekolah (RLS) dari tahun 2010 sampai dengan 2021 divisualisasikan dengan line chart. Berikut dijelaskan visualisasi data dalam dashboard. </p>

* Visualisasi Data Jumlah Sekolah 
<p align="center">
<img src = "https://github.com/amandafirds/dashboard-pendidikan/blob/master/VisJumlahSekolah.png" width="350" height="250" />
</p>

<p align="justify">
Data jumlah sekolah di Kota Bekasi menurut jenjang pendidikan di visualisasikan dengan bentuk horizontal bar chart. Alasan memilih visualisasi ini karena agar dapat terlihat perbedaan jumlah sekolah antar jenjang pendidikan. Selain itu, dengan visualisasi ini dapat dengan mudah melihat susunan jumlah sekolah dari yang lebih banyak sampai yang sedikit. Visualisasi data ini dilengkapi dengan fitur filter yang digunakan untuk menampilkan tahun tertentu yang diinginkan. Filter bersifat multivalues list sehingga dapat menampilkan visualisasi dengan lebih dari satu tahun tertentu.  Visualisasi ini bersifat interaktif yang akan berubah sesuai tahun yang dipilih. </p>

* Visualisasi Data APM dan APK 
<p align="center">
<img src = "https://github.com/amandafirds/dashboard-pendidikan/blob/master/VisAPKAPM.png" width="350" height="250" />
</p>

<p align="justify">
Data Angka Partisipasi Murni (APM) dan Angka Partisipasi Kasar (APK) menurut jenjang pendidikan di Kota Bekasi di visualisasikan dengan double bar chart. Tujuan di visualisasikan dengan double bar chart adalah  untuk mengetahui perbandingan besarnya nilai APK dan APM tiap jenjang pendidikan. Dengan visualisasi ini dapat secara langsung dibandingkan antara nilai APM dengan APK sehingga terlihat jelas perbedaan diantara keduanya. Visualisasi data ini juga dilengkapi dengan fitur filter yang digunakan untuk menampilkan tahun tertentu yang diinginkan. Filter bersifat multivalues list sehingga dapat menampilkan visualisasi dengan lebih dari satu tahun tertentu.  Visualisasi ini bersifat interaktif yang akan berubah sesuai tahun yang dipilih. </p>

* Visualisasi Data Rata-Rata Lama Sekolah (RLS)
<p align="center">
<img src = "https://github.com/amandafirds/dashboard-pendidikan/blob/master/VisRLS.png" width="350" height="250" />
</p>

<p align="justify">
Data Rata-Rata Lama Sekolah (RLS) Kota Bekasi dari tahun 2010 sampai dengan 2021 yang di visualisasikan dengan line chart. Alasan memilih visualisasi ini karena untuk data time series, visualisasi menggunakan line chart lebih efektif karena pola naik atau turun dapat terlihat dengan jelas dengan visualisasi ini. Visualisasi data RLS bersifat statis atau tetap. </p>

#### Pembuatan Dashboard
<p align="justify">
Setelah seluruh data di visualisasikan selanjutnya adalah menyatukan seluruh visualisasi tersebut dalam dashboard. Dashboard tidak boleh mengandung hal yang sangat menarik perhatian atau mencolok sehingga informasi pada visualisasi data tidak tersampaikan dengan baik. Ukuran dashboard yang digunakan adalah ukuran yang disediakan oleh Tableau, yaitu Desktop Browser dengan ukuran 1000x800 pixel. Ukuran ini dipilih karena sangat tepat untuk menampung semua visualisasi sehingga dapat memudahkan user yang melihat dashboard. Hal ini memudahkan karena tidak terdapat scrollbar, baik itu horizontal maupun vertical, karena tidak perlu mengerahkan usaha lebih. Untuk membuat dashboard menjadi lebih menarik, dashboard dirancang dengan menggunakan palette color yang sama yaitu blue palette color. Berikut tampilan dashboard yang telah dibuat. </p>

<p align="center">
<img src = "https://github.com/amandafirds/dashboard-pendidikan/blob/master/Dashboard.png" width="350" height="250" />
</p>

<p align="justify">
Dashboard juga dilengkapi dengan filter. Pengguna dapat memilih tahun yang sesuai dengan keinginannya. Selain itu, filter bersifat multivalues list sehingga dapat menampilkan visualisasi dengan lebih dari satu tahun tertentu yang dipilih. Dengan fitur ini, informasi yang ada dapat tersampaikan dengan baik kepada pengguna. Berikut tampilan fitur filter yang terdapat pada dashboard. </p>

<p align="center">
<img src = "https://github.com/amandafirds/dashboard-pendidikan/blob/master/FilterTahun.png" width="200" height="250" />
</p>

## Publikasi Dashboard
<p align="justify">
Langkah terakhir yang dilakukan adalah mempublikasikan dashboard. Dalam hal ini, publikasi dilakukan dengan memanfaatkan fitur yang ada di Tableau, yaitu publikasi dengan Tableau Public. Hasil publikasi dapat diakses melalui link berikut: (https://public.tableau.com/app/profile/amanda.firdaus/viz/projectuas/Dashboard1?publish=yes) </p>
