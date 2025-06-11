# UAS Penambangan Data Project: Menemukan Pola Asosiasi Yang Mempengaruhi Nilai Mahasiswa Dengan Algoritma Apriori dan FP - Growth

## Proyek
**Judul**: Penerapan Algoritma Apriori dan FP-Growth Dalam Menemukan Pola Asosiasi Faktor Yang Mempengaruhi Nilai Mahasiswa  
**Topik**: Association Rule Mining 
**MataKuliah**: Penambangan Data 2023C
**Dataset**: https://archive.ics.uci.edu/dataset/856/higher%2Beducation%2Bstudents%2Bperformance%2Bevaluation?utm_source=  

**Anggota Tim (Kelompok 8 - 2023C)**:  
1. Anisa Khaynun Najwa (23031554007)
2. Thea Bayu Revalina (23031554035)
3. Danisa Ariatna Putri (23031554048)

## Pendahuluan 
Keberhasilan akademik mahasiswa, seperti Indeks Prestasi Kumulatif (GPA), dipengaruhi oleh berbagai faktor internal dan eksternal. Melalui pendekatan data mining, pola-pola tersembunyi dalam data pendidikan dapat diungkap dan dimanfaatkan untuk meningkatkan mutu pembelajaran. Penelitian ini bertujuan untuk menerapkan algoritma Apriori dan FP-Growth pada dataset mahasiswa guna menemukan pola asosiasi antar nilai mata kuliah serta mengidentifikasi faktor-faktor yang paling berkontribusi terhadap prestasi akademik. Dengan menganalisis hubungan antar nilai dan variabel-variabel terkait. Hasil dari penelitian ini diharapkan dapat memberikan insight bagi pengambilan keputusan dalam dunia pendidikan, khususnya dalam upaya meningkatkan pencapaian akademik mahasiswa.

## Tujuan
1. Menerapkan algoritma Apriori dan FP-Growth untuk menganalisis data mahasiswa dalam menemukan pola asosiasi yang mempengaruhi nilai mahasiswa.
2. Mengidentifikasi hubungan keseluruhan faktor yang mempengaruhi nilai mahasiswa.
3. Mengidentifikasi hasil perbandingan antara algoritma Apriori dan algoritma FP-Growth yang paling optimal untuk menemukan pola asosiasi.
4. Mengindentifikasi kebutuhan mahasiswa dalam meningkatkan prestasi akademik.

---

## Visualisasi Hasil
Proyek ini menghasilkan **graf jaringan aturan asosiasi** berdasarkan algoritma FP-Growth, yang memvisualisasikan hubungan antar variabel dengan nilai **lift tertinggi**. Beberapa temuan kunci:
- **Jenis Kelamin dan IPK**: Mahasiswa dengan jenis kelamin 2 cenderung memiliki ekspektasi IPK kelulusan 4.00 dan output grade 7.  
- **IPK Tinggi dan Persepsi Proyek**: Mahasiswa dengan IPK semester terakhir 5.00 menunjukkan persepsi positif terhadap proyek, yang berkorelasi dengan nilai output tinggi.  
- **Hubungan Faktor**: Jenis kelamin, IPK sebelumnya, dan persepsi terhadap proyek memainkan peran penting dalam membentuk ekspektasi dan hasil akademik.

Visualisasi ini memberikan wawasan / insight visual tentang hubungan antar variabel, yang dapat digunakan untuk pengambilan keputusan strategis dalam pendidikan.

---

## Struktur Folder
```
📁 Penambangan Data/
├── README.md               # Dokumentasi proyek (file ini)
├── data_mining.ipnyb       # Berisi notebook proses dan kode yang dijalankan 
├── datmin.csv              # Dataset awal 
├── requirements.txt        # Daftar pustaka yang dibutuhkan
```
---

## Cara Menjalankan code 
1. **Clone Repository**:
   ```bash
   git clone <repository-url>
   cd Penambangan_Data
   ```
2. **Instal Dependensi**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Jalankan Notebook**:
   Buka `data_mining.ipynb` menggunakan Jupyter Notebook atau Google Colab, lalu jalankan sel-sel kode secara berurutan.
4. **Dataset**:
   Pastikan file `datmin.csv` berada di direktori yang sama dengan notebook.

---

## Tools yang Digunakan
- **Python**: Bahasa pemrograman utama untuk analisis data.
- **Pandas**: Untuk manipulasi dan analisis data.
- **MLxtend**: Untuk implementasi algoritma Apriori dan FP-Growth.
- **NetworkX**: Untuk visualisasi graf jaringan aturan asosiasi.
- **Matplotlib/Seaborn**: Untuk visualisasi tambahan.

---

## Lisensi
Proyek ini dibuat untuk keperluan akademik sebagai bagian dari tugas UAS Penambangan Data untuk Kelompok 8 (2023C).
