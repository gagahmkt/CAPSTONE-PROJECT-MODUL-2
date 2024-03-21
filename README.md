# BACKGROUND
AWS adalah sebuah layanan komputasi cloud milik Amazon yang memiliki komposisi maupun perpaduan antara infrastruktur IAAS, PAAS serta SAAS. Layanan ini menawarkan layanan cloud atau database penyimpanan yang berskala besar, fleksibel serta menghemat biaya pengeluaran.

Software as a Service/SaaS adalah model software berbasis cloud yang mengirimkan aplikasi ke end user melalui internet. Vendor SaaS meng-host layanan dan aplikasi bagi pelanggan untuk mengakses sesuai permintaan. Penyedia SaaS mengelola perangkat keras, perangkat lunak, dan aplikasi di pusat data atau lingkungan cloud-nya sendiri. Pada Model SaaS berbasis langganan, pengguna dapat menaikkan atau menurunkan skala penggunaan software sesuai kebutuhan bisnis. Aspek tipikal lain dari model SaaS adalah penetapan harga yang dibayar untuk berlangganan atau model bayar sesuai kebutuhan, alih-alih membeli semua fungsionalitas sekaligus dalam satu potongan besar.

Pada model SaaS, perangkat lunak disediakan secara online sebagai layanan yang dapat diakses oleh pengguna melalui internet, biasanya melalui browser web. Contoh umum aplikasi SaaS adalah Customer Relationship Management (CRM), Enterprise Resource Planning (ERP), Amazon Chime, Amazon WorkDocs. Termasuk juga email berbasis web, dimana user dapat mengirim dan menerima email tanpa harus mengelola penambahan fitur pada produk email, atau memelihara server dan sistem operasi tempat program email dijalankan.

Sebuah perusahaan penyedia layanan SaaS sedang melakukan riset terhadap penjualan produk. Perusahaan melakukan analisa yang ditinjau dari Sales Performance, segmentasi pasar, dan perilaku konsumen. Hasil dari analisa tersebut digunakan oleh Perusahaan terutama Tim Marketing. Hasil analisa digunakan untuk mencari solusi terhadap permasalahan yang dihadapi, sehingga Tim Marketing dapat membuat strategi pemasaran yang efektif dan efisien untuk meningkatkan pemasaran produk dan mencapai profitabilitas yang tinggi.

# PROBLEMS
Permasalahan yang dihadapi perusahaan SaaS antara lain:
1. Bagaimana Sales Performance secara keseluruhan?
2. Bagaimana pengaruh diskon terhadap Profit?
3. Segmen apa saja yang mendapatkan keuntungan/kerugian terbesar?
4. Bagaimana pengaruh pola perilaku customer terhadap perusahaan?

# GOALS
Berdasarkan permasalahan yang dihadapi oleh perusahaan, tujuan dari analisa ini antara lain:
1. Mengetahui Sales Performance dari waktu ke waktu dan melihat tren yang terjadi.
2. Mengetahui pengaruh diskon terhadap profit dan membuat strategi pemasaran yang baik untuk mengurangi kerugian yang dialami Perusahaan.
3. Mengetahui segmentasi pasar dan membuat perencanaan yang baik 
4. Mengetahui pola perilaku customer dan menemukan treatment terbaik bagi customer.

# DATA UNDERSTANDING

Dataset ini berisi transaksi dari Perusahaan SaaS fiktif yang menjual software sales and marketing kepada Perusahaan lain (B2B). Pada dataset, tiap baris merepresentasikan produk dalam sebuah transaksi, dimana tiap kolom berisi:

