# Capstone-Project-2
Pada Capstone Project 2 ini saya melakukan analisis pada dataset [tsa_claims](https://www.kaggle.com/datasets/terminal-security-agency/tsa-claims-database). TSA (Transportation Security Agent) merupakan sebuah badan pemerintah Amerika Serikat yang yang memiliki fokus utama dalam kemanan bandara. TSA bertanggung jawab untuk pemeriksaan penumpang dan bagasi di lebih dari 450 bandara Amerika Serikat. TSA mencatat klaim yang diajukan oleh para penumpang pesawat seperti kehilangan ataupun kerusakan barang. Data klaim yang diajukan kepada TSA tersebut dapat digunakan oleh TSA sebagai acuan untuk terus dapat meningkatkan kinerja keamanan di bandara. Dengan data klaim tersebut, TSA ingin melakukan evaluasi terkait keamanan bandara. TSA ingin mengetahui perkembangan jumlah klaim yang diterima dari tahun ke tahun, bandara mana saja yang memiliki jumlah klaim terbanyak serta jenis klaim apa yang paling banyak dilaporkan oleh penumpang. Informasi ini akan membantu TSA untuk mengetahui bandara mana saja yang membutuhkan peningkatan sistem keamanan sehingga dapat mengurangi jumlah klaim yang diajukan oleh penumpang pada TSA. 

Sebagai seorang *data analyst*, saya akan menyelesaikan masalah:

* Bagaimana perkembangan jumlah klaim penumpang pada rentang tahun 2002-2015?
* Bandara apa yang menerima jumlah klaim paling banyak?
* Jenis klaim apa yang paling banyak dilaporkan?
* Titik lokasi apa yang paling banyak menerima laporan klaim?

Untuk menyelesaikan masalah di atas, dibuat beberapa tujuan yaitu:
* Mengetahui perkembangan jumlah klaim penumpang pada rentang tahun 2002-2015
* Mengetahui bandara mana yang memiliki jumlah klaim paling banyak
* Mengetahui jenis klaim yang paling banyak dilaporkan
* Mengetahui titik lokasi yang paling banyak menerima laporan klaim

Untuk menyelesaikan permasalahan tersebut, sebelum melakukan analisis, saya melakukan tahapan *data understanding* dan *data cleaning* terlebih dahulu. Hal ini dilakukan agar data dapat dianalisis dengan baik serta tidak menimbulkan hasil yang bias. Analisis yang dilakukan adalah dengan menggunakan serangkaian analisis deskriptif. 

Setelah dilakukan analisis, berikut sejumlah *insight* yang telah diperoleh:
* Tahun 2002 merupakan tahun dengan jumlah klaim penumpang yang paling sedikit dan tahun 2004 merupakan tahun dengan jumlah klaim tertinggi. Kemudian setelah tahun 2004, jumlah klaim yang diajukan penumpang cenderung menurun.
 * Bandara yang paling banyak menerima klaim dari penumpang adalah Los Angeles International Airport (LAX), kemudian diikuti oleh John F. Kennedy International Airport (JFK). Bandara dengan jumlah klaim di atas rata-rata banyak yang termasuk ke dalam list bandara tersibuk di Amerika Serikat.
 * Jenis klaim yang paling banyak dilaporkan adalah **Passenger Property Loss** dan **Property Damage**. Kedua jenis klaim tersebut juga merupakan jenis klaim terbanyak di bandara-bandara yang memiliki jumlah klaim paling banyak.
 * Titik lokasi yang paling banyak menerima klaim adalah **Checked Baggage** dan **Checkpoint**. Kedua titik lokasi tersebut juga merupakan titik lokasi yang paling banyak menerima laporan klaim di bandara-bandara yang memiliki jumlah klaim paling banyak.
