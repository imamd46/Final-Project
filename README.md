# Travel Insurance Prediction
## 1.	Descriptive Statistics
![info](https://raw.githubusercontent.com/imamd46/Final-Project/main/pic/info%20data.png)

Pada gambar diatas tentang info data tidak terdapat data yang *null* lalu terdapat kolom **Unnamed: 0** yang dirasa tidak terlalu dibutuhkan

![desc](https://github.com/imamd46/Final-Project/blob/main/pic/describe.png?raw=true)

nilai *mean* dan *median* pada setiap kolom tidak terlalu jauh berbeda yang berarti tidak ada *skew* pada data

![boxplot](https://github.com/imamd46/Final-Project/blob/main/pic/Boxplot.png)

Jika dilihat dari *Boxplot* data numerik nya tidak terdapat sebuah *outlier* dari data maka dapat disimpulkan data sudah bersih

## 2.	Univariate Analysis 
![univariate](https://github.com/imamd46/Final-Project/blob/main/pic/Univariate.png)

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

![Multi](https://github.com/imamd46/Final-Project/blob/main/pic/multi.png)

Secara Singkat dapat diketahui dari visualisasi mayoritas data berdasarkan rasio jumlah tiap kategorinya bahwa Customer yang menggunakan Travel Insurance adalah Customer dengan kategori Sarjana, tidak memiliki penyakit kronis, bekerja di Private Sector, tidak sering bepergian, dan belum pernah keluar negeri. kategori Customer tersebut merupakan kategori-kategori dengan penggunaan Travel Insurance yang banyak.

**Korelasi Variabel kategori dengan Target**

![corr](https://github.com/imamd46/Final-Project/blob/main/pic/corr.png)

Variabel kategori Heatmap yang berkorelasi dengan fitur target:
- variabel EverTravelledAbroad, FrequentFlyer dan Employment Type

Variabel kategori Heatmap yang kemungkinan berkorelasi dengan fitur lainnya:
- variabel EverTravelledAbroad dengan FrequentFlyer
- variabel EverTravelledAbroad dengan Employment Type
- variabel Employment Type dengan GraduateOrNot
- variabel FrequentFlyer dengan Employment Type

**sebagian besar berkorelasi kecil, perlu dibuktikan kembali dengan analisis lanjutan, seperti analisis regresi atau uji hipotesis.** 
