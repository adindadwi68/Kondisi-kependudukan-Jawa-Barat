
> Proyek ini merupakan proyek pribadi yang menganalisis data kependudukan Jawa Barat, meliputi jumlah penduduk, kelompok pekerjaan, jumlah penduduk miskin, kasus penyakit, dan kematian.

## 📁 Struktur Repository
- `Dataset`— [Dataset mentah yang digunakan](https://github.com/adindadwi68/Kondisi-kependudukan-Jawa-Barat/tree/main/Dataset)
- `Visualization` — [Hasil visualisasi data](https://github.com/adindadwi68/Kondisi-kependudukan-Jawa-Barat/tree/main/Visualisasi)
- `Notebook` — [Notebook analisis menggunakan Python (Jupyter/Colab)](https://github.com/adindadwi68/Kondisi-kependudukan-Jawa-Barat/blob/main/notebook.ipynb)
- `README.md` — Halaman utama repo ini.

## 🛠️ Skillset
### 📊 Data Analysis & Manipulation
- `Pandas`
- `Numpy`
- `Re` (regex untuk cleaning)
- `Math & Textwrap` (penyesuaian data & tampilan)
### 📈 Data Visualization
- `matplotlib.pyplot`
- `seaborn`
- `plotly.express & plotly.graph_objects` (visualisasi interaktif)
- `squarify` (tree map)
- `highlight_text` (annotasi visualisasi)
### 🗄️ Database & Query
`sqlalchemy` (koneksi dan integrasi database)
Query ke MySQL menggunakan `create_engine`
### 📉 Statistik
`scipy.stats.kendalltau` (analisis korelasi)


## 📚 Analisis Kependudukan Jawa Barat
### 📈 Pertumbuhan Penduduk Jawa Barat
- Sejak 2013, laju pertumbuhan penduduk di Jawa Barat menunjukkan tren positif dengan rata-rata sekitar 2% per tahun.
- Tahun 2020 menjadi puncak pertumbuhan (2,97%), kemungkinan besar akibat dampak pandemi COVID-19 (migrasi, perubahan mobilitas).
- Rasio jenis kelamin tahun 2024 menunjukkan ketimpangan ringan (102 laki-laki per 100 perempuan).

### 🏘️ Sebaran Penduduk Antar Wilayah
- Kabupaten Bogor memiliki jumlah penduduk terbanyak (~5,8 juta jiwa).
- Kota Banjar memiliki jumlah penduduk paling sedikit (~200 ribu jiwa).
- Terdapat konsentrasi populasi yang tidak merata antar kabupaten/kota.

### 👷‍♀️ Struktur Pekerjaan Penduduk
- Kelompok terbesar: ibu rumah tangga, wiraswasta, pelajar, dan yang belum bekerja.
- Sejak 2020, jumlah penduduk tidak/belum bekerja meningkat signifikan, diperkirakan akibat dampak pandemi terhadap lapangan kerja.
- Jumlah wiraswasta juga meningkat, terutama sejak 2021, seiring berkembangnya e-commerce, afiliasi, dan sosial media marketing.

### 📉 Korelasi Pengangguran, Wiraswasta, dan Kemiskinan
- Tidak ada hubungan signifikan antara tingkat kemiskinan dengan jumlah pengangguran maupun wiraswasta berdasarkan uji Kendall’s Tau:
    - Kemiskinan vs Pengangguran → `τ = -0.111 ; p = 0.761`
    - Kemiskinan vs Wiraswasta → `τ = -0.389 ; p = 0.180`
- Meskipun korelasi negatif muncul antara kemiskinan dan wiraswasta, tidak cukup signifikan secara statistik.

### 📊 Sebaran dan Tingkat Kemiskinan
- Kabupaten Bogor dan Garut: jumlah penduduk miskin terbanyak.
- Namun jika dilihat dari rasio, Kota Tasikmalaya (1,069%) dan Kabupaten Kuningan (1,052%) merupakan daerah dengan tingkat kemiskinan tertinggi.

### 🦠 Kesehatan Masyarakat – Penyakit dan Kematian (2019)
- Penyakit dengan jumlah kasus tertinggi: diare dan pneumonia, terkait sanitasi dan akses air bersih.
- Tantangan utama kesehatan: kualitas fasilitas kesehatan, terutama di daerah padat penduduk dan infrastruktur rendah.

### ⚰️ Distribusi Jenis dan Penyebab Kematian
- Tahun 2019, kematian lahir mati mendominasi (62,92%), diikuti kematian ibu (18,72%).
- Penyebab utama kematian: BBLR (berat badan lahir rendah) dan asfiksia.
- Permasalahan terkait kesehatan maternal dan neonatal menonjol.

### 📌 Hasil Analisis Korelasi Statistik
- Penduduk vs Kematian → korelasi positif signifikan `τ = 0,51 ; p = 0,0002`
   - Daerah berpenduduk padat cenderung memiliki jumlah kematian lebih tinggi.
- Penduduk vs Fasilitas Kesehatan → korelasi sangat kuat `τ = 0,82 ; p ≈ 0`
   - Infrastruktur kesehatan mengikuti jumlah penduduk.
- Fasilitas Kesehatan vs Kematian → korelasi negatif lemah & tidak signifikan `τ = -0,14 ; p = 0,297`
  - Banyaknya fasilitas belum tentu berdampak langsung pada penurunan kematian, kemungkinan karena kualitas, distribusi, dan tenaga kesehatan.

### ✅ Kesimpulan Umum Insight
- Pertumbuhan penduduk tinggi belum sepenuhnya diimbangi oleh kualitas hidup dan layanan publik.
- Ketimpangan wilayah dan kelompok pekerjaan terlihat jelas dalam distribusi penduduk dan tingkat kemiskinan.
- Infrastruktur kesehatan berkembang mengikuti populasi, namun kualitas layanan masih menjadi tantangan besar.
- Upaya penguatan layanan kesehatan ibu-anak dan sanitasi perlu diprioritaskan.

---

### <p align="center"> Kependudukan Jawa Barat </p>

Jawa Barat merupakan salah satu provinsi dengan jumlah penduduk terbanyak di Indonesia. Sejak tahun 2013, laju pertumbuhan penduduk di provinsi ini menunjukkan tren positif dengan rata-rata pertumbuhan sekitar 2% per tahun. [Unduh disini!](https://github.com/adindadwi68/Kondisi-kependudukan-Jawa-Barat/blob/main/Visualisasi/Jumlah%20Penduduk%20Pertahun.html) 
<p align="center"> <img width="1002" height="490" alt="newplot (3)" src="https://github.com/user-attachments/assets/125a8bd7-574f-4d79-aa55-52703e04cec3" /></p>
Puncak laju pertumbuhan terjadi pada tahun 2020 dengan angka mencapai 2,97%, yang kemungkinan besar dipengaruhi oleh kondisi khusus saat pandemi COVID-19. Selain pertumbuhan penduduk, struktur demografi juga mencerminkan ketimpangan ringan; pada tahun 2024, rasio jenis kelamin di Jawa Barat tercatat sebanyak 102 laki-laki untuk setiap 100 perempuan. [Unduh disini!](https://github.com/adindadwi68/Kondisi-kependudukan-Jawa-Barat/blob/main/Visualisasi/Pertumbuhan%20penduduk%20di%20jawa%20barat.html)    
<p align="center"><img width="1194" height="568" alt="newplot (5)" src="https://github.com/user-attachments/assets/e7ffda76-0fd8-47b7-969e-fed6963b4f0c" /> </p>

Jika dilihat berdasarkan sebaran wilayah, Kabupaten Bogor menempati posisi pertama sebagai daerah dengan jumlah penduduk terbanyak, yaitu sekitar 5,8 juta jiwa. Sedangkan Kota Banjar menjadi daerah dengan populasi penduduk paling sedikit, hanya sekitar 200 ribu jiwa. Perbedaan ini menunjukkan adanya konsentrasi populasi yang tidak merata antar kabupaten/kota di Jawa Barat.[Unduh disini!](https://github.com/adindadwi68/Kondisi-kependudukan-Jawa-Barat/blob/main/Visualisasi/sebaran%20penduduk%20perkabupaten.png)
<p align="center">
  <img width="5968" height="4014" alt="sebaran penduduk perkabupaten" src="https://github.com/user-attachments/assets/979c55dc-4d5d-45cb-b924-1c832691bb72" />
</p>

Lebih dari 40 juta penduduk tercatat tinggal di Jawa Barat. Sebagian besar di antaranya bekerja sebagai ibu rumah tangga, wiraswasta, pelajar, atau belum bekerja. Sejak tahun 2020, jumlah penduduk yang tidak atau belum bekerja terus meningkat. Kemungkinan besar, hal ini dipengaruhi oleh dampak pandemi COVID-19 terhadap kondisi ekonomi dan lapangan pekerjaan. [Unduh disini!](https://github.com/adindadwi68/Kondisi-kependudukan-Jawa-Barat/blob/main/Visualisasi/Sebaran%20Kelompok%20Pekerjaan.png)
<p align="center"><img width="1194" height="568" alt="newplot (1)" src="https://github.com/user-attachments/assets/73ae1da5-2e2c-4063-9516-ad79cc9bfd39" /></p>

Di tengah meningkatnya tingkat pengangguran, jumlah penduduk yang berwiraswasta juga mengalami kenaikan. Ini menunjukkan pergeseran masyarakat ke sektor informal atau usaha mandiri sebagai strategi bertahan selama pandemi. Peningkatan signifikan terjadi pada 2021, seiring maraknya e-commerce, program afiliasi, dan pemanfaatan media sosial sebagai sarana pemasaran. Hal ini mengindikasikan bahwa masyarakat Jawa Barat mulai memanfaatkan teknologi untuk berwirausaha. [Unduh disini!](https://github.com/adindadwi68/Kondisi-kependudukan-Jawa-Barat/blob/main/Visualisasi/Penduduk%20berwiraswasta.html)
<p align="center"><img width="1373" height="662" alt="newplot (4)" src="https://github.com/user-attachments/assets/ecd53f5c-00fa-4680-89f5-b166ccc532b6" /></p>

Peningkatan jumlah penduduk tidak/bekerja berbanding terbalik dengan jumlah penduduk miskin yang tercatat. Hal ini membuktikan bahwa angka penganguran di Jawa Barat tidak mempengaruhi jumlah penduduk miskin. Meningkatnya jumlah wiraswasta juga dapat menyumbang peran dalam tren negatif yang ditunjukan pada jumlah penduduk miskin di Jawa Barat. [Unduh disini!](https://github.com/adindadwi68/Kondisi-kependudukan-Jawa-Barat/blob/main/Visualisasi/Jumlah%20penduduk%20miskin.html)
<p align="center"><img width="1359" height="648" alt="newplot (2)" src="https://github.com/user-attachments/assets/802f5ecd-a7d8-4a3b-86fd-892db8382b73" /></p>

Hal tersebut perlu dibuktikan dengan analisis korelasi menggunakan Metode Kendall's Tau. Didapatkan hasil sebagai berikut :
<div align="center">
  
|             Analisis Korelasi            | Nilai Kendall's Tau | P-value |
|------------------------------------------|---------------------|---------|
|Tingkat kemiskinan terhadap jumlah pengangguran|  -0.111 |0.761|
|Tingkat kemiskinan terhadap jumlah wiraswasta|-0.389|0.180|
 
  </div>
  
  Hasil analisis menunjukkan bahwa tidak terdapat hubungan yang signifikan antara tingkat kemiskinan dengan jumlah pengangguran maupun jumlah wiraswasta. Meskipun terdapat kecenderungan hubungan negatif antara tingkat kemiskinan dan jumlah wiraswasta, korelasi tersebut belum cukup kuat dan tidak signifikan secara statistik (p > 0.05). 
  
  Bedasarkan hasil pengolahan data, Kabupaten Bogor dan Garut merupakan daerah dengan jumlah penduduk miskin terbanyak. Namun, tingkat kemiskinan tertinggi lebih akurat jika dilihat dari persentase atau rasio antara jumlah penduduk dengan jumlah penduduk miskin di setiap daerah. Dihasilkan bahwa, Kota Tasikmalaya dan Kabupaten Kuningan merupakan daerah dengan tingkat kemiskinan tertinggi dengan persentase masing0masing 1,069% dan 1,052%.
#
Selain kelompok pekerjaan dan jumlah penduduk miskin, kesejahteraan suatu daerah juga dapat ditinjau dari jumlah kasus penyakit dan tingkat kematian. Namun, karena keterbatasan dataset yang tersedia, analisis terhadap kasus penyakit dan kematian hanya dilakukan berdasarkan data tahun 2019.

Berdasarkan data tersebut, jenis penyakit dengan jumlah kasus tertinggi di Jawa Barat, serta di beberapa daerah lainnya, adalah diare dan pneumonia. Hal ini menunjukkan bahwa penyakit infeksi saluran pencernaan dan pernapasan masih menjadi masalah kesehatan utama di wilayah ini.
<p align="center"><img width="3440" height="2372" alt="Sebaran Jenis Penyakit" src="https://github.com/user-attachments/assets/31ab4c75-79e1-41be-8125-ef4d0352a3f8" /></p>

Kedua jenis penyakit tersebut umumnya berkaitan dengan sanitasi lingkungan, akses terhadap air bersih, dan kualitas fasilitas layanan kesehatan. Tingginya kasus ini dapat mengindikasikan bahwa masih terdapat tantangan dalam pemenuhan kebutuhan dasar kesehatan masyarakat, terutama di daerah dengan kepadatan penduduk tinggi atau keterbatasan infrastruktur kesehatan.

Oleh karena itu, selain menurunkan angka kemiskinan dan pengangguran, peningkatan kualitas layanan kesehatan dan infrastruktur sanitasi menjadi faktor penting dalam meningkatkan kesejahteraan masyarakat secara menyeluruh.
#
Sejak tahun 2017 hingga 2019, jumlah kasus kematian di Jawa Barat menunjukkan tren penurunan. Meskipun demikian, pada tahun 2019, jenis kematian terbanyak adalah kematian lahir mati, yang mencapai 62,92% dari total kasus kematian. Jenis kematian tertinggi kedua adalah kematian ibu, dengan proporsi sebesar 18,72%.
<p align="center"><img width="2248" height="1474" alt="Distribusi Jenis kematian" src="https://github.com/user-attachments/assets/45dcc425-98b6-42d2-b01a-c438c5de4ee6" /></p>

Dari sisi penyebab, kematian paling banyak disebabkan oleh berat badan lahir rendah (BBLR), disusul oleh asfiksia sebagai penyebab kedua terbanyak. Kedua penyebab ini erat kaitannya dengan kualitas kesehatan ibu dan bayi, termasuk status gizi, pemantauan selama kehamilan, dan penanganan saat persalinan. [Unduh disini!](https://github.com/adindadwi68/Kondisi-kependudukan-Jawa-Barat/blob/main/Visualisasi/Jenis%20dan%20Penyebab%20kematian.html)
<p align="center"><img width="1512" height="730" alt="newplot" src="https://github.com/user-attachments/assets/d2150624-a2a2-4e9b-8975-894f6ea35aab" /></p>
Meskipun angka kematian secara umum menunjukkan penurunan, kesehatan maternal dan neonatal masih menjadi tantangan besar di Jawa Barat. Kematian tertinggi didominasi oleh kematian lahir mati dan kematian ibu, yang umumnya disebabkan oleh BBLR dan asfiksia. Hal ini menunjukkan perlunya peningkatan akses terhadap layanan kesehatan ibu dan anak, perbaikan gizi ibu hamil, serta penguatan kapasitas fasilitas persalinan yang aman dan berkualitas sebagai prioritas kebijakan kesehatan.

Hasil analisis statistik menggunakan uji Kendall’s Tau menunjukkan adanya hubungan yang signifikan antara jumlah penduduk dan jumlah kasus kematian, dengan nilai korelasi sebesar 0,51 dan p-value 0,0002. Ini menunjukkan bahwa daerah dengan jumlah penduduk yang lebih besar cenderung memiliki kasus kematian yang lebih tinggi pula. Temuan ini masuk akal karena populasi besar secara alami berpotensi menimbulkan lebih banyak kasus kematian, terutama jika tidak diimbangi dengan ketersediaan layanan kesehatan dan infrastruktur yang memadai. Oleh karena itu, penguatan sistem kesehatan di wilayah berpenduduk padat menjadi sangat penting untuk mencegah peningkatan risiko kematian.

Sementara itu, korelasi antara jumlah penduduk dan jumlah fasilitas kesehatan menunjukkan hubungan yang sangat kuat dan signifikan, dengan nilai korelasi sebesar 0,82 dan p-value 1,1 × 10⁻¹². Artinya, semakin besar jumlah penduduk, semakin banyak pula fasilitas kesehatan yang tersedia. Ini menunjukkan adanya penyesuaian infrastruktur kesehatan terhadap kebutuhan populasi, yang merupakan langkah positif dalam menjaga akses layanan kesehatan. Namun demikian, peningkatan jumlah fasilitas belum tentu menjamin kualitas layanan. Hal ini terlihat dari hasil korelasi antara jumlah fasilitas kesehatan dan jumlah kematian yang justru menunjukkan hubungan negatif sangat lemah dan tidak signifikan (nilai korelasi -0,14; p-value 0,297). Artinya, keberadaan fasilitas yang banyak belum tentu berdampak langsung terhadap penurunan angka kematian, kemungkinan karena faktor kualitas layanan, distribusi fasilitas yang tidak merata, atau keterbatasan sumber daya manusia kesehatan.

Dengan demikian, meskipun kuantitas fasilitas kesehatan telah mengikuti pertumbuhan penduduk, diperlukan evaluasi yang lebih dalam terhadap kualitas, distribusi, serta efektivitas layanan agar infrastruktur yang ada dapat benar-benar berdampak dalam menekan angka kematian dan meningkatkan kesejahteraan masyarakat.

---
## 📬 Kontak
- 📧 Email: [adindadl1234@gmail.com](mailto:adindaddwiilestari@gmail.com)
- 💬 Telegram: [@rynt68](https://t.me/rynt68)
- 💼 LinkedIn: [Adinda Dwi Lestari](https://linkedin.com/in/adindadwi06)