|Nama Kolom       | Keterangan                                                |
|-----------------|-----------------------------------------------------------|
|`Row ID `        | Pengidentifikasi untuk setiap transaksi.                  |
|`Order ID`       | Pegidentifikasi untuk setiap order.                       |
|`Order Date`     | Tanggal saat order dilakukan.                             |
|`Date Key`       | Angka yang merepresentasikan tanggal order (YYYYMMDD).    |
|`Contact Name`   | Nama orang yang melakukan order.                          |
|`Country`        | Negara dimana order dilakukan.                            |
|`City`           | Kota dimana order dilakukan.                              |
|`Region`         | Region dimana order dilakukan.                            |
|`Subregion`      | Subregion dimana order dilakukan.                         |
|`Customer`       | Nama perusahaan yang melakukan order.                     |
|`Customer ID`    | Pengidentifikasi untuk setiap customer.                   |
|`Industry`       | Jenis industri customer.                                  |
|`Segment`        | Segmen customer (SMB, Strategic, Enterprise, etc.).       |
|`Product`        | Jenis produk yang dipesan.                                |
|`License`        | License key untuk produk.                                 |
|`Sales`          | Jumlah total penjualan pada transaksi.                    |
|`Quantity`       | Jumlah total item pada transaksi.                         |
|`Discount`       | Diskon yang berlaku pada transaksi.                       |
|`Profit`         | Profit dari transaksi.                                    |

# CONCLUSION
1. Terjadi kenaikan penjualan tahun namun tidak diiringi dengan peningkatan gross profit margin. Hal ini menunjukkan bahwa perusahaan mampu meningkatkan Sales dan Profit tiap tahunnya namun belum mampu melakukan efisiensi biaya.
2. Pemberian diskon yang berlebihan menyebabkan kerugian dari segi perusahaan. Jika terus berlanjut tanpa adanya regulasi terkait diskon, maka akan beresiko terhadap kelangsungan perusahaan, dimana pendapatan bersih akan menurun dan mempengaruhi keuntungan bersih. Selain itu dengan diskon yang tidak terkendali akan menurunkan citra merek karena customer akan menganggap produk memiliki nilai intrinsik yang lebih rendah dari nilai jualnya.
3. Segmen dengan kontribusi terbesar dari segmen SMB. Hal ini terjadi karena volume pelanggan dalam segmen ini biasanya jauh lebih tinggi daripada di Enterprise atau segmen Strategic. Selain itu dan kemudahan akses SaaS menjadikan solusi yang mudah digunakan dan diimplementasikan tanpa perlu sumber daya IT yang besar, beda dengan Enterprise atau Strategic yang lebih kompleks. Dengan kemudahan tersebut menjadikan biaya SaaS pada segmen SMB lebih rendah.
4. Industri dengan kontribusi terbesar berasal dari Finance, Energy, dan Manufacturing. Kebutuhan yang lebih besar terkait dengan penggunaan SaaS untuk mengelola data, analisis, manajemen risiko, dan efisiensi operasional menjadi faktor kuat yang menjadikan pentingnya penggunaan SaaS bagi industri. Industri finance memiliki regulasi yang ketat terkait dengan keamanan data, privasi, dan kepatuhan, sehingga mendorong penggunaan SaaS.
5. Region dengan kotribusi terbesar berasal dari EMEA (Europe, Middle Eastern, Africa). Pertumbuhan ekonomi, regulasi, kesiapan teknologi,dan jumlah perusahaan besar yang beroperasi di region tersebut berpengaruh terhadap penggunaan SaaS untuk mendukung bisnis.
6. Banyaknya customer dalam kategori Potential Loyalists, Promising, New Customers menunjukkan adanya peluang yang besar untuk pertumbuhan dan retensi pelanggan. Hal ini merupakan situasi yang positif bagi perusahaan, tetapi juga memerlukan tindakan yang tepat untuk memanfaatkan potensi ini. Perusahaan dapat membuat penawaran sesuai dengan segmen customer. Perusahaan juga harus meningkatkan layanan dan melibatkan customer. Membantu New Customer untuk memahami nilai produk akan mengurangi resiko churn di awal. Mengembangkan produk sesuai dengan feedback customer dan tren pasar sangat diperlukan, memiliki produk yang inovatif dan relevan akan membantu mempertahankan customer yang sudah ada dan menarik customer baru.

