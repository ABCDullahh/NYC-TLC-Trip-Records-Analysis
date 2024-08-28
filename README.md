# CapstoneProject-Module-02

# NYC Taxi and Limousine Commission (TLC) Analysis

## Latar Belakang

New York City Taxi and Limousine Commission (TLC) adalah badan yang bertanggung jawab atas regulasi dan perizinan taksi medali (yellow taxi), street hail livery (green taxi), kendaraan sewaan (for-hire vehicles/FHVs), van komuter, dan kendaraan paratransit di New York City. Didirikan pada tahun 1971, TLC memiliki peran sentral dalam pengembangan dan peningkatan layanan taksi serta sewa di Kota New York.

TLC tidak hanya mengatur perizinan tetapi juga menetapkan tarif, standar layanan, persyaratan asuransi, keselamatan pengemudi, desain kendaraan, serta kriteria perizinan bagi kendaraan, pengemudi, dan operator/vendor yang beroperasi dalam layanan transportasi ini.

## Stakeholder

TLC, sebagai pengelola utama industri taksi di New York City, bertanggung jawab untuk memastikan efisiensi layanan dan kepuasan pengemudi. Dalam upaya memajukan sektor ini, TLC bertujuan untuk mengidentifikasi area dan waktu penjemputan yang paling ramai, baik pada hari kerja maupun akhir pekan. Informasi ini penting bagi TLC untuk mengoptimalkan distribusi armada taksi, sehingga pengemudi dapat memaksimalkan pendapatan mereka.

## Rumusan Masalah

### Analisis Berdasarkan Waktu Penjemputan:
1. **Kapan waktu (jam) penjemputan paling ramai?**  
   Membandingkan jam-jam puncak penjemputan antara weekend dan weekday.

2. **Bagaimana distribusi total pendapatan berdasarkan waktu?**  
   Mengkaji perbedaan distribusi pendapatan pada jam-jam tertentu di weekend dan weekday.

### Analisis Berdasarkan Wilayah Penjemputan:
1. **Wilayah mana yang paling sibuk?**  
   Menentukan zona dan borough dengan aktivitas penjemputan tertinggi pada weekend dan weekday.

2. **Kapan waktu (jam) penjemputan paling ramai di setiap borough?**  
   Mengidentifikasi jam puncak penjemputan di tiap borough pada weekend dan weekday.

## Kesimpulan Analisis

### Weekday vs. Weekend
- **Jam Puncak Penjemputan:**  
  Pada **weekday**, penjemputan tertinggi terjadi pada pagi hari (07:00 - 09:00) dan sore hari (17:00 - 19:00), terutama di **Manhattan** pada zona **East Harlem North** dan **East Harlem South**.

- **Distribusi Pendapatan:**  
  Meskipun volume penjemputan lebih tinggi pada weekday, **pendapatan per trip cenderung serupa** antara weekday dan weekend, dengan pendapatan tertinggi terjadi pada dini hari sekitar pukul 04:00.

### Wilayah Tersibuk
- **Manhattan** tetap menjadi pusat aktivitas penjemputan baik pada weekday maupun weekend, dengan zona seperti **Central Harlem** dan **Times Square** juga menunjukkan tingkat aktivitas tinggi.
  
- **Queens** dan **Brooklyn** memiliki penjemputan signifikan pada siang hari selama weekend, namun masih di bawah Manhattan.

- **Bronx** dan **Staten Island** menunjukkan **jarak perjalanan lebih panjang** namun dengan volume penjemputan yang rendah.

## Rekomendasi

1. **Penempatan Armada yang Tepat:**
   - **Weekday:** Fokuskan armada di **Manhattan** pada **jam sibuk pagi (07:00 - 09:00) dan sore (17:00 - 19:00)**. Hindari **oversupply** di area ini untuk menjaga **pendapatan per driver**.
   - **Weekend:** Tempatkan armada di **Queens** (**Forest Hills**, **Elmhurst**) dan **Brooklyn** (**Fort Greene**, **Downtown Brooklyn/MetroTech**) pada **siang hari (12:00 - 15:00)** untuk memanfaatkan permintaan yang stabil. Driver yang lebih suka persaingan rendah dapat fokus di zona ini.

2. **Penyesuaian Jam Operasional:**
   - Mulai operasional lebih awal, sekitar **pukul 04:00**, untuk **memaksimalkan pendapatan per trip** di zona seperti **Central Park** dan **East Harlem**.

3. **Optimalisasi Rute:**
   - **Bronx** dan **Staten Island**: Driver di zona ini bisa fokus pada **perjalanan jarak jauh** yang lebih bernilai, meskipun frekuensinya rendah, untuk menghindari persaingan di zona-zona padat.

4. **Kampanye di Zona dengan Aktivitas Rendah:**
   - **Staten Island** dan zona lainnya dengan aktivitas rendah dapat ditingkatkan melalui **kampanye promosi atau diskon** untuk menarik lebih banyak penumpang dan menghindari oversupply di zona utama.

Rekomendasi ini dirancang untuk memberikan **fleksibilitas** kepada driver dalam memilih strategi operasi yang sesuai dengan preferensi mereka, serta membantu **menghindari risiko oversupply** yang dapat mengurangi pendapatan.

## Visualisasi

Untuk visualisasi data yang lebih mendalam, Anda dapat mengakses dasbor interaktif Tableau melalui tombol di bawah ini:

[![Tableau Dashboard](https://img.shields.io/badge/Visualize_on-Tableau-blue)](https://public.tableau.com/views/capstone_17247814146250/Capstone2ProjectNYCTLCTripJAN2023?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


---
