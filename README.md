# Strategi Peningkatan Retensi dan Kepuasan Pelanggan Olist (Brazillian E-Commerce) Berbasis CSAT dan Segmentasi RFM










Alpha Team JCBDAAH-003 |
Ganjar Raharja, Khalisha Nadhira, Iffa Aulia


---
# **1. Business Understanding**
## **1.1 Background**
**Pelanggan** adalah **sumber kehidupan bagi setiap bisnis**. Tanpa pelanggan, perusahaan tidak akan memiliki pendapatan, bahkan tidak akan memiliki alasan untuk terus beroperasi. Memahami pelanggan dan memenuhi kebutuhan mereka menjadi kunci keberhasilan dan keberlanjutan bisnis dari waktu ke waktu. [Miley, 2023](https://www.dailycupoftech.com/why-customers-are-a-companys-biggest-asset/) Dalam dunia bisnis yang kompetitif, mempertahankan pelanggan sama pentingnya dengan menarik pelanggan baru, dan customer loyalty menjadi kunci stabilitas serta pertumbuhan jangka panjang.[Dentsu, 2024](https://www.dentsu.com/id/en/insights/our-blog/apa-itu-customer-loyalty)

Menurut analisis McKinsey, **e-commerce merupakan arena bisnis yang sangat kompetitif** dan inovatif karena menggabungkan teknologi baru serta perubahan perilaku konsumen. Di tengah persaingan yang ketat, perusahaan tidak hanya dituntut menarik pelanggan baru tetapi juga mempertahankan pelanggan yang sudah ada. Oleh karena itu, **loyalitas dan retensi pelanggan menjadi faktor penting untuk mendukung pertumbuhan dan keberlanjutan bisnis e-commerce**. [McKinsey, 2025](https://www.mckinsey.com/mgi/our-research/capturing-the-next-big-arenas-of-competition-in-ten-charts)

Menariknya, pasar e-commerce Brazil ternyata lebih besar dibanding Asia Tenggara. Pada tahun 2023, transaksi e-commerce di Asia Tenggara mencapai sekitar USD 114,6 miliar, sementara Brasil sendiri mencapai kurang lebih USD 216 miliar. Selisih yang cukup besar ini menunjukkan bahwa ekosistem digital di Brazil sudah cukup matang, didorong oleh akses internet yang luas, populasi muda yang tech-savvy, dan kebiasaan belanja online yang sangat tinggi. [Ppro](https://www.ppro.com/insights/e-commerce-opportunities-in-brazil-a-market-overview/)

Di Brazil sendiri terdapat lebih dari 40 marketplace seperti Mercado Livre, Americanas.com, Amazon, Shopee dan lainnya, yang dapat terhubung melalui platform Olist. Olist merupakan platform integrasi e-commerce di Brazil yang memudahkan penjual dari berbagai skala untuk memasarkan produknya ke banyak marketplace hanya melalui satu sistem. Platform ini membantu pengelolaan produk, pemrosesan pesanan, dan pengiriman melalui mitra logistik, sehingga penjual tidak perlu berurusan dengan setiap marketplace secara terpisah. Dengan menyediakan ekosistem yang terintegrasi, Olist mempercepat proses jual beli online sekaligus meningkatkan pengalaman pelanggan dalam bertransaksi. [Olist.com](https://olist.com/o-que-e-olist/)

## **1.2 Problem Statement**

Berdasarkan analisis data Olist yang telah tersedia, lebih dari 90% Customer cenderung hanya melakukan satu kali pembelian menandakan Customer Retention yang rendah.[ICPDI, 2022 ](https://www.scitepress.org/Papers/2022/118366/118366.pdf)  Hal tersebut mengindikasikan bahwa Olist sedang dalam titik kritis, karena Customer Retention menjadi salah satu faktor yang menandakan pertumbuhan bisnis yang stabil serta tingkat Return of Investment yang lebih tinggi. [Monnier, 2025](https://www.opensend.com/post/customer-retention-rate-ecommerce)

Masalah ini muncul karena belum adanya strategi yang terdiferensiasi untuk setiap segmen pelanggan berdasarkan perilaku mereka. Selain itu, respons yang kurang optimal terhadap feedback pelanggan membuat perusahaan sulit memahami hambatan yang dihadapi pengguna. Dengan mengelola customer feedback secara tepat, perusahaan dapat mengidentifikasi barrier atau kendala yang dialami pelanggan, sehingga strategi perbaikan dapat lebih tepat sasaran. Pendekatan ini tidak hanya berpotensi meningkatkan retensi, tetapi juga mendorong peningkatan kepuasan pelanggan secara keseluruhan. [Codilar](https://www.codilar.com/methods-to-enhance-customer-retention-in-ecommerce/)


Sehingga disumpulkan bahwa problem statement project ini adalah:
1. Rendahnya tingkat pembelian ulang
2. Masih terdapat score review/kepuasan yang rendah  
3. Belum ada segmentasi pelanggan dalam menentukan campaign strategi

## **1.3 Goals**
Beberapa hal yang dapat menjadi tolak ukur keberhasilan peningkatan Olist antara lain:

1. Meningkatkan retention rate
2. Menemukan hambatan dalam pengalaman pelanggan dan meningkatkan overall kepuasan pelanggan
3. Mengidentifikasi segmentasi pelanggan agar dapat digunakan menentukan strategi marketing yang tepat dan relevan.

## **1.4 Stakeholders**
### 1. Tim Growth dan Marketing
Menggunakan segmen RFM untuk:
* Menentukan segmen yang layak mendapatkan
promo, loyalty program, atau campaign winback.
  * Mengurangi pemborosan budget pada segmen yang nilai bisnisnya rendah atau berisiko rendah.
  * Melihat komposisi basis pelanggan: berapa banyak pelanggan aktif vs tidak aktif, high value vs low value.
  * Menentukan prioritas strategi retensi vs akuisisi.
  * Memantau KPI seperti repeat purchase rate dan kontribusi revenue per segmen.
* Output yang dipakai: daftar segmen pelanggan dan karakteristik tiap segmen, metrik agregat per segmen (jumlah pelanggan, revenue, contribution, repeat rate).

### 2. Tim Product dan Customer Experience
* Menggunakan CSAT untuk menganalisa score kepuasan pelanggan agar dapat mengidentifikasi hambatan dan memaksimalkan pengalaman pengguna
* Menggunakan segmentasi RFM untuk:
  * Memahami pola perilaku pelanggan high-value vs low-value di dalam produk (journey, friction point).
  * Mendesain fitur/flow yang berbeda untuk segmen tertentu (misal: rekomendasi produk untuk segmen loyal vs edukasi untuk segmen baru).
* Output yang dipakai: analisis sentimen pada customer satisfaction score dan karakteristik perilaku per segmen dan implikasinya ke keseluruhan customer experience.

## **1.5 Analytical Approach**

Dalam analisis ini, kami menerapkan **pendekatan customer-centric segmentation** dengan **mengombinasikan metrik *CSAT* sebagai indikator pengalaman pelanggan**, ***RFM* analysis untuk mengukur nilai dan perilaku transaksi pelanggan**, serta ***K-Means* clustering untuk mengidentifikasi kelompok pelanggan yang memiliki karakteristik serupa**. Integrasi ketiga pendekatan ini memungkinkan identifikasi segmen pelanggan secara lebih komprehensif dan menjadi dasar dalam merumuskan strategi yang lebih terarah dan relevan sesuai dengan karakteristik setiap segmen, sehingga diharapkan dapat meningkatkan retensi pelanggan serta pengalaman pengguna secara keseluruhan [Kotler & Keller, 2016 ](https://www.researchgate.net/publication/40349508_Marketing_Management) ; [Wedel & Kamakura, 2000](https://www.researchgate.net/publication/279384714_The_Historical_Development_of_the_Market_Segmentation_Concept).

# **2. Data Understanding**
Dataset yang digunakan dalam project ini merupakan Brazilian E-Commerce Public Dataset yang dirilis oleh Olist dan berisi sekitar 100.000 transaksi dari 2016–2018 yang berasal dari berbagai marketplace di Brazil. Data ini memungkinkan analisis end-to-end, mulai dari status pesanan, harga, metode pembayaran, performa pengiriman, lokasi pelanggan, atribut produk, hingga ulasan pelanggan. Dataset ini merupakan data komersial nyata yang telah dianonimkan, nama perusahaan dan mitra yang muncul pada review diganti menggunakan nama-nama rumah di Game of Thrones.

Berikut detail dataset dari [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
# **3. Data Preparation**
# **4. Data Analysis**
Outline
* Exploratory Data Analysis (Delivered Orders)
* Customer Retention
* Customer Satisfaction
* Customer Segmentation
# **5. Recommmendation**
### **Tim Growth & Marketing**


* Mempromote campaign garansi pengembalian produk apabila barang yang diterima tidak sesuai maksimal H+3 setelah sampai
* Promote & membuat skema reward garansi tepat waktu (penerimaan voucher otomatis kepada customer apabila sudah lewat dari ETA yang diberikan)
* Buat journey otomatis setelah delivered product +7 Hari atau +14 Hari (email, WA, push notification rekomendasi product sesuai kategori order pertama) jika tidak ada pembelian kedua, kirim “best seller” product dari kategori yang sama di hari ke-21
* Rekomendasi per user persona:


| Persona             | Tujuan Utama               | Strategi Growth & Marketing      | Action Point                                                    | Success Metrics (KPI)                                |
| ------------------- | -------------------------- | -------------------------------- | -------------------------------------------------------------- | ---------------------------------------------------- |
| **Loyal**    | Retain & maximize CLV      | Lifecycle & loyalty optimization | Loyalty tier, early access promo, personalized reminder        | Repeat Purchase Rate ↑, CLV ↑, Monthly Active Buyers |
| **Potential** | Convert to loyal customers | Nurturing & conversion           | Bundle bernilai tinggi, personalized offer, education campaign | Conversion to repeat buyer ↑, AOV ↑, CSAT ↑       |
| **Newcomer**    | Drive repeat with low CAC  | Promo efficiency                 | Flash sale terbatas, voucher expiry                            | Repeat rate (30–60 hari), Promo ROI, Cost per Repeat |
| **At-Risk** | Selective reactivation     | Win-back or drop                 | One-time reactivation voucher                                  | Reactivation Rate, Cost per Reactivated User         |

### **Tim Product & CX Tim**

* Membuat customer journey garansi pengembalian produk dengan syarat dan
ketentuan berlaku (seperti salah ukuran, barang tidak sesuai dengan etalase, barang defect, dsb)
* Membuat customer journey program garansi tepat waktu
* Voucher potongan/ free ongkir pembelian berikutnya untuk yang mengalami delay parah (misalnya untuk yang lebih dari 14 hari)
* Melakukan analisis lanjutan dengan tim Customer Service untuk memvalidasi review customer dengan ticket keluhan
* Identifikasi permasalahan utama di dalam proses pengiriman kenapa sampai telat parah kesalahannya di sektor mana dan perbaiki kesalahan tersebut (contoh keterlambatan seller dalam mengirimkan barang ke ekspedisi -> berikan pelatihan kepada seller agar dalam memproses barang pesanan customer bisa lebih cepat)
* Rekomendasi intervensi tiap user persona:


| Persona             | Masalah Utama             | Fokus Product & CX            | Action Point                                    | Success Metrics (KPI)                                 |
| ------------------- | ------------------------- | ----------------------------- | ---------------------------------------------- | ----------------------------------------------------- |
| **Loyal**    | Ekspektasi tinggi, kritis | Reliability & premium UX      | Faster checkout, priority support              | CSAT ≥ baseline, Complaint rate ↓, Order success rate |
| **Potential** | CSAT terendah             | Reduce friction & build trust | Transparansi harga & ongkir, UX simplification | CSAT ↑, Checkout completion rate ↑                    |
| **Newcomer**    | Sensitif promo     | Stable promo experience       | Validasi voucher jelas, promo error prevention       | Promo conversion rate ↑, CSAT during promo                 |
| **At-Risk** | Tidak ada alasan kembali  | Diagnose experience gap       | Exit survey ringan, friction analysis          | Feedback response rate, Identified root causes        |

# **6. Business Impact Simulation**


Sebagai bagian dari eksplorasi lanjutan, dilakukan simulasi untuk memperkirakan dampak dari beberapa intervensi strategis terhadap kepuasan pelanggan dan retensi bisnis. Tujuan dari simulasi ini adalah memberikan estimasi bagaimana performa bisnis dapat meningkat apabila hambatan atau kendala dalam pengalaman pelanggan dikurangi melalui inisiatif berikut:


* Delivery date dipatok sesuai dengan kategori lokasi & simulasi pemberian skor menjadi 4 apabila tidak telat
* Simulasi ketika garansi retur produk sukses dan kepuasan pelanggan dengan sentimen produk negatif menjadi lebih meningkat
* Simulasi adanya promo-promo tertentu untuk meningkatkan retensi pengguna