# RECOMMENDATIONS
1. Perlu dilakukan evaluasi untuk penjualan yang tinggi namun profit menurun atau tetap rendah, yaitu dengan peninjauan mendalam terkait biaya, strategi penetapan harga, evaluasi produk atau layanan, analisis pesaing, dan juga upaya untuk meningkatkan efisiensi operasional dan memperbaiki Profit Margin. Perlunya evaluasi pada produk Marketing Suite yang Profitnya lebih kecil daripada Marketing Suite - Gold, bisa dengan menggabung 2 layanan tersebut menjadi satu atau migrasi pengguna Marketing Suite ke Marketing Suite - Gold kemudian menghapus produk yang tidak profit.

2. Mengatur ulang strategi penetapan Discount bagi Customer sehingga menguntungkan bagi kedua belah pihak, dimana Perusahaan tidak mengalami kerugian namun tidak memberatkan Customer dengan penyesuaian Discount yang didapatkan. Pemberian diskon yang harus diperhatikan karena diskon lebih dari 30%, antara lain: ContactMatcher, Marketing Suite, Big Ol Database, Site Analytics, SaaS Connector Pack, Oneview.

3. Memberikan edukasi bagi industri terkait penggunaan SaaS yang mempermudah bisnis perusahaan.

4. Membuat strategi untuk memperbaiki produk atau layanan di region dengan profit yang rendah, perhatikan kondisi perekonomian negara tersebut dan sesuaikan harga produk dengan kemampuan daya beli customer di negara tersebut. Lakukan promosi untuk memperkenalkan produk ke customer baru terutama pada segmen Small Medium Business (SMB) dimana konsumen segmen SMB lebih banyak dibanding Enterprise maupun Strategic.

5. Terkait perilaku Customer, hal-hal yang dapat dilakukan perusahan:

**Champions :**
- Memberikan akses eksklusif ke fitur premium, customer support 24/7, dan penawaran harga khusus.
- Memberikan insentif untuk mereferensikan produk ke perusahaan lain.
- Melibatkan customer dalam beta test untuk produk baru atau fitur tambahan, dan gunakan feedback untuk meningkatkan produk secara keseluruhan.

**Loyal :**
- Menawarkan diskon berkelanjutan bagi customer Loyal atau harga khusus sebagai bentuk penghargaan atas loyalitas customer.
- Memperkuat hubungan dengan pelanggan Loyal melalui webinar khusus atau konsultasi yang dibuat khusus untuk mereka.
- Melibatkan customer dalam beta test untuk produk baru atau fitur tambahan, dan gunakan feedback untuk meningkatkan produk secara keseluruhan.

**Potential Loyalists :**
- Mengembangkan campaign pemasaran yang ditargetkan khusus dengan berfokus pada manfaat dan value produk yang ditawarkan.
- Memberikan demo produk atau uji coba gratis kepada customer mencoba sebelum memutuskan untuk berlangganan.

**New Customers :**
- Menawarkan diskon atau welcome offer kepada customer baru agar memulai penggunaan produk dengan cepat.
- Memberikan penawaran khusus untuk pembelian berikutnya atau langganan jangka panjang.

**Promising :**
- Meningkatkan engagement produk untuk menarik customer melalui pelatihan, tutorial, atau webinar tentang key features.
- Memberikan penawaran upgrade atau diskon khusus bagi customer untuk meningkatkan transaksi.

**Need Attention :**
- Melakukan audit untuk mengidentifikasi masalah atau kebutuhan customer dan melakukan perbaikan.
- Menjaga komunikasi secara aktif dengan customer, menawarkan solusi yang relevan dan mengikuti untuk memastikan kebutuhan mereka terpenuhi.

**Hibernating Customers :**
- Memberikan insentif atau penawaran khusus untuk mendorong customer supaya kembali berlangganan.
- Meninjau riwayat transaksi dan mengembangkan strategi untuk memperbaiki pengalaman customer dengan produk.

**Lost Customers :**
- Melakukan kontak langsung dengan customer untuk memahami masalah dan menawarkan solusi yang memuaskan.
- Melakukan analisis menyeluruh untuk memahami alasan di balik perginya customer dan membuat rencana tindak lanjut untuk mencegah kehilangan customer di masa depan.
