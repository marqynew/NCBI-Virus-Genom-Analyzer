
# 🧬 Virus Genome Analyzer

Proyek ini adalah sebuah notebook Python interaktif untuk menganalisis genom virus secara bioinformatika menggunakan pustaka **Biopython**. Fokus utama proyek ini adalah pada virus *Barmah Forest* (Accession ID: `NC_001786.1`), namun dapat disesuaikan untuk virus lain dengan mudah.

## 🔍 Fitur Utama

- 📥 **Pengambilan Data Otomatis**  
  Ambil data genom dari NCBI menggunakan Accession ID.

- 🧪 **Analisis Komposisi Basa Nukleotida**  
  Hitung jumlah A, T, G, dan C dari genom lengkap dan CDS (Coding Sequence).

- 🧬 **Ekstraksi dan Analisis CDS**  
  Identifikasi dan gabungkan semua bagian genom yang mengkode protein.

- ⚠️ **Pendeteksian Karakter Aneh**  
  Temukan karakter non-standar dalam sekuens genom (misalnya `N`, `R`, dll).

- 🧱 **Identifikasi Structural Polyprotein**  
  Temukan dan tampilkan urutan protein struktural yang penting dari genom.

## 🧰 Tools & Teknologi

- Biopython
- NCBI Entrez & GenBank API
- Python 3.x
- Jupyter Notebook

## 🚀 Cara Menjalankan

1. **Clone repositori ini**
   git clone https://github.com/username/virus-genome-analyzer.git
   cd virus-genome-analyzer

2. **Install dependencies**
   pip install biopython

3. **Jalankan notebook**
   Buka Virus.ipynb dengan Jupyter:
   jupyter notebook Virus.ipynb

## 🔄 Ganti Virus Target

Untuk menganalisis genom virus lain, cukup ganti **accession ID** di bagian awal notebook:
record = ambil_data_genome("NC_001786.1")  # Ganti dengan ID GenBank lain

## 📄 Contoh Output

- Komposisi basa lengkap
- Komposisi CDS
- Posisi karakter aneh
- Urutan Structural Polyprotein

## 📚 Referensi

- NCBI Nucleotide Database: https://www.ncbi.nlm.nih.gov/nucleotide/
- Biopython Documentation: https://biopython.org/wiki/Documentation

## 🧑‍💻 Kontributor

- Ammar Qurthuby (ammarqurthuby@gmail.com)

---
💡 *Proyek ini sangat cocok untuk pembelajaran bioinformatika dasar, praktikum analisis sekuens, atau sebagai dasar pengembangan pipeline analisis genomik lebih lanjut.*
