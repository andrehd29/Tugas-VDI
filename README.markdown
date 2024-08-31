---
jupyter:
  colab:
  kernelspec:
    display_name: Python 3
    name: python3
  language_info:
    name: python
  nbformat: 4
  nbformat_minor: 0
---

::: {.cell .markdown id="4D-OPCvHfpmz"}
### Andre Hadiman Rotu Parhusip

### 122450108 {#122450108}

### RC

**Resume Jurnal Berjudul Making Data Visualization More Efficient and
Effective: a Survey**

Jurnal ini membahas pembuatan visualisasi data yang efektik dan efisien
dengan berbagai metode yang dilakukan dan fitur-fitur yang lebih
menguntungkan itu apa saja. Pada dasarnya visualisasi data adalah alat
yang kuat untuk mengubah data abstrak menjadi bentuk visual yang dapat
dipahami manusia. Dengan semakin banyaknya data yang tersedia, berbagai
institusi kini menggunakan visualisasi data untuk memberikan gambaran
umum dan memudahkan interpretasi hasil analitik, mendukung keputusan
strategis dan operasional. Kemudian, terdapat 5 alur dalam visualisasi
data, yaitu:

1.  Data Import, mengambil data dari sumber data.
2.  Data Preparation, mempersiapkan data yang diimpor untuk
    divisualisasikan.
3.  Data Manipulation, memanipulasi data dengan bahasa manipulasi data
    seperti penggabungan dan pengelompokan.
4.  Mapping, memetakan data yang diperoleh dengan proses menghubungkan
    data dari sistem ke format sistem lainnya.
5.  Rendering, mengubah data geometri di atas menjadi representasi
    visual.

Berdasarkan alur kerja di atas dapat diidentifikasi tiga arah membuat
visualisasi data lebih efisien dan efektif, yaitu:

1.  Spesifikasi Visualisasi: berbagai bahasa visualisasi telah
    dikembangkan untuk membantu pengguna menentukan apa yang ingin
    mereka lihat dalam visualisasi.
2.  Pendekatan Efisien untuk Visualisasi Data: mengintegrasikan mesin
    pemrosesan data dengan alat visualisasi, serta mengembangkan solusi
    perkiraan dan progresif untuk menangani data dalam jumlah besar.
3.  Rekomendasi Visualisasi: Menyediakan rekomendasi visualisasi yang
    relevan dan otomatis berdasarkan spesifikasi atau referensi yang
    diberikan oleh pengguna.

Spesifikasi Visualisasi Data Pada dasarnya bahasa visualisasi data
terdiri dari tiga bagian, data, tanda, dan pemetaan di antara keduanya.

Kategori Bahasa Visualisasi Data Bahasa yang digunakan tergantung
kebutuhan dalam penggunaan. Semakin rendah level suatu bahasa, semakin
ekspresif bahasa tersebut. Terdapat bahasa tingkat rendah dan bahasa
tingkat tinggi. Bahasa tingkat tinggi itu merangkum detail konstruksi
visualisasi.

Operasi Visual Berbasis GUI Tujuan membahas operasi visual ini adalah
untuk menunjukkan berbagai cara yang dapat ditentukan oleh pengguna
visualisasi. Daftar alat berbasis GUI yang canggih, yaitu Tableau, Qlik,
Excel, Google Sheets, Amazon Quick-sight, Microsoft Power BI, Google
Fusion Tables, iVisDesigner, Lyra, Keshif, dan Data Illustra-tor.

DeepEye dan Voyager memungkinkan eksplorasi aspek dan membantu pengguna
menavigasi visualisasi dengan mudah.

1.  Stepwise Query Refinement Polaris dan Tableau menyediakan template
    grafik untuk menunjukkan visualisasi multidimensi.
2.  Navigasi Bersegi DeepEye mendukung navigasi bersegi untuk membantu
    pengguna menjelajahi ruang desain visualisasi.

Terjemahan Kueri cara alami untuk menggunakan kembali banyak sistem
(DBMS) yang sudah matang adalah menerjemahkan kueri visualisasi ke kueri
yang diterima oleh sistem tersebut. Misalnya, DeepEye, Polaris, SeeDB
mendapatkan data dengan mengeluarkan kueri SQL ke basis data.

Mengintegrasikan Sistem Visualisasi dengan DBMS Penyimpanan Kolom, dalam
manajemen data, kinerja utama faktornya adalah tata letak data, misalnya
berbasis baris dan berbasis kolom tata letak, yang mungkin memiliki
perbedaan kinerja yang sangat besar untuk Aplikasi OLAP. Indeks, indeks
banyak digunakan untuk meningkatkan kinerja pencarian dengan mengurangi
jumlah rekaman/baris dalam tabel yang perlu diperiksa.

