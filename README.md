Nama: Raden Bimo Rizki Prayogo

NRP: 0511740000139

# Big Data - Tugas 5

## Percobaan Konfigurasi Spark di Docker

### 2 Workers, 2 Cores

![image](img/s2_c2_set_up.PNG)

Hasil dengan 100 partisi:

![image](img/s2_c2_p100_res.PNG)

Hasil dengan 1000 partisi:

![image](img/s2_c2_p1000_res.PNG)

### 2 Workers, 4 Cores

![image](img/s2_c4_set_up.PNG)

Hasil dengan 100 partisi:

![image](img/s2_c4_p100_res.PNG)

Hasil dengan 1000 partisi:

![image](img/s2_c4_p1000_res.PNG)

### 5 Workers, 2 Cores

![image](img/s5_c2_set_up.PNG)

Hasil dengan 100 partisi:

![image](img/s5_c2_p100_res.PNG)

Hasil dengan 1000 partisi:

![image](img/s5_c2_p1000_res.PNG)


### 5 Workers, 4 Cores

![image](img/s5_c4_set_up.PNG)

Hasil dengan 100 partisi:

![image](img/s5_c4_p100_res.PNG)

Hasil dengan 1000 partisi:

![image](img/s5_c4_p1000_res.PNG)


## Kesimpulan

Partisi harus sesuai dengan kompleksitas pekerjaan. Partisi yang banyak pada task yang simple hanya akan menyebabkan bottleneck, karena spark perlu melakukan distribusi pekerjaan dan penggabungan hasil.

Jumlah partisi harus disesuaikan dengan jumlah worker.