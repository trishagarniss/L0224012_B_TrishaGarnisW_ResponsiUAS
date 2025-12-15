# Simulasi Prediksi Harga Saham BBCA Menggunakan Geometric Brownian Motion (GBM)

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-Academic-green)

> **Responsi UAS Pemodelan dan Simulasi**
> <br> *Studi kasus prediksi pergerakan harga saham PT Bank Central Asia Tbk (BBCA) dan pengukuran risiko investasi menggunakan metode simulasi Monte Carlo.*

---

## Identitas Mahasiswa
| Atribut | Detail |
| :--- | :--- |
| **Nama** | Trisha Garnis W |
| **NIM** | L0224012 |
| **Kelas** | B |
| **Mata Kuliah** | Pemodelan dan Simulasi |

---

## Deskripsi Studi Kasus
Saham merupakan instrumen investasi dinamis dengan tingkat volatilitas yang tinggi. Proyek ini bertujuan menerapkan **Pemodelan Stokastik** menggunakan metode **Geometric Brownian Motion (GBM)** untuk mensimulasikan **1.000 skenario** pergerakan harga saham BBCA dalam kurun waktu **31 hari** ke depan.

Selain aspek prediksi, simulasi ini difokuskan pada analisis risiko kuantitatif menggunakan **Value at Risk (VaR)** dengan tingkat kepercayaan 95% (*Confidence Level*) guna mengestimasi potensi kerugian maksimal (*Maximum Potential Loss*) dalam kondisi pasar normal.

### Tahapan Pemodelan:
1.  **Data Acquisition**: Pengunduhan data historis *time-series* dari Yahoo Finance (`yfinance`) selama 5 tahun terakhir.
2.  **Statistical Analysis**: Perhitungan parameter kunci model meliputi *Log Return*, *Drift* (tren rata-rata), dan *Volatility* (standar deviasi).
3.  **Monte Carlo Simulation**: Pembangkitan 1.000 lintasan acak (*Random Walk*) berdasarkan persamaan stokastik GBM untuk memvisualisasikan ketidakpastian.
4.  **Risk Assessment**: Perhitungan statistik deskriptif hasil simulasi, penentuan interval kepercayaan, dan estimasi nilai **VaR (95%)**.

---
