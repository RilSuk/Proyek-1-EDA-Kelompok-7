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

1. **Jam 16.00 adalah jam paling ramai.** Volume kendaraan paling tinggi terjadi di sore hari pada jam pulang kerja.
2. **Hujan tidak otomatis bikin jalan sepi.** Rata-rata volume saat hujan sekitar 3.292 kendaraan/jam, hampir sama dengan saat tidak hujan (3.257 kendaraan/jam). Baru saat curah hujan makin tinggi, rata-ratanya turun jadi sekitar 2.784 kendaraan/jam.
3. **Hari kerja tidak sama ramainya.** Jumat paling ramai, Senin paling sepi di antara hari kerja, dan Minggu adalah hari paling sepi secara keseluruhan.

Catatan: ada data suhu bernilai 0 Kelvin yang kami anggap error sensor, dan kolom `holiday` banyak yang kosong karena hanya diisi saat hari libur nasional.

---

## Cara Menjalankan Notebook

1. Pastikan Python sudah terpasang, lalu install library yang dibutuhkan:
   ```
   pip install pandas matplotlib jupyter
   ```
2. Download dataset dari link di atas, lalu simpan file `Metro_Interstate_Traffic_Volume.csv` ke dalam folder `data/` (sejajar dengan file notebook).
3. Buka notebook dengan perintah:
   ```
   jupyter notebook Tugas_EDA_kelompok.ipynb
   ```
4. Jalankan semua cell dari atas ke bawah (**Run All**).

Kalau muncul error `FileNotFoundError`, cek lagi path file CSV di cell `pd.read_csv(...)` dan sesuaikan dengan lokasi file di komputer kalian.

