# 🚲 Capital Bikeshare: Bikesharing Analysis and Dashboard

## 📝 Analysis with Google Colab
🚧 See the detail of this analysis and visualization on the [notebook](https://github.com/Farras-06/Submission-bike-sharing-analysis/blob/main/notebook.ipynb) 🚧

### Definisi Pertanyaan
1. Bagaimana perbandingan jumlah penyewa sepeda antara tipe pengguna casual dan pengguna registered?
2. Bagaimana trend penyewaan sepeda dalam 2 tahun terakhir?
3. Bagaimana pola penggunaan layanan penyewaan sepeda berdasarkan hari dalam satu minggu?

### Hasil dan Kesimpulan
1. Jumlah pengguna bike-sharing `registered`, berjumlah 2,6 juta, **jauh lebih tinggi** dibandingkan dengan pengguna `casual`, yang hanya berjumlah 600 ribu. Hal ini menunjukkan perbedaan yang besar.

2. Dalam 2 tahun terakhir (2011-2012), terjadi **pertumbuhan secara keseluruhan** dalam jumlah pengguna bike-sharing. Peningkatan ini terutama terlihat di pengguna jenis `registered`. Secara signifikan, pengguna jenis `registered` mengungguli pengguna jenis `casual` dalam hal kuantitas/jumlah, sehingga menunjukkan peningkatan untuk kedua jenis pengguna.

3. Pola pengguna bike-sharing berdasarkan hari dalam seminggu menunjukkan **jumlah yang konsisten di sekitar 400.000** pengguna setiap hari. Namun, jika dilihat lebih dekat berdasarkan jenis pengguna menunjukkan bahwa pengguna jenis `registered` cenderung **lebih tinggi pada hari kerja**, sedangkan pengguna jenis `casual` menunjukkan **penggunaan lebih tinggi pada akhir pekan**.


# 📊 Dashboard with Streamlit

## Streamlit Cloud
View the dashboard on streamlit could directly on this link: [GitHub Pages](https://pages.github.com/)

Dasboard menunjukkan jumlah total pengguna sepanjang tahun dan musim. Hal ini juga menunjukkan perbedaan penggunaan layanan bikesharing antara pengguna casual dan pengguna registered, berdasarkan hari dalam seminggu.

![/Image/gambar-dashboard.png](https://github.com/Farras-06/Submission-bike-sharing-analysis/blob/main/Image/gambar-dashboard.png)


## Run Streamlit on Local

### Install Dependencies
To install all the required libraries, open your terminal/command prompt/conda prompt, navigate to this project folder, and run the following command:

```
pip install -r requirements.txt
```

### Run Dashboard
```
cd dashboard
streamlit run dashboard.py
```