Komputasi Paralel, Komputasi paralel juga telah banyak digunakan untuk
pemrosesan kueri dalam sistem visualisasi data. Kueri agregasi pada
petak data di imMens diparalelkan menggunakan representasi indeks padat
dari petak data. SeeDB mengeksekusi beberapa kueri SQL kandidat
visualisasi secara paralel selama pemeringkatan visualisasi. Arsitektur
ini mempertahankan utas aplikasi utama untuk menangkap permintaan
interaksi pengguna dan beberapa utas visualisasi untuk setiap
visualisasi guna memproses visualisasi utas ini.

Prediksi dan Prapengambilan adalah salah satu langkah penting
visualisasi data adalah eksplorasi data---pengguna terus menelusuri
visualisasi yang mereka minati untuk mendapatkan gambaran tentang apa
yang akan divisualisasikan.

2 Kategori teknologi prefetch dan prediksi, berdasarkan:

1.  Visualisasi yang Sedang Dieksplorasi. Contoh alatnya XmdvTool yang
    di mana mengelompokkan tupel dalam tingkat kehalusan yang berbeda
    untuk mendukung navigasi user.
2.  Data Historis. Ketika data historis tersedia, tentu saja, sistem
    dapat melakukan inferensi yang lebih rumit namun bermakna daripada
    memilih arah secara acak.

Kyrix adalah sistem visualisasi data interaktif yang dapat diskalakan.
Kyrix menyediakan antarmuka spesifikasi visualisasi deklaratif di
front-end dan pemrosesan visualisasi yang efektif dan dapat diskalakan
di back-end, di mana pengguna memperbesar tampilan untuk melihat
informasi terperinci dan memperkecil tampilan untuk melihat gambaran
umum dalam visualisasi yang dapat diskalakan.

Visualisasi Data Perkiraan Berbasis AQP Cara mudah untuk menghasilkan
visualisasi perkiraan dalam waktu interaktif adalah memanfaatkan teknik
AQP. Menggunakan subset representatif dari data dapat memberikan
pengguna visualisasi perkiraan untuk interaksi online dengan
mengorbankan kualitas. Sample+Seek adalah sistem AQP untuk menjawab
visualisasi yang dihasilkan dari kueri agregasi dalam kecepatan
interaktif, dan hasil visualisasi berada dalam batas kesalahan yang
ditentukan oleh pengguna.

Pengambilan Sampel Inkremental Beberapa karya mencoba menghubungkan
teknik pengambilan sampel data inkremental dengan visualisasi data.

SampleAction adalah alat untuk memvisualisasikan kueri agregasi pada
kumpulan data yang sangat besar. Dengan adanya kueri, SampleAction
dengan cepat merespons pengguna dengan hasil agregasi parsial untuk
setiap kelompok dengan batasan kesalahan (misalnya, diagram batang
dengan batasan keyakinan) berdasarkan sampel tetap.

IFocus, sebuah algoritma pengambilan sampel online, dapat menghasilkan
diagram batang perkiraan dengan cepat dan menjamin urutan berpasangan
setiap batang dalam diagram batang, karena urutan berpasangan dalam
diagram batang merupakan fokus persepsi manusia yang penting.

Visualisasi Data Progresif Pengelompokan Berbasis Rentang, Pengguna
dapat menjelajahi data dalam level yang berbeda dan mengubah resolusi
visualisasi yang sedang dijelajahi dengan memperbesar atau memperkecil
tampilan, dan kemudian, sistem akan mengubah ukuran bin agregasi yang
mendasarinya sesuai dengan itu.

Rekomendasi Visualisasi Terdapat pengelompokkan HETree-R dan HETree-C
dalam kasus pengelompokkan atribut usia.

Pemeringkatan Visualisasi Berbasis Pembelajaran Mesin Machine Learning
menjadi salah satu algoritma yang dipakai untuk memvisualisasikan suatu
data. DeepEye mengembangkan solusi berbasis pembelajaran esin yang
menangkap pengetahan desain visualisasi secara otomatis.

Rekomendasi Berbasis Perilaku HARVEST adalah sistem rekomendasi
visualisasi berbasis perilaku. Sistem ini merekomendasikan visualisasi
berdasarkan tugas pengguna yang disimpulkan dari perilaku mereka.
HARVEST dapat merekomendasikan visualisasi berdasarkan pola pengguna
yang disimpulkan.

Rekomendasi yang Dipersonalisasi Model Linier VizDeck memberikan hasil
rekomendasi visualisasi yang dipersonalisasi dengan melatih model linier
untuk setiap pengguna menggunakan perilaku historis mereka.

Jurnal ini memberikan survei komprehensif tentang teknik yang digunakan
untuk meningkatkan efisiensi dan efektivitas visualisasi data, serta
membahas tantangan dan solusi dalam pembuatan visualisasi data yang
lebih baik.

Rekomendasi berbasis perilaku dapat merekomendasikan visualisasi
alizations berdasarkan tugas yang disimpulkan, tetapi terbatas pada pola
perilaku yang telah ditentukan sebelumnya, sehingga tidak fleksibel bagi
pengguna perilaku acak.
:::
