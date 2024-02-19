# Capstone-Project-Module-3

**Context**

Tempat tinggal menjadi salah satu faktor pertimbangan seseorang untuk tinggal di wilayah tersebut. Dalam memilih tempat tinggal, pastinya banyak orang yang memilih letak yang strategis, transportasi yang dekat dan mudah ditemukan, jarak yang ditempuh antara tempat tinggal dengan kantor atau kampus, dan masih banyak lagi. Apartemen menjadi salah satu pertimbangan seseorang untuk tinggal. Korea Selatan merupakan salah satu negara yang memiliki mayoritas penduduknya tinggal di apartemen daripada di perumahan. 

Terletak di wilayah tengah selatan semenanjung Korea, [Daegu](https://www.gone2korea.com/popular-destinations-daegu/#:~:text=Daegu%20is%20well%20known%20for,fantastic%20festivals%20throughout%20the%20year.) adalah kota kerah putih dengan industri teknologi tinggi yang berkembang pesat. Kota ini juga memiliki industri fashion yang sangat maju, sehingga dijuluki sebagai 'ibu kota fashion Korea'. Daegu juga merupakan rumah bagi tim bisbol paling produktif di Korea dan memiliki reputasi yang kuat sebagai salah satu kota paling ramah di negara ini. Terkenal dengan musim panasnya yang panas dan lembap, lokasi geografis Daegu menjadikannya tempat utama untuk petualangan akhir pekan.  Selain Seoul, Daegu menjadi salah satu wilayah yang banyak diminati oleh banyak orang, termasuk orang asing. Bukan hanya sebagai pengunjung, tetapi ada juga orang yang datang ke Daegu sebagai pekerja. Daegu merupakan kota terbesar keempat di Korea Selatan yang menyenangkan dan progresif dengan pasar obat tradisional yang menarik, kawasan pusat bersejarah yang penuh dengan warisan budaya, gereja-gereja tua, dan tempat tinggal misionaris, beberapa pilihan makan yang luar biasa dan pusat kota yang ramai dan menyenangkan untuk dijelajahi. Kota ini merupakan tempat yang populer bagi pertukaran pelajar dan guru. Meskipun biaya hidup sehari-hari jauh lebih rendah dibandingkan Seoul, Daegu masih sedikit lebih mahal dibandingkan kota-kota kecil di Korea. Pada umumnya, individu akan mencari apartemen yang murah untuk menjaga kestabilan biaya hidup yang dikeluarkan. 

**Problem Statement and Goals**

 Individu atau perusahaan biasanya membuat penawaran apartemen (unit). Penawar dapat menjual unit di platform dengan menentukan harga apartemen mereka. Dengan begitu cukup sulit bagi pemilik apartemen untuk menyesuaikan dengan harga pasar. Jika harganya terlalu tinggi dibandingkan dengan harga pasar, tentu akan sulit untuk melakukan penjualan. Sebaliknya, jika terlalu rendah, pemilik akan kesulitan untuk mendapatkan keuntungan maksimal. 

 Daegu juga menjadi salah satu wilayah yang banyak diminati oleh wisatawan atau orang asing untuk bekerja atau bertukar pelajar. Berdasarkan data [Populasi terdaftar di Daegu](https://www.daegu.go.kr/english/index.do?menu_id=00939612) memiliki angka yang lebih kecil 1,37% dibandingkan jumlah penduduk tahun sebelumnya. Menurunnya jumlah penduduk dapat menjadi salah satu alasan menurunnya minat terhadap pembelian apartemen. Harga apartemen juga berperan penting terhadap penjualan apartemen, dimana harga dapat ditentukan berdasarkan tipe unit, lokasi, fasilitas, dan lain-lain. 

 Oleh karena itu, diperlukan penelusuran dalam menentukan antara harga yang akan diberikan penjual dan harga yang diminati oleh pembeli. Untuk menentukan harga apartemen dibutuhkan sebuah model yang dapat memprediksi harga apartemen yang dapat mengimbangi antara pembeli dan penjual sehingga masing-masing stakeholder mendapatkan keuntungan dalam proses jual-beli apartemen. 


 **Analytic Approach**

Penetuan harga apartemen dapat dilakukan analisis data pada data apartemen Daegu yang tersedia, melalui masing-masing fasilitas yang diberikan terhadap unit apartemen. Model yang digunakan yaitu model regresi dimana model ini dapat memprediksi harga apartemen yang sesuai berdasarkan fasilitas yang ada. Hal ini dapat mengetahui fasilitas mana yang memiliki nilai pengaruh yang tinggi terhadap harga apartemen.


**Metric Evaluation**

Memprediksi harga apartemen dapat dilakukan evaluasi dengan menggunakan metrik Rooth Mean Square Error (RMSE), Mean Absolute Error (MAE), dan Mean Absolute Percentage Error (MAPE). Hasil perhitungan metrik tersebut dapat memberikan keakuratan dalam memprediksi harga apartemen, apabila nilai metrik yang dihasilkan semakin kecil, maka prediksi harga apartemen akan semakin akurat. Apabila hasil akhir model yang diperoleh merupakan model linear, maka dapat menggunakan evaluasi metrik R-Squares atau adj. R-Squared. Hasil metrik ini akan memberikan nilai yang menentukan seberapa baik model bekerja, dimana jika nilai semakin mendekati 1, maka semakin baik pula model tersebut bekerja.


**Attributes Information**

| **Attribute** | **Description** |
| --- | --- |
| Hallway Type | Apartment type |
| TimeToSubway | Time needed to the nearest subway station |
| SubwayStation | The name of the nearest subway station |
| N_FacilitiesNearBy(ETC) | The number of facilities nearby |
| N_FacilitiesNearBy(PublicOffice) | The number of public office facilities nearby |
| N_SchoolNearBy(University) | The number of universities nearby |
| N_Parkinglot(Basement) | The number of the parking lot |
| YearBuilt |The year the apartment was built |
| N_FacilitiesInApt | Number of facilities in the apartment|
| Size(sqf) | The apartment size (in square feet) |
| SalePrice | The apartment price (Won) |


<br>
