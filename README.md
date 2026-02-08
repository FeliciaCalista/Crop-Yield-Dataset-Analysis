# Crop-Yield-Dataset-Analysis

## Project Overview

Proyek ini bertujuan untuk menganalisis faktor-faktor yang memengaruhi hasil panen (crop yield) menggunakan teknik data cleaning, feature selection, dan exploratory data analysis (EDA). Analisis difokuskan pada hubungan antara hasil panen dengan variabel seperti penggunaan pestisida, curah hujan, suhu, negara, dan jenis tanaman.

Melalui pendekatan statistik dan visualisasi data, proyek ini mengeksplorasi tren produksi pertanian global serta efisiensi penggunaan pestisida.

## Dataset

Dataset berisi data hasil panen berbagai tanaman dari banyak negara dan tahun, termasuk:

* Negara (Area)
* Jenis tanaman (Item)
* Tahun
* Yield (hg/ha)
* Curah hujan tahunan
* Penggunaan pestisida
* Suhu rata-rata

## Data Preprocessing

* Missing Values Handling
* Outlier Removal

## Feature Selection

* Mutual Information
* ANOVA (F-test)

Fitur paling berpengaruh:
* pesticides_tonnes
* Item
* average_rain_fall_mm_per_year

## Exploratory Data Analysis (EDA)

* Tren Yield per Tahun
* Negara dengan Perubahan Yield Terbesar
* Hubungan Pestisida vs Yield
* Negara dengan Penggunaan Pestisida Tertinggi
* Efisiensi Produksi
* Ketergantungan Pestisida per Negara

## Key Insights

* Yield global meningkat seiring waktu
* Pestisida bukan satu-satunya faktor utama
* Efisiensi berbeda antar negara
* Beberapa negara sangat bergantung pada pestisida

## Future Improvements

- Machine learning prediction model
- Advanced statistical analysis
- Time-series forecasting
