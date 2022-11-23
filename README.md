# Algoritma-K-Modes
Pada Dunia nyata, data mungkin memiliki tipe yang berbeda, seperti data numerik dan kategorik. Untuk melakukan analisis *cluster*, kita harus mempertimbangkan tipe data yang kita miliki. Algoritma *clustering* yang biasa digunakan dalam teknik pengelompokan dan efisien digunakan untuk data besar adalah K-Means. akan tetapi algoritma K-Means hanya bisa digunakan untuk data numerik. Jadi, Huang pada tahun 1998 mengusulkan algoritma yang disebut K-Modes untuk menangani algoritma pengelompokan dengan tipe data kategorik. K-Modes pertamakali dipublikasikan oleh (Huang 1998) yang merupakan metode pertama yang dapat mengelompokan data kategorik. Pendekatan K-Modes merupakan hasil modifikasi dari K-Means standar untuk mengklasterisasi data kategoris dengan mengantikan fungsi jarak Euclidean dengan jarak mismatching. Algoritma K-Means hanya dapat bekerja dengan baik untuk set data yang tipe datanya numerik (interval atau rasio), namun tidak dapat digunakan untuk fitur kategorikal (nominal atau ordinal). Permasalahan yang terjadi pada K-Means ini terbatas pada penggunaan data bertipe numerik karena pengelompokan yang dilakukan K-Means dengan cara menghitung rata-rata dari suatu data dengan data yang lain. Untuk Menyelesaikan maslah tersebut K-Modes melakukan modifikasi pada K-Means sebagai Berikut:

1.  Menggunakan ukuran pencocokan ketidakmiripan sederhana pada fitur data bertipe kategorikal

2.  mengganti mean cluster dengan modus (nilai yang sering muncul)

3.  menggunakan metode partisi berbasis frekuensi untuk mencari modus dari sekumpulan data

Andaikan **X** dan **Y** adalah dua dara dengan variabel bertipe kategorik, ukuran ketidak miripan diantara **X** dan **Y** dapat diukur dengan jumlah ketidakcocokan nilai dari fitur yang berkorespondensi dari dua data. Semakin kecil nilai ketidakcocokan, maka semakin mirip data tersebut. matriks seperti ini sering disebut dengan pencocokan sederhana atau *simple matching (Prasetyo, 2014)
