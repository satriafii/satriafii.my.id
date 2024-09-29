---
title: "[ID] Heteroskedastisitas"
date: 2023-08-13T10:53:43+07:00
summary: "Sedikit catatan tentang heteroskedastisitas." 
tags: ["uji statistika", "belajar", "skripsi"]
aplayer: false
showLicence: false
draft: false
---

Sebelum disuruh ganti judul, aku harus menguji ini dulu sebelum bisa regresi. Hasilnya jelek. Makanya aku bikin satu catatan khusus dan baca apapun yang terkait dengan ini dalam waktu sangat singkat. Intinya, begini:

Uji heteroskedastisitas digunakan untuk melihat apakah ada ketidaksamaan varian dari residual pengamatan yang satu ke pengamatan lainnya. Berikut adalah beberapa metode untuk menguji ada tidaknya masalah heteroskedastisitas:
- Metode Grafik
- Park
- Glejser = Uji Glejser mengihitung nilai F dan membandingkannya dengan Ftabel untuk mengetahui apakah ada pengaruh signifikan variabel bebas terhadap harga mutlak galatnya
- Korelasi Spearman (sering disebut Spearman Rho)
- Goldfed-Quandt 
- Bruesch-Pagan-Godfrey 
- White

Pernyataan tersebut diperoleh dari buku [Analisis Regresi dengan Menggunakan Aplikasi Komputer Statistik SPSS](https://onesearch.id/Record/IOS3659.31857) oleh Fridayana Yudiaatmaja yang bisa diakses melalui gramedia digital dengan langganan full premium.

Dari [salah satu jurnal tentang hederoskedastisitas](https://jurnal.unitri.ac.id/index.php/Optima/article/view/1250) disebutkan bahwa menurut Santoso (2014) uji heteroskedastisitas dilakukan untuk mengetahui apakah di dalam sebuah model regresi terjadi ketidaksamaan varians residual dari satu pengamatan ke pengamatan yang lain tetap.

| Uji          | Aturan main                                                                                                                                                                                                  |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Spearman Rho | Jika nilai signifikansi lebih besar dari 0,05 berarti residual varians tidak mengalami heteroskedastisitas. Apabila nilai signifikansi kurang dari 0,05 maka residual varians mengalami heteroskedastisitas. |

Salah satu asumsi penting dari CLRM (Classical Linear Regression Model) adalah varians dari setiap gangguan ui, kondisional terhadap variabel penjelas yang dipilih, adalah suatu angka konstan tertentu yang setara dengan varians. Hal ini disebut homoskedastisitas (homo=sama, scedasticity/spread=persebaran). Peristiwa heteroskedastisitas tidak menghilangkan sifat konsistensi dan ketidakbiasan karakteristik estimator-estimator *ordinary least square*, nemun estimator tersebut tidak lagi memiliki varians minimum yang efisien, sehingga mereka tidak lagi menjadi estimator yang BLUE (*Best Linear Unbiased Estimator*).

Cara untuk mendeteksi peristiwa heteroskedastisitas pada suatu model adalah:
- Metode informal
	- Sifat alamiah problem
	- Metode grafis
- Metode formal
	- Uji Park
	- Uji Glejser
	- Uji Korelasi Spearman
	- Uji Goldfeld-Quandt
	- Uji Breusch-Pagan-Godfrey
	- Uji heteroskedastisitas White umum
	- Uji Koenker-Bassett

Sumber: [Dasar-dasar ekonometrika](https://archive.org/details/basiceconometric0000guja_g4u9) oleh Gujarati yang bisa diakses di internet archive atau perpustakaan kampus yang menyediakan (aku dikasih bukunya sama seorang teman yang baik hati, btw hehe).