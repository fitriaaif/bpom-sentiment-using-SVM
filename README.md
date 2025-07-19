# 📊 Penerapan Algoritma SVM dengan PSO dan ADASYN untuk Sentimen Opini Kinerja BPOM dalam Pengawasan Produk *Skincare*

Repository ini berisi kode program untuk analisis sentimen opini publik terhadap kinerja BPOM dalam pengawasan produk *skincare*. Proyek ini menggunakan algoritma *Support Vector Machine* (SVM) untuk klasifikasi sentimen, serta menerapkan *Particle Swarm Optimization* (PSO) sebagai metode optimasi dan ADASYN (*Adaptive Synthetic Sampling*) untuk menangani ketidakseimbangan kelas.

---

## 📁 Dataset

Dataset berasal dari opini publik di media sosial X (Twitter) mengenai kinerja BPOM dalam pengawasan produk *skincare* di Indonesia.

---

## 🔍 Langkah - Langkah

- *Crawling data*
- *Data preparation* (mengecek nilai null, data duplikat, dan menghapus kolom yang tidak relevan)
- *Preprocessing data* teks (*case folding*, pembersihan, normalisasi, tokenisasi, *stopword removal*, dan *stemming*)
- Pelabelan data
- Eksplorasi data (EDA)
- Ekstraksi fitur menggunakan TF-IDF
- Optimasi parameter menggunakan PSO
- Penanganan dataset tidak seimbang menggunakan metode ADASYN
- Implementasi algoritma SVM untuk klasifikasi sentimen: positif dan negatif- 
- Evaluasi model dengan metrik:

---

## 🧰 Tools 

- Python
- re
- string
- numpy
- pandas
- matplotlib
- seaborn
- NLTK
- Sastrawi
- WordCloud
- scikit-learn
- imbalanced-learn
