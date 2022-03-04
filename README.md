# EnigmaTeam_JC_DS_VL_03_FinalProject

CONSULTANT ANALYST: BANK X
Created By: Irwanti & Josceline (Enigma Team)
Business Problem Understanding
Context

Sebuah perusahaan di bidang keuangan khususnya dunia perbankan, memiliki salah satu produk utama yaitu penyediaan kartu kredit. Bank tersebut ingin melakukan segmentasi nasabah dengan melihat perilaku atau profil pengguna kartu kredit selama 6(enam) bulan terakhir, dengan tujuan agar bisa melakukan kampanye pemasaran atau promosi penjualan yang efektif kepada pelanggan yang dituju.

Segmentasi adalah analisis tentang bagaimana produk harus dijual atau dikembangkan, berdasarkan analisis segmen pelanggan saat ini yang untuk jangka panjangnya bisa membantu mengidentifikasi segmen baru sebagai target untuk produk yang ada atau pengembangan produk baru. Segmentasi sangatlah penting karena perusahaan memiliki sumber daya yang terbatas, dan harus fokus pada cara terbaik mengidentifikasi dan melayani pelanggannya. Segmentasi yang efektif memungkinkan perusahaan untuk menentukan kelompok pelanggan mana yang harus mereka layani dan bagaimana memposisikan produk dan layanan mereka dengan baik untuk setiap kelompok.

Segmentasi nasabah dapat dilakukan dengan mengelompokkan pengguna kartu kredit berdasarkan perilaku masing-masing agar akhirnya perusahaan bisa lebih mudah untuk membuat strategi bisnis yang efektif.

Problem Statement

Pemasaran memegang peranan yang sangat penting bagi dunia perbankan sehingga Bank mengalokasi rata-rata 5-7% dari total biaya tahunan untuk biaya pemasaran. Dengan melakukan pengelompokkan customer secara tidak akurat, sebagian besar dari biaya tersebut akan menjadi sia-sia. Selain dari biaya, proses segmentasi nasabah juga memakan waktu yang cukup lama jika dilakukan secara manual karena banyaknya data yang harus diinput satu per satu.

Goals

Bank biasanya melalukan segmentasi dengan bantuan informasi demografik customer yang terkadang tidak akurat untuk diaplikasikan pada pemasaran. Dengan melalukan analisis menggunakan data perilaku pengguna kartu kredit, Bank dapat mengelompokkan customer dengan lebih akurat yang bisa membantu dalam pengalokasian biaya pemasaran secara optimal agar lebih terarah dan efektif pada setiap customer kartu kredit. Selain itu, manfaat lain yang bisa didapatkan adalah penghematan waktu yang akan didapatkan dengan melakukan automasi market segmentasi.

Analytic Approach

Yang akan kita lakukan adalah menganalisis data menggunakan unsupervised learning untuk menemukan pola perilaku yang serupa ditiap pengguna kartu kredit kemudian kita akan mengidentifikasi model yang terbaik untuk mengelompokkan customer-customer berdasarkan perilaku pengguna kartu kredit selama 6(enam) bulan terakhir.

Data Understanding

Dataset source: https://www.kaggle.com/arjunbhasin2013/ccdata

Notes :

Seluruh dataset bersifat kategori numerik kecuali kolom cust_id bersifat kategori categorical
Setiap baris data merepresentasikan informasi seorang pengguna kartu kredit selama 6(enam) bulan
