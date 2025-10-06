# 🧠 Tugas Besar 1 IF3070 - Dasar Inteligensi Artifisial  
### *Pencarian Solusi Pengepakan Barang (Bin Packing Problem) dengan Local Search*  

## 📋 Deskripsi  
Repositori ini berisi implementasi tiga algoritma **Local Search** — *Hill Climbing*, *Simulated Annealing*, dan *Genetic Algorithm* — untuk menyelesaikan masalah **Bin Packing Problem**, yaitu menempatkan barang berukuran berbeda ke dalam sejumlah kontainer berkapasitas sama dengan tujuan meminimalkan jumlah kontainer yang digunakan.

## 🧩 Algoritma yang Diimplementasikan  
1. **Hill Climbing** (Steepest Ascent / Stochastic / Sideways / Random Restart)  
2. **Simulated Annealing**  
3. **Genetic Algorithm**

Setiap algoritma diuji minimal tiga kali dan hasilnya divisualisasikan melalui grafik perkembangan *objective function* terhadap jumlah iterasi.

## ⚙️ Struktur Folder  
```
├── src/
│   ├── hill_climbing.py
│   ├── simulated_annealing.py
│   ├── genetic_algorithm.py
│   └── utils.py
├── doc/
│   └── laporan_TB1_IF3070.pdf
├── data/
│   └── sample_input.json
└── README.md
````

## 🚀 Cara Menjalankan Program  
1. Clone repositori ini:  
   ```bash
   git clone https://github.com/<username>/TB1-IF3070-BinPacking.git
   cd TB1-IF3070-BinPacking
   2. Pastikan Python 3.8+ telah terpasang.
3. Instal dependensi (jika ada):

   ```bash
   pip install -r requirements.txt
   ```
4. Jalankan salah satu algoritma, contoh:

   ```bash
   python src/hill_climbing.py
   ```

## 📊 Output Program

* Visualisasi *state* awal dan akhir
* Plot nilai *objective function* terhadap iterasi
* Waktu eksekusi dan hasil perbandingan algoritma
