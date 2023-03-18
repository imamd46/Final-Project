# Travel Insurance Prediction
## 1.	Descriptive Statistics
![info](http://localhost:8891/files/Documents/Rakamin/info%20data.png?_xsrf=2%7C6c5fc4a0%7Cc78ba531a75a9a980d9d7583b6a1f3b8%7C1678889168)
Pada gambar diatas tentang info data tidak terdapat data yang *null* lalu terdapat kolom **Unnamed: 0** yang dirasa tidak terlalu dibutuhkan

![desc](http://localhost:8891/files/Documents/Rakamin/describe.png?_xsrf=2%7C6c5fc4a0%7Cc78ba531a75a9a980d9d7583b6a1f3b8%7C1678889168)

nilai *mean* dan *median* pada setiap kolom tidak terlalu jauh berbeda yang berarti tidak ada *skew* pada data

![boxplot](http://localhost:8891/files/Documents/Rakamin/Boxplot.png?_xsrf=2%7C6c5fc4a0%7Cc78ba531a75a9a980d9d7583b6a1f3b8%7C1678889168)

Jika dilihat dari *Boxplot* data numerik nya tidak terdapat sebuah *outlier* dari data maka dapat disimpulkan data sudah bersih

## 2.	Univariate Analysis 
![univariate](http://localhost:8891/files/Documents/Rakamin/Univariate.png?_xsrf=2%7C6c5fc4a0%7Cc78ba531a75a9a980d9d7583b6a1f3b8%7C1678889168)

**Insight :**
- Grafik Employment
Terdapat 2 kategori pada fitur Employement yaitu Government Sector dan Private Sector dimana Private Sector mendominasi data customer secara keseluruhan.
- Grafik Graduate
Pada status Gelar, customer yang berstatus Sarjana lebih banyak daripada customer yang bukan Sarjana.
- Grafik Frequent Flyer
Ternyata, mayoritas customer termasuk orang yang tidak sering bepergian.
- Grafik Ever Travelled Abroad
Pada dataset ini, customer yang pernah melakukan perjalanan keluar negeri ternyata lebih sedikit dibanding yang belum pernah.
- Grafik Travel Insurance Holder (Target)
Customer yang menyatakan no atau tidak menggunakan produk travel insurance lebih banyak daripada customer yang menyatakan yes. Sekitar 36% orang telah membeli asuransi perjalanan, sedangkan hanya 64% orang yang belum membeli asuransi. Selain itu, kita juga dapat menyimpulkan bahwa kumpulan data sedikit imbalance.

## 3.	Multivariate Analysis
**Distribusi Variabel kategori dengan Target**

![Multi](http://localhost:8891/files/Documents/Rakamin/multi.png?_xsrf=2%7C6c5fc4a0%7Cc78ba531a75a9a980d9d7583b6a1f3b8%7C1678889168)

Secara Singkat dapat diketahui dari visualisasi mayoritas data berdasarkan rasio jumlah tiap kategorinya bahwa Customer yang menggunakan Travel Insurance adalah Customer dengan kategori Sarjana, tidak memiliki penyakit kronis, bekerja di Private Sector, tidak sering bepergian, dan belum pernah keluar negeri. kategori Customer tersebut merupakan kategori-kategori dengan penggunaan Travel Insurance yang banyak.

**Korelasi Variabel kategori dengan Target**

![corr](http://localhost:8891/files/Documents/Rakamin/corr.png?_xsrf=2%7C6c5fc4a0%7Cc78ba531a75a9a980d9d7583b6a1f3b8%7C1678889168)

Variabel kategori Heatmap yang berkorelasi dengan fitur target:
- variabel EverTravelledAbroad, FrequentFlyer dan Employment Type

Variabel kategori Heatmap yang kemungkinan berkorelasi dengan fitur lainnya:
- variabel EverTravelledAbroad dengan FrequentFlyer
- variabel EverTravelledAbroad dengan Employment Type
- variabel Employment Type dengan GraduateOrNot
- variabel FrequentFlyer dengan Employment Type

**sebagian besar berkorelasi kecil, perlu dibuktikan kembali dengan analisis lanjutan, seperti analisis regresi atau uji hipotesis.** 
