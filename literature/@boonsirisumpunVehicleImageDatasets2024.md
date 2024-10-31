---
title: Vehicle image datasets for image classification
authors: Narong Boonsirisumpun, Emmanuel Okafor, Olarik Surinta
year: 2024
doi: 10.1016/j.dib.2024.110133
zotero: zotero://select/items/@boonsirisumpunVehicleImageDatasets2024
tags:
  - literature
  - data
---

## Introduction

- Terdiri dari 2 *dataset*:
	- ***Vehicle Type Image Dataset Verision 2***: terdiri dari 5 jenis kendaraan
	- ***Vehicle Make Image Dataset***: terdiri dari gambar logo merk kendaraan
- **VTID 2** terdiri dari 4.356 gambar dari peringkat 5 terbaik jenis kendaraan yang dipakai di Thailand
- 5 kelas kendaraan dari **VTID 2**:
	- *sedans*,
	- *hatchbacks*,
	- *pick-ups*,
	- *SUVs*,
	- *other vehicles*.

## Method

- Gambar diambil menggunakan **2 kamera**  *CCTV* yang terpasang di  **gerbang Loei Rajabhat University, Loei, Thailand**
- Data diambil dalam kurung waktu **4 bulan**, yaitu bulan **Juli - Desember 2018**
- **Kamera 1** terpasang pada posisi lebih atas untuk mendapatkan *overhead perspective*, mengarah 45&deg; ke bawah
- **Kamera 2** terpasang pada posisi lebih bawah untuk mendapatkan *visual view lower perspective*
- Jenis/kategori ***Van*** digabung dengan ***Motorcycles*** menjadi kategori ***Other Vehicles***, hal tersebut dikarenakan gambar ***van*** terlalu sedikit jika dibandingkan dengan gambar jenis kendaraan lain
- Pengambilan gambar dilakukan pada **siang hari** tanpa gangguan musim atau iklim
## Result/Discussion

- **VTID 2** terdiri dari **4356** gambar:
	- **1230** *sedans*,
	- **1240** *pick-ups*,
	- **680** *SUVs*,
	- **606** *hatchbacks*,
	- **600** *other vehicles*.
- **Ukuran** gambar bervariasi dari **5 - 50 KB**
- **Wajah** dan **Nomor Plat** pada gambar dibuat **buram** untuk melindungi informasi sensitif 
- Gambar yang didapat terdiri dari **2 arah** kendaraan, yaitu:
	- kendaraan **masuk**
	- kendaraan **keluar**
- Dataset **tidak** dibagi kedalam ***training, validation, test set***
- Dilakukan penelitian pada paper [[@boonsirisumpunEnsembleMultipleCNNs2022]]
## Conclusion
- Dataset **VTID 2** yang didapat ***imbalance*** 
- Dapat ***imbalance*** dapat diatasi dengan *data augmentation* pada penelitian selanjutnya
- Dataset dapat diakses di [[https://data.mendeley.com/datasets/htsngg9tpc/2]] 



