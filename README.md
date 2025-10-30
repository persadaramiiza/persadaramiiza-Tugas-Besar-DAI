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
├── docs/
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
4. Jalankan salah satu algoritma experiment dengan jupyternotebook, 
## 📊 Output Program
* Visualisasi *state* awal dan akhir
* Plot nilai *objective function* terhadap iterasi
* Waktu eksekusi dan hasil perbandingan algoritma
* https://colab.research.google.com/drive/1hf3z25rMhGl8QOhynkimDKCEVUbaRsGO?usp=sharing (untuk histori perubahan pada file source code)
