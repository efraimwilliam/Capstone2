# Capstone2
<h1>Capstone 2 - New York City TLC Trip Records</h1>

![image_alt](https://github.com/efraimwilliam/Capstone2/blob/main/NYC%20Taxi.jpg?raw=true)

<h3>Company Overview</h3>
Komisi Taksi dan Limusin Kota New York (TLC) adalah lembaga yang bertanggung jawab untuk memberikan lisensi dan mengatur operasional taksi medali, kendaraan sewaan (FHV), kendaraan paratransit, dan van komuter di Kota New York. Didirikan pada tahun 1971, TLC memastikan layanan transportasi yang aman, efisien, dan dapat diakses bagi jutaan penduduk dan pengunjung setiap tahunnya. TLC menetapkan tarif, membuat aturan operasional, serta menegakkan standar pengemudi dan kendaraan untuk menjaga keselamatan publik dan kualitas layanan. TLC memainkan peran penting dalam mengelola lanskap transportasi darat yang beragam di kota ini, mencakup taksi kuning ikonik, mobil hitam, dan layanan ride-sharing.

<h3>Problem Statement & Objective</h3>

1.  Apakah ada perbedaan yang signifikan pada hari kerja dan akhir pekan?
2.  Apakah perbedaanya berpengaruh terhadap tarif taksi di hari kerja serta akhir pekan?
3.  Perbedaan Fare per Kilometer pada Weekdays dan Weekends
4.  Apakah jumlah tip berpengaruh pada hari kerja serta akhir pekan?
5.  Dimanakah letak lokasi terbanyak yang menggunakan taxi pada hari kerja serta akhir pekan
6.  Apakah ada perbedaan signifikan dalam peringkat tip_amount untuk perjalanan yang diambil pada jam sibuk pagi dibandingkan dengan jam sibuk sore hari, dari lokasi penjemputan yang sama (PULocationID)?

<h3>Kesimpulan dan Rekomendasi</h3>

1. Karena adanya perbedaan dari trip_per_km pada weekdays dan weekends, maka perusahaan dapat melakukan tinjauan terhadap strategi penetapan harga akhir pekan. Mungkin bisa menambahkan promo yang dapat menarik pengunjung agar menggunakan taxi, mengingat dari data, pengguna yang menggunakan taxi pada weekedays dibanding weekends juga lumayan jauh.
2. Untuk meningkatkan kepuasan pelanggan, perusahaan dapat melakukan adjust/optimalisasi tarif Fare per Kilometer khususnya pada jarak pendek. Hal ini perlu dilakukan untuk meningkatkan minat pelanggan dalam menggunakan Taxi meskipun dengan jarak yang pendek. Optimalisasi seperti penurunan Fare per Kilometer untuk jarak yang rendah dapat dilakukan untuk meningkatkan jumlah pelanggan.
3. Karena adanya perbedaan jumlah Fare Per KM yang mana lebih tinggi pada weekday dibanding weekends, maka perlu adanya promosi pada trip wekeends. Karena jika kita melihat dari jumlah data pun, terdapat perbedaan pengguna taxi pada weekdays dan weekends. Tujuannya adalah untuk meningkatkan volume perjalanan pada weekends sehingga revenue dapat meningkat.
4. Mengingat tidak adanya perbedaan signifikan antara tip di hari kerja maupun di pekan hari, pekerja dapat memahami bahwa tip tidak akan berbeda ketika mereka bekerja di pekan hari maupun di hari kerja. Jadi pekerja dapat fokus ke hal lain seperti kesopanan, kenyamanan mobil, serta kualitas layanan mereka.
5. Karena perusahaan telah mengetahui titik Top 10 Pickup Zones, maka perusahaan bisa menggunakan data tersebut untuk menarik lebih banyak revenue, misalnya dengan cara mengadakan promo pada lokasi pickup tertentu atau menambah jumlah pengemudi taxi agar bisa "standby" di sekitar lokasi tersebut baik weekdays atau weekends.
6. Dikarenakan adanya korelasi antara tip_amount dengan jam sibuk pagi hari dan sore hari dengan hasil jumlah tip biasanya lebih besar di sore hari, perusahaan bisa memberikan tip juga kepada pengemudi di pagi hari (morning_peak) sehingga, jumlah taxi yang ada pada pagi hari dan sore hari seiimbang. Jika tidak, maka ada kemungkinan para pengemudi enggan bekerja di pagi hari, mengingat jumlah tip yang dihasilkan tidak sebesar pada sore hari.
