# Tupro_Fuzzy

Dalam Program :

1) Membaca Data

2) Fuzzification

3) Defuzzification

4) Output ke File

Langkah - Langkah :

1) Jumlah dan Nama Linguistik Setiap Atribut Input

        untuk kategori "Harga" terdapat 3 batas yang digunakan dengan label ["Murah", "Sedang", "Mahal"]
        untuk kategori "Servis" terdapat 4 batas yang digunakan dengan label ["Buruk", "Biasa", "Bagus", "Sangat Bagus"]

2) Bentuk dan Batas Fungsi Keanggotaan Input

        Bentuk untuk Fuzzy Set : 
        1) Bentuk Trapesium 
        2) Bentuk Segitiga.

        Fuzzy set untuk kategori "Harga" rentang [1,10] :
        1) Murah  (c = 3, d = 4)
        2) Sedang (a = 3, b = 5, c = 7)
        3) Mahal  (a = 6, b = 7)

        Fuzzy set untuk kategoti "Servis" rentang [1,100] :
        1) Buruk        (c = 15, d = 25)
        2) Biasa        (a = 15, b = 25, c = 45, d = 55)
        3) Bagus        (a = 45, b = 55, c = 75, d = 85)
        4) Sangat Bagus (a = 75, b = 85)

3) Aturan Inferensi

4) Metode Defuzzification

5) Bentuk dan Batas Fungsi Keanggotaan Output (sesuai metode Defuzzification)