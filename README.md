# Prediksi Resistensi Antibiotik pada Mycobacterium tuberculosis

## Deskripsi Proyek
Proyek ini merupakan implementasi model machine learning untuk memprediksi resistensi antibiotik pada bakteri Mycobacterium tuberculosis berdasarkan sekuens epitop. Model menggunakan teknik k-mer featurization untuk mengekstrak fitur dari sekuens DNA dan melakukan klasifikasi multi-label untuk 11 jenis antibiotik.

## Tim Pengembang
Proyek ini dibuat untuk memenuhi tugas mata kuliah **IF3211 - Komputasi Domain Spesifik** di Institut Teknologi Bandung.

**Kelompok 9:**
1. David Dewanto - 18222027
2. Ricky Wijaya - 18222043
3. Dedy Hofmanindo Saragih - 18222085

## Struktur File
- `1 - Model.ipynb` - Notebook utama yang berisi implementasi model machine learning
- `2 - VisualisasiLaporan.ipynb` - Notebook untuk membuat visualisasi fungsi sigmoid
- `datafix.csv` - Dataset yang berisi informasi epitop dan resistensi antibiotik

## Model yang Diimplementasikan
1. **Random Forest Classifier**
2. **Decision Tree Classifier** (performa terbaik dengan Hamming Loss: 0.0140)
3. **Logistic Regression**

## Fitur Utama
- Preprocessing data dengan k-mer featurization (k=6)
- Klasifikasi multi-label untuk 11 antibiotik
- Visualisasi fungsi sigmoid untuk penjelasan model
- Interface sederhana untuk prediksi resistensi berdasarkan input sekuens

## Antibiotik yang Diprediksi
- Amikacin
- Amoxicillin
- Capreomycin
- Ciprofloxacin
- Ethambutol
- Isoniazid
- Kanamycin
- Moxifloxacin
- Pyrazinamide
- Rifampin
- Streptomycin

## Cara Penggunaan
1. Jalankan notebook `1 - Model.ipynb` untuk melatih model
2. Masukkan sekuens epitop pada bagian testing untuk mendapatkan prediksi resistensi
3. Gunakan notebook `2 - VisualisasiLaporan.ipynb` untuk membuat visualisasi