---
title: Ensemble multiple CNNs methods with partial training set for vehicle image classification
authors: Narong Boonsirisumpun, Olarik Surinta
year: 2022
doi: 
zotero: zotero://select/items/@boonsirisumpunEnsembleMultipleCNNs2022
tags: literature
---

## Introduction

- Menggunakan **Ensemble Method** 
- Bertujuan untuk melihat performa dari **Ensemble Method** dengan **Multiple CNN models**

## Method

- **Ensemble method** yang digunakan adalah ***Unweighted average method*** dan ***Majority vote method*** 
- **Unweighted**: menjumlahkan semua probabilitas kemudian dibagi jumlah model
- **Majority**: pake argmax

## Result/Discussion

- Eksperimen untuk melihat *ensemble multiple CNN* vs *single model*
- Dengan 5 CNN model secara bersama dapat meningkatkan akurasi namun butuh waktu lama
- Solusi dengan menggunakan training set yang lebih kecil (**partial**)

## Conclusion

- ***Slicing training set*** dapat mengurangi waktu proses hingga 60%
- Future work: tuning *hyperparameters* (model combination, size of partial training set)
