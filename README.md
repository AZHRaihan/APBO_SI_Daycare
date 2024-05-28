# APBO_SI_Daycare

## Use Case Diagram
![use caseDay drawio](https://github.com/AZHRaihan/APBO_SI_Daycare/assets/145973780/7cf00916-ca55-4cf1-a7ee-bd6d77624cc2)

Penjelasan : 
•	Mendaftarkan anak : Orang tua mengisi formulir pendaftaran, staf memverifikasi data, anak terdaftar di sistem.

•	Membayar Biaya : Orang tua memilih metode pembayaran, staf menerima pembayaran, administrasi memproses pembayaran, sistem mencatat transaksi.

•	Mengantar Anak : Orang tua mengantar anak, staf menerima anak, mencatat waktu kedatangan.

•	Menjemput Anak : Orang tua menjemput anak, staf menyerahkan anak, mencatat waktu penjemputan.

•	Orang tua melihat laporan perkembangan anak melalui sistem atau aplikasi.

•	Mengelola Data : Administrator menambahkan, mengedit, dan menghapus data anak, orang tua/wali, staf, jadwal, kehadiran, dan laporan.

•	Membuat Laporan : Administrator generate laporan kehadiran, perkembangan anak, dan keuangan.

## Class Diagram
![ClassD DayCare drawio](https://github.com/AZHRaihan/APBO_SI_Daycare/assets/145973780/d35d244a-fc8c-462f-b3a9-c148f320d2a3)
## ERD (Entity Relationship Diagram)
![image (4)](https://github.com/AZHRaihan/APBO_SI_Daycare/assets/145973780/f618b231-acbd-4268-935b-0bf56b3e25a8)
•	Orang Tua > Anak (One to Many) : Seorang orang tua dapat memiliki banyak anak.

•	Anak > Kehadiran (One To many) : Seorang anak dapat menghadiri semua jadwal.

•	Staf > Jadwal (One To Many) : Seorang staf memiliki banyak jadwal.

•	Orang Tua > Pembayaran (One To One) : Seorang orang tua dapat melakukan sekali pembayaran

•	Pembayaran > Administrator(Many to One) : Banyak Pembayaran dapat diproses oleh satu administrator

•	Administrator > Laporan (One To Many) : Seorang administrator dapat mengolah banyak data.

•	Jadwal > Kehadiran : Sebuah Jadwal Memiliki banyak catatan Kehadiran
