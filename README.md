# K02-T1-IF2220
# Tugas Besar IF2220 Probabilitas dan Statistika
## Penarikan Kesimpulan dan Pengujian Hipotesis

Program ini dibuat untuk memenuhi tugas Mata Kuliah **IF2220 Probabilitas dan Statistika** <br />

*Program Studi Teknik Informatika* <br />
*Sekolah Teknik Elektro dan Informatika* <br />
*Institut Teknologi Bandung* <br />

*Semester II Tahun 2020/2021*

## Author :
1. Mahesa Lizardy (13520116)
2. Muhammad Gilang Ramadhan (13520137)

### Tujuan:
- Mahasiswa memahami dan dapat menyelesaikan persoalan distribusi peluang variabel
random diskrit dan kontinu, dan
- Mahasiswa mampu menyelesaikan persoalan untuk menarik kesimpulan mengenai
parameter populasi yang diperoleh dari data hasil eksperimen.
- Mahasiswa mampu menyelesaikan persoalan pengujian hipotesis.

## Deskripsi
Diberikan sebuah data water_potability.csv yang dapat diakses pada Dataset
Tugas Besar IF2220. water_potability.csv merupakan data metrik kualitas air yang
mengandung 11 kolom sebagai berikut:

1. id
2. pH
3. Hardness
4. Solids
5. Chloramines
6. Sulfate
7. Conductivity
8. OrganicCarbon
9. Trihalomethanes
10. Turbidity
11. Potability

Kolom 2-10 adalah kolom atribut (non-target), sedangkan kolom 11 adalah kolom target.

---
### Hipotesis 1 sampel, dengan menuliskan 6 langkah testing dan menampilkan juga boxplotnya untuk kolom/bagian yang bersesuaian
**Enam Langkah Testing:**
<br>
1. Tentukan Hipotesis nol (H0: θ = θ0), dimana θ bisa berupa μ, σ2, p, atau data lain berdistribusi tertentu (normal, binomial, dsc.).
2. Pilih hipotesis alternatif H1 salah dari dari θ > θ0 , θ < θ0 , atau θ ≠ θ0.
3. Tentukan tingkat signifikan α.
4. Tentukan uji statistik yang sesuai dan tentukan daerah kritis.
5. Hitung nilai uji statistik dari data sample. Hitung p-value sesuai dengan uji statistik yang digunakan.
6. Ambil keputusan dengan TOLAK H0 jika nilai uji terletak di daerah kritis atau dengan tes signifikan, TOLAK H0 jika p-value lebih kecil dibanding tingkat signifikansi α yang diinginkan

---
### Hipotesis 2 sampel, dengan menuliskan 6 langkah testing dan menampilkan juga boxplotnya untuk kolom/bagian yang bersesuaian.

<ul>
1. Data kolom Sulfate dibagi 2 sama rata: bagian awal dan bagian akhir kolom. Benarkah
rata-rata kedua bagian tersebut sama?
<br>
2. Data kolom OrganicCarbon dibagi 2 sama rata: bagian awal dan bagian akhir kolom.
Benarkah rata-rata bagian awal lebih besar dari pada bagian akhir sebesar 0.15?
<br>
3. Rata-rata 100 baris pertama kolom Chloramines sama dengan 100 baris terakhirnya?
<br>
4. Proporsi nilai bagian awal Turbidity yang lebih dari 4, adalah lebih besar daripada,
proporsi nilai yang sama di bagian akhir Turbidity ?
<br>
5. Bagian awal kolom Sulfate memiliki variansi yang sama dengan bagian akhirnya?
</ul>

---
### Test korelasi: tentukan apakah setiap kolom non-target berkorelasi dengan kolom target, dengan menggambarkan juga scatter plot nya. Gunakan correlation test.
Adapun metode yang digunakan adalah sebagai berikut.
1. Melakukan tes korelasi dengan metode Pearson
    - H0 : p = 0 (Tidak ada korelasi antara kolom target dan kolom non-target)
    - H1 : p ≠ 0 (Ada korelasi antara kolom target dan kolom non-target)
<br><br>
2. Jika terdapat korelasi diantara kolom non-target dan kolom target maka cari berapa koefisien korelasi diantara kedua kolom tersebut. Beberapa kesimpulan yang dapat diambil sebagai berikut :
    - 0 < Koefisien Korelasi < 1 (Positive Correlation)
    - Koefisien Korelasi = 1 (Strong Positive Correlation)
    - -1 < Koefisien Korelasi < 0 (Negative Correlation)
    - Koefisien Korelasi = -1 (Strong Negative Correlation)
    - Koefisien Korelasi = 0 (No Correlation)
<br><br>
3. Tampilkan Scatter Plot di antara dua kolom tersebut
