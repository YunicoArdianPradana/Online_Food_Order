# Online Food Order Prediction

Proyek ini bertujuan untuk memprediksi apakah seorang pelanggan akan memesan makanan online lagi berdasarkan data historis dan karakteristik pelanggan.

![Deskripsi gambar](https://github.com/YunicoArdianPradana/Online_Food_Order/blob/8db3c0913f4f8dc90c93565c87e850d517865f69/ss_hasil_prediksi.png)

## Fitur

- Analisis data pelanggan yang memesan makanan online
- Visualisasi data menggunakan Matplotlib, Seaborn, dan Plotly
- Pra-pemrosesan data: konversi fitur kategorikal ke numerik
- Pelatihan model machine learning (Random Forest)
- Prediksi interaktif menggunakan ipywidgets

## Struktur Project

- `onlinefoods.csv` — Dataset utama pelanggan
- `customer_model.pkl` — Model machine learning hasil pelatihan
- `test.ipynb` — Notebook utama berisi analisis, pelatihan, dan prediksi

## Cara Menjalankan

1. Clone repository ini.
2. Pastikan sudah menginstall dependensi berikut:
    - numpy
    - pandas
    - matplotlib
    - seaborn
    - plotly
    - scikit-learn
    - joblib
    - ipywidgets
3. Buka dan jalankan seluruh sel di [`test.ipynb`](test.ipynb) menggunakan Jupyter Notebook.

## Alur Analisis

1. **Import dan eksplorasi data**  
   Data pelanggan diimpor dan dianalisis secara visual.
2. **Pra-pemrosesan**  
   Fitur kategorikal diubah menjadi numerik agar bisa digunakan untuk pelatihan model.
3. **Pelatihan Model**  
   Model Random Forest dilatih untuk memprediksi kemungkinan pelanggan memesan lagi.
4. **Prediksi Interaktif**  
   Formulir input menggunakan ipywidgets untuk melakukan prediksi secara langsung.

## Lisensi

Proyek ini menggunakan lisensi Yunico Ardian Pradana.
ada pertanyaan ? bisa hubungi saya di Email yunicoardian123@gmail.com
