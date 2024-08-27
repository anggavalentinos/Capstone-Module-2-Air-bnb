## **Background**

Bangkok, ibu kota Thailand, merupakan salah satu destinasi wisata paling populer di dunia. Kota ini menawarkan perpaduan unik antara budaya tradisional dan modernitas, yang menarik wisatawan dari berbagai belahan dunia. Dengan meningkatnya jumlah wisatawan setiap tahun, pasar akomodasi di Bangkok, termasuk platform Airbnb, mengalami pertumbuhan yang signifikan.

Airbnb telah menjadi pilihan akomodasi yang populer di kalangan wisatawan karena fleksibilitas dan keragaman pilihan yang ditawarkan. Namun, dengan begitu banyaknya listing yang tersedia, terdapat tantangan bagi tuan rumah dan penyewa untuk menentukan lokasi yang paling strategis. Memahami lokasi-lokasi yang paling populer di Bangkok dapat memberikan wawasan penting bagi para pemilik properti untuk memaksimalkan okupansi dan pendapatan, serta bagi calon penyewa untuk menemukan tempat tinggal yang sesuai dengan preferensi mereka.


## **Problem Statement**

Dengan semakin banyaknya pilihan akomodasi di Bangkok yang tersedia di platform Airbnb, ada kebutuhan untuk memahami faktor-faktor yang mempengaruhi `price`,`room_type`, dan `number_of_reviews` yang diterima oleh masing-masing listing. Penelitian ini bertujuan untuk menjawab beberapa pertanyaan penting:

1. Apa saja faktor utama yang mempengaruhi `price` dari listing Airbnb di Bangkok?
2. Bagaimana `neighbourhood` dan `room_type` mempengaruhi tingkat hunian ?
3. Apakah ada hubungan antara `number_of_reviews` dengan `price` atau `room_type`?
4. Bagaimana pola `availability_365` dan `Term` mempengaruhi performa listing?


## **Data:**

**Dataset ini berisi informasi terkait lokasi, tipe kamar, host, harga, minimal jumlah hari yang disewa, ketersediaan, dan review yang didapat oleh listing**

1. Unnamed : index
2. id: ID unik untuk setiap listing.
3. name: Nama listing.
4. host_id: ID unik untuk setiap host.
5. host_name: Nama host.
6. neighbourhood: Lokasi atau wilayah listing.
7. latitude dan longitude: Koordinat geografis dari listing.
8. room_type: Tipe ruangan yang tersedia (misalnya "Entire home/apt", "Private room").
9. price: Harga per malam.
10. minimum_nights: Jumlah minimum malam untuk menginap.
11. number_of_reviews: Jumlah ulasan yang diterima.
12. last_review: Tanggal ulasan terakhir.
13. reviews_per_month: Rata-rata ulasan per bulan.
14. calculated_host_listings_count: Jumlah listing yang dimiliki oleh host.
15. availability_365: Ketersediaan dalam 365 hari terakhir.
16. number_of_reviews_ltm: Jumlah ulasan dalam 12 bulan terakhir




`Kesimpulan Umum`: Dalam pasar Airbnb di Bangkok, harga, tipe kamar, dan ketersediaan semuanya saling terkait dan memainkan peran penting dalam menentukan popularitas dan jumlah ulasan yang diterima oleh sebuah properti. Pemilik properti yang fokus pada menawarkan nilai yang baik melalui harga kompetitif, tipe kamar yang diinginkan, dan memastikan properti mereka dikelola dengan baik dapat meningkatkan popularitas dan, pada akhirnya, pendapatan mereka. Sewa jangka pendek tetap menjadi segmen pasar yang dominan, dan pemilik harus mempertimbangkan untuk menargetkan pasar ini untuk memaksimalkan jumlah tamu dan ulasan.

## **Solusi tambahan :**

1. Bagaimana cara menyesuaikan harga properti: 
    - Analisis Pasar Lokal
    - Gunakan Harga Dinamis
    - Tetapkan Harga Minimum dan Maksimum
    - Beri Diskon untuk Pemesanan Awal dan Jangka Panjang
    - Manfaatkan Harga untuk Akhir Pekan dan Hari Kerja
    - Pertimbangkan Keunikan Properti

2. Bagaimana cara menarik lebih banyak ulasan positif?
    - Beri Kesan Pertama yang Baik
    - Tingkatkan Kualitas Properti
    - Komunikasi yang Baik Selama Menginap
    - Minta Ulasan dengan Sopan
    - Tanggapi Ulasan
    - Pelajari Ulasan dan Tingkatkan Layanan
    