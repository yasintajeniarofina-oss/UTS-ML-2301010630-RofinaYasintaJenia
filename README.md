# UTS Machine Learning — Jalur C (Clustering)

## Identitas Mahasiswa
* **Nama:** Rofina Yasinta Jenia
* **NIM:** 2301010630
* **Topik / Jalur:** Jalur C — Clustering (K-Means) menggunakan kerangka CRISP-DM
* **Random Seed:** `630`

## Dataset
* **Nama Dataset:** Retail Sales Dataset (`retail_sales_dataset.csv`)
* **Ukuran Awal:** 1.000 baris transaksi, 9 kolom awal (tanpa label target)
* **Fitur Utama Clustering:** `Age`, `Quantity`, `Price per Unit`, `Total Amount` (beserta analisis konteks pada `Product Category` dan `Gender`)

## Struktur Repository
* `UTS_ML_2301010630_Rofina_Yasinta_Jenia.ipynb` — Notebook lengkap seluruh tahapan CRISP-DM (pemahaman masalah/data, eksplorasi & visualisasi, pra-pemrosesan dengan IQR & `StandardScaler`, pemodelan & evaluasi grid `k = 2..8` dengan `BEST_K = 4`, serta kesimpulan) beserta sel teks **Keputusan saya**.
* `README.md` — Dokumentasi singkat proyek dan pernyataan penggunaan AI.

## Pernyataan Penggunaan AI
* **Alat AI yang Digunakan:** Gemini (asisten AI percakapan).
* **Bagian yang Dibantu AI:** Membantu merapikan struktur tahapan CRISP-DM, meninjau alur kode pra-pemrosesan/evaluasi clustering, serta membantu menyusun draf narasi penjelasan dan dokumentasi.
* **Cara Memeriksa & Memverifikasi Hasil:** Seluruh kode dijalankan dan diperiksa langsung di Google Colab (`Jalankan semua`), output numerik serta visualisasi diverifikasi kesesuaiannya dengan data `retail_sales_dataset.csv`, dan keputusan analitis disesuaikan serta ditinjau kembali 
