# Analisis Numerik Gerai Donat

Repository ini berisi tugas **Analisis Numerik** mengenai hubungan antara jumlah penjualan dan revenue pada lima gerai donat dengan strategi pemasaran yang berbeda.

## Deskripsi

Analisis dilakukan menggunakan data laba/rugi harian dari lima gerai donat:

* **Gerai A** — Premium Gourmet
* **Gerai B** — Mass Market Volume
* **Gerai C** — Promo Agresif
* **Gerai D** — Mall Premium Flagship
* **Gerai E** — Cloud Kitchen

Tujuan analisis adalah melihat hubungan antara volume penjualan dengan revenue serta menentukan jumlah penjualan yang diperlukan untuk mencapai **Break Even Point (BEP)**.

## Metode Analisis

Tahapan yang dilakukan dalam notebook meliputi:

1. Membaca dan melihat struktur dataset.
2. Membuat **scatter plot jumlah penjualan vs revenue** untuk kelima gerai.
3. Menerapkan **regresi linear** untuk melihat tren revenue berdasarkan jumlah penjualan.
4. Menghitung nilai **R²** untuk melihat seberapa baik model regresi menggambarkan hubungan data.
5. Menentukan fungsi BEP berdasarkan hasil regresi.
6. Mencari jumlah penjualan pada titik BEP menggunakan **metode Bisection**.
7. Membandingkan hasil BEP dari masing-masing gerai.

## Dataset

Dataset yang digunakan adalah data harian kelima gerai donat dalam format CSV. Dataset dibaca langsung dari file CSV yang diunggah ke **Google Colab**, sehingga proses analisis tidak bergantung pada link eksternal.

## Tools & Library

Analisis dibuat menggunakan Python dengan beberapa library berikut:

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

