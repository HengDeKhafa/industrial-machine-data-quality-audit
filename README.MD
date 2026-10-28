# Industrial Machine Data Quality Audit

## Tujuan
Proyek portofolio untuk memeriksa kualitas data pada AI4I 2020 Predictive
Maintenance Dataset menggunakan Python, Pandas, dan NumPy.

## Pemeriksaan
- Nilai kosong
- Baris duplikat dan keunikan UDI
- Kandidat nilai ekstrem
- Ringkasan perubahan data sensor

## Dataset
AI4I 2020 adalah dataset sintetis dari UCI Machine Learning Repository.
Penjelasan kolom dan catatan dataset ada di [dataset_notes.md](dataset_notes.md).

Sumber: https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset

## Menjalankan proyek
Petunjuk instalasi dan cara menjalankan notebook akan ditambahkan di sini.

## Batasan
Temuan statistik menunjukkan data yang perlu ditinjau lebih lanjut.
Temuan tersebut tidak membuktikan penyebab kerusakan mesin atau kondisi mesin nyata.

## Isi Proyek

- `01_data_quality_audit.ipynb` — notebook analisis kualitas data.
- `ai4i2020.csv` — dataset yang digunakan.
- `dataset_notes.md` — sumber dan keterangan kolom dataset.
- `Requirements.txt` — daftar library Python yang diperlukan.