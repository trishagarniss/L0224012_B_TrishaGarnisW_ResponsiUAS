# Simulasi Prediksi Harga Saham BBCA Menggunakan Geometric Brownian Motion (GBM)

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-Academic-green)

> **Responsi UAS Pemodelan dan Simulasi**
> <br> *Studi kasus prediksi pergerakan harga saham PT Bank Central Asia Tbk (BBCA) dan pengukuran risiko investasi menggunakan metode simulasi Monte Carlo.*

---

## Identitas Mahasiswa
**Nama** : Trisha Garnis W  
**NIM** : L0224012  
**Kelas** : B  
**Mata Kuliah** : Pemodelan dan Simulasi  

---

## Deskripsi Studi Kasus
Saham merupakan sistem dinamis yang memiliki volatilitas tinggi. Studi kasus ini bertujuan untuk menerapkan **Pemodelan Stokastik** menggunakan metode **Geometric Brownian Motion (GBM)** guna mensimulasikan 1.000 kemungkinan skenario pergerakan harga saham BBCA dalam kurun waktu 30 hari ke depan.

Selain aspek prediksi harga, simulasi ini juga mencakup analisis risiko kuantitatif menggunakan **Value at Risk (VaR)** dengan tingkat kepercayaan 95% untuk mengestimasi kerugian maksimal dalam kondisi pasar normal.

### Tahapan Pemodelan:
1.  **Data Acquisition**: Pengambilan data historis *time-series* dari Yahoo Finance (5 Tahun Terakhir).
2.  **Statistical Analysis**: Estimasi parameter model (*Log Return*, Volatilitas, dan *Drift*).
3.  **Monte Carlo Simulation**: Pembangkitan 1.000 lintasan acak (*Random Walk*) untuk memvisualisasikan ketidakpastian harga.
4.  **Risk Assessment**: Penentuan batas kerugian maksimal (VaR 95%) dan interval kepercayaan prediksi (*Confidence Interval* 90%).

---
