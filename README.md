# Pola Volume Lalu Lintas Jalan Tol Antarnegara Bagian (Metro)

## Anggota Kelompok 7
1. **Safina Nur Lathifah** - 5027261023
2. **Dyon Panangian Sitorus** - 5027261108
3. **Adib Rizqullah Baqir** - 5027261126

---

## Topik
Exploratory Data Analysis (EDA) mengenai pengaruh kondisi cuaca dan atribut waktu terhadap volume kendaraan di jalan tol Interstate 94 (Minneapolis – St. Paul, AS).

---

## Sumber Dataset dan Lisensi
* **Sumber:** Dataset [Metro Interstate Traffic Volume](https://www.kaggle.com/datasets/pooriamst/metro-interstate-traffic-volume) diunggah di Kaggle oleh pooriamst, bersumber dari UCI Machine Learning Repository (dikumpulkan oleh John Hogue dari stasiun pengukur MnDOT dan OpenWeatherMap).
* **Lisensi:** [CC BY 4.0 / Public Domain (Kaggle & UCI ML Repository).](https://creativecommons.org/licenses/by/4.0/)

---

## 3 Temuan Utama

1. Di dalam data, ditemukan angka suhu 0 Kelvin (-273,15°C). Angka ini mustahil terjadi secara fisik di dunia nyata, yang menandakan adanya kesalahan dari alat sensor atau saat pencatatan data.
2.Meskipun cuaca berawan (Clouds) paling sering mendominasi, kondisi cuaca tidak menentukan seberapa ramai jalanan. Faktanya, jalanan yang padat maupun sepi bisa saja terjadi di berbagai jenis cuaca.

Catatan: kolom `holiday` banyak yang kosong karena hanya diisi saat hari libur nasional.

---

## Cara Menjalankan Notebook

1. Pastikan Python sudah terpasang, lalu install library yang dibutuhkan:
   ```
   pip install pandas matplotlib jupyter
   ```
2. Download dataset dari link di atas, lalu simpan file `Metro_Interstate_Traffic_Volume.csv` ke dalam folder `data/` (sejajar dengan file notebook).
3. Buka anaconda prompt dan jalankan perintah:
   ```
   jupyter notebook 
   ```
4. Buka file **Tugas_EDA_kelompok.ipynb** di folder tempat anda menyimpan file
5. Buka dan jalankan semua cell dari atas ke bawah (**Run All**).
Kalau muncul error `FileNotFoundError`, cek lagi path file CSV di cell `pd.read_csv(...)` dan sesuaikan dengan lokasi file di komputer kalian.

