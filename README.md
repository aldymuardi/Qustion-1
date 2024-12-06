
# Submission Dicoding "Belajar Analisis Data dengan Python"

## Deskripsi

Proyek ini bertujuan untuk menganalisis data pada Bike Sharing Dataset. Tujuan akhirnya adalah untuk menghasilkan wawasan dan informasi yang berguna dari data yang dianalisis.

## Setup Environment
```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```
## Pertanyaan

1. pada jam berapa yang paling banyak dan paling sedikit disewa?

![image](https://github.com/user-attachments/assets/3d4984b1-320f-4412-8c5f-155d20c3c5f3)

Berdasarkan gambar di atas, Anda dapat melihat bahwa penyewaan sepda paling banyak digunakan pada jam 17:00 sekitar 336860 penyewaan. Kontras dengan hal tersebut, penyewaan pada jam 04:00 merupakan produk yang paling sedikit terjual sekitar 4428 penyewaan.

2. pada musim apa penyewaan sepeda paling banyak?

![image](https://github.com/user-attachments/assets/58cdf6bf-ae9b-4438-bf79-99f1c9ce43d3)

Musim yang paling banyak disewa ialah pada musim Fall (musim gugur) dengan total penyewaan pada musim gugur sebanyak 1061129 penyewaan

3. Bagaimana performa penjualan perusahaan dalam beberapa tahun terakhir?

![image](https://github.com/user-attachments/assets/8c5e48ec-34af-455e-82cb-badbda627b4d)

Berdasarkan visualisasi di atas, kita dapat melihat bahwa jumlah order terbanyak terjadi pada bulan September. Selain itu, kita juga dapat melihat adanya penurunan jumlah order yang cukup signifikan pada bulan November dan December.

4. Perbandingan Customer Registered dengan casual

![image](https://github.com/user-attachments/assets/d376a993-4408-43de-a98c-267f2865dc38)

seseorang yang sudah registered sebanyak 81.2% sedangkan sesorang yang belum melakukan regsitered (casual) sebanyak 18.8%

## Conclusion

- Conclution pertanyaan 1: Berdasarkan gambar di atas, Anda dapat melihat bahwa penyewaan sepda paling banyak digunakan pada jam 17:00. Kontras dengan hal tersebut, penyewaan pada jam 04:00 merupakan produk yang paling sedikit terjual.  
- conclution pertanyaan 2: pada musim Fall (musim gugur).
- conclution pertanyaan 3: Berdasarkan visualisasi di atas, kita dapat melihat bahwa jumlah order terbanyak terjadi pada bulan September 2012. Selain itu, kita juga dapat melihat adanya penurunan jumlah order yang cukup signifikan pada bulan januari 2011.
- conclution pertanyaan 4: Seseorang yang sudah registered sebanyak 81.2% sedangkan sesorang yang belum melakukan regsitered (casual) sebanyak 18.8%

## Run steamlit app
```
streamlit run dashboard.py
```
