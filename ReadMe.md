##### *Disclaimer*:
1. *This analysis was created to be submitted as a personal portfolio in the Data Science field.*
2. *This program is written in the Python programming language and is created in Indonesian Language. The available ReadMe file is also written in Indonesian*
3. *The Data used is from Kaggle.com with the link: https://www.kaggle.com/datasets/kiva/data-science-for-good-kiva-crowdfunding*


# Analisis Data Crowdfunding Kiva: Memahami Dampak Sosial Melalui Data

## Deskripsi Proyek

Proyek ini bertujuan untuk melakukan analisis eksploratif (EDA) terhadap dataset Kiva yang tersedia di Kaggle ([https://www.kaggle.com/datasets/kiva/data-science-for-good-kiva-crowdfunding/data](https://www.kaggle.com/datasets/kiva/data-science-for-good-kiva-crowdfunding/data)). Kiva adalah organisasi non-profit yang memungkinkan orang untuk memberikan pinjaman kepada pengusaha dan siswa di seluruh dunia. Dataset ini menyediakan informasi rinci tentang pinjaman Kiva, peminjam, dan mitra Kiva.

Tujuan utama dari analisis ini adalah untuk memberikan Informasi sebagai sebuah rekomendasi sektor-sektor mana yang cocok untuk diberikan pendanaan.


## Dataset

Dataset yang digunakan dalam proyek ini berasal dari Kaggle:

*   **Sumber:** [https://www.kaggle.com/datasets/kiva/data-science-for-good-kiva-crowdfunding/data](https://www.kaggle.com/datasets/kiva/data-science-for-good-kiva-crowdfunding/data)

## Deskripsi kolom:
Berikut adalah deskripsi dari masing-masing kolom:
- `id`: Unique ID untuk masing-masing loan (loan ID)
- `funded_amount`: Jumlah yang dicairkan oleh Kiva ke agen (USD)
-  `loan_amount`: Jumlah yang disalurkan oleh agen ke peminjam (USD)
    ​Keterangan tambahan:
    - loan_amount adalah jumlah dana yang dibutuhkan oleh borrower (peminjam).
    - funded_amount biasanya sama atau lebih kecil dari loan_amount:
    - Sama: Jika seluruh jumlah yang dibutuhkan berhasil terkumpul.
    - Lebih kecil: Jika belum seluruhnya terkumpul, tetapi Kiva memutuskan tetap mendistribusikan sebagian yang sudah terkumpul.
 
- `activity`: Kategori lebih spesifik dari `sector`
- `sector`: Kategori dari loan
- `country`: Nama negara lengkap, tempat pinjaman dicairkan
- `region`: Nama wilayah lengkap dari `country`
- `currency`: Mata uang
- `partner_id`: ID untuk organisasi partner
- `posted_time`: Waktu pinjaman di-posting di Kiva oleh agen
- `funded_time`: Waktu pinjaman telah sepenuhnya dibiayai oleh pemberi pinjaman
- `term_in_months`: Durasi pencairan pinjaman (dalam satuan bulan)
- `lender_count`: Banyaknya peminjam yang berkontribusi
- `repayment_interval`: Cara pelunasan peminjaman


## Library
Proyek ini menggunakan library Python berikut:

*   pandas
*   numpy
*   matplotlib
*   seaborn

# Detail Analisa Lanjutan
Detail analisis lanjutan yang dilakukan menggunakan visualisasi data dengan Tableu. Hasilnya bisa di lihat pada tautan berikut: https://public.tableau.com/app/profile/satrio.prabowo/viz/KivaAnalysis_17419397210690/MainDashboard?publish=yes