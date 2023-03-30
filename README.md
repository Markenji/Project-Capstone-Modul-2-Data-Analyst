# Project Capstone Modul 2 Data Analyst 

## US Youtube Trending Data / (Data Youtube yang Trending di US)

Pada project capstone ke-2 yang bertema Data Analyst dimana kami bebas menentukan masalah dan menyelesaikannya menggunakan data yang telah diberikan. Disini kami dituntun untuk bisa mencari Insight yang ada pada data kemudian memberikan Kesimpulan dan Rekomendasi berdasarkan apa yang kami temukan pada data itu sendiri. Data yang digunakan adalah data berisikan data video trending yang ada di negara US 



## Konten Utama

 - [Main Project ipynb : US Youtube Trending Data](https://github.com/Markenji/Project-Capstone-Modul-2-Data-Analyst/blob/main/Capstone%20Project%202%20Youtube%20(4).ipynb)  
![Pandas License](https://img.shields.io/badge/pandas-1.4.2-lightgrey)  
![Pandas License](https://img.shields.io/badge/numpy-1.23.2-yellow)  
![Pandas License](https://img.shields.io/badge/seaborn-0.11.2-blue)  
![Pandas License](https://img.shields.io/badge/matplotlib-3.5.1-red)

 - [Main Project tableau Story : US Youtube Trending Data](https://public.tableau.com/app/profile/adha.ozy.prima.dewangga7190/viz/StoryCapstone2Tableau/StoryCapstone2_1?publish=yes)

## Daftar Isi Main Project ipynb
 - [Latar Belakang](#Latar-Belakang)
 - [Pernyataan Masalah](#Pernyataan-Masalah)
 - [Data](#Data)
 - [Data Understanding and Data Cleaning](#Data-Understanding-and-Data-Cleaning)
 - [Data Visualisation](#Data-Visualisation)
 - [Statistics](#Statistics)
 - [Data Analysis](#Data-Analysis)
 - [Kesimpulan dan Rekomendasi](Kesimpulan-Rekomendasi)

## Main Project Capstone Modul 2 Data Analyst ipynb

### Latar Belakang

 - Youtube ingin menyaring beberapa youtuber lokal di negara US guna mengoptimalkan potensi konten kreator local. Nantinya youtuber lokal yang akan di ikutkan ke dalam Kampanye produk-produk yang akan datang.
 - Serta Youtube ingin mengoptimalkan iklan pada tipe tipe konten tertentu agar Adsen menjadi maksimal sehingga menguntungkan kedua belah sisi (konten kreator lokal di US dan penguna jasa Google Adsense).

### Pernyataan Masalah
 - Youtube ingin membuat kampanye yang akan melibatkan konten kreator yang akan membantu youtube dalam meningkatkan performa dan pendapatan youtube melalui program yang telah direncanakan. Untuk itu perlu dilakukan penyaringan konten kreator/youtuber lokal di US yang layak menjadi brand ambasador kedepanya.
 - Youtube ingin mencari cara mengoptimasi iklan pada setiap jenis video pada youtube yang trending. Sehingga tepat dalam memberikan iklan sehingga optimasi iklan yang melalui google adsen akan lebih optimal dimana ini akan mengguntungkan dari kedua belah pihak. Yang menjadi pertanyaan apakah jumlah tags , likes, describsi, publish_time, dan comments menjadi pengaruh besar banyak tidaknya views sehingga menentukan trending tidak suatu video. 

### Data
    - JSON File (US_kategori_id.json)
    - CSV File (USvideos.csv)
### Data Understanding and Data Cleaning
 - Data Understanding
    - Menggabungkan 2 data set json dan csv
    - Melihat tipe data untuk setiap kolum
    - Melakukan pengecekan nilai unik pada tiap kolum
 - Data Cleaning
    - Mengecek ada tidaknya NaN pada tiap kolum
    - Merubah Data Nan Menjadi data isi dengan tulisan kosong
    - Mencari string dalam bentuk None pada seluruh data set
    - Merubah column 'comments_disabled', 'ratings_disabled','video_error_or_removed' menjadi nilai bolean
    - Ditambahkan 4 kolum tambahan yaitu kategori, tag_1, Description_1,  avg_channel_views, dan label_trending

### Data Visualisation
 - Penilaian Normalitas
    - Grapical Methods
    ![alt text](https://github.com/Markenji/Project-Capstone-Modul-2-Data-Analyst/blob/main/Tableau/Dashboard%201%20Distribusi%20.png?raw=true)
    
### Statistics
 - Frequentist Test
    - Untuk mengetahui karakteristik dari 'views', 'likes', 'dislikes', 'comment_count', 'avg_channel_views' maka kita akan melihat distribusi datanya menggunakan uji Normalitas D'Agostino and Pearson's Test.
### Data Analysis
 - Apa yang menjadi faktor - faktor tolak ukur viewer banyak pada video yang trending sehingga pengiklanan menjadi lebih maksimal dan cara menentukan apakah konten kreator itu memenuhi syarat menjadi brand ambasador ?
    - Apakah tags , likes, publish_time, and comments memiliki korelasi satu sama lain ?
    - Apakah ada tidaknya describsi mempengaruhi viewer pada video yang di publish di Negara US ?
    - Apakah ada tidaknya tags mempengaruhi viewer pada video video yang di publish di Negara US ?
    - Berapa lama waktu yang diperluhkan agar video menjadi trending di Negara US?
    - Apakah banyak atau sedikitnya comments mempengaruhi viewer pada video yang di     publish di Negara US sehingga menjadi trending ?
    - Pada Negara US konten dengan kategori apa yang paling trending dan yang tidak ?
    - Apakah tindakan disabled pada comments, ratings, dan video_error_or_removed mempengaruhi rank videe yang di publish di Negara US?
    - Cara menentukan apakah seorang konten kreator cocok menjadi brand ambasador di Negara US ?
    
### Kesimpulan dan Rekomendasi
 - Kesimpulan
    - Dari analisis yang telah dilakukan, kita bisa membuat kesimpulan tentang kriteria pemilihan brand ambasador pada Negara US
    - Pola video yang trending dan tidak trending pada video yang di publish, terutama pada negara US
 - Rekomendasi
    - Berisikan rekomendasi yang relevan yang didapat melalui pembacaan pada data yang di visualisasikan.



## Tableau Story


 - [Rata-Rata Views Video yang Trending dan Tidak Trending Berdasarkan kategori](#Rata-Rata-Views-Video-yang-Trending-dan-Tidak-Trending-Berdasarkan-kategori)
 - [AVG. Penayangan per Judul Saluran](#AVG.-Penayangan-per-Judul-Saluran)
 - [Views vs Like](#Views-vs-Like)
 - [Tren Peta Pohon atau tidak Tren tergantung pada Kategori](#Tren-Peta-Pohon-atau-tidak-Tren-tergantung-pada-Kategori)
 - [Video Paling Banyak Dilihat berdasarkan Kategori baik Trending maupun Tidak Trendin](#Video-Paling-Banyak-Dilihat-berdasarkan-Kategori-baik-Trending-maupun-Tidak-Trending)
 - [Distribusi Trending Rating berdasarkan jumlah penayangan judul channel](#Distribusi-Trending-Rating-berdasarkan-jumlah-penayangan-judul-channel)


## Tableau Grafik

### Rata-Rata Views Video yang Trending dan Tidak Trending Berdasarkan kategori
![alt text](https://github.com/Markenji/Project-Capstone-Modul-2-Data-Analyst/blob/main/Tableau/Rata-Rata%20Views%20Video%20yang%20Trending%20dan%20Tidak%20Trending%20Berdasarkan%20Category.png?raw=true)
### AVG. Penayangan per Judul Saluran
![alt text](https://github.com/Markenji/Project-Capstone-Modul-2-Data-Analyst/blob/main/Tableau/AVG.%20Views%20per%20Channel%20Tittle%20(1).png?raw=true)
### Views vs Like
![alt text](https://github.com/Markenji/Project-Capstone-Modul-2-Data-Analyst/blob/main/Tableau/Views%20vs%20Like.png?raw=true)
### Tren Peta Pohon atau tidak Tren tergantung pada Kategori
![alt text](https://github.com/Markenji/Project-Capstone-Modul-2-Data-Analyst/blob/main/Tableau/Tree%20Map%20Trending%20or%20not%20Trending%20depends%20on%20Category.png?raw=true)
### Video Paling Banyak Dilihat berdasarkan Kategori baik Trending maupun Tidak Trending
![alt text](https://github.com/Markenji/Project-Capstone-Modul-2-Data-Analyst/blob/main/Tableau/Most%20Views%20%20Video%20by%20Category%20even%20It%20Trending%20or%20Not%20Trending.png?raw=true)
### Distribusi Trending Rating berdasarkan jumlah penayangan judul channel
![alt text](https://github.com/Markenji/Project-Capstone-Modul-2-Data-Analyst/blob/main/Tableau/Distribution%20of%20Trending%20Rating%20based%20on%20the%20number%20of%20channel%20title%20views.png?raw=true)




