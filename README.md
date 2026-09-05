# Algoritma-dan-Pemrograman-2026
Maila.Andira.Putri.2225250126
ALGORITMA DAN PEMROGRAMAN
“Menentukan Luas dan Keliling Segitiga Menggunakan Python”
1.	Deskripsi Masalah
Segitiga merupakan salah satu bangun datar yang memiliki tiga sisi. Pada tugas ini, dibuat sebuah algoritma untuk menghitung luas dan keliling segitiga berdasarkan data yang diberikan oleh pengguna. Untuk menghitung luas, diperlukan nilai alas dan tinggi segitiga, sedangkan untuk menghitung keliling diperlukan panjang ketiga sisi segitiga. Hasil akhir yang diperoleh berupa nilai luas dan keliling segitiga.
Rumus yang digunakan:

Luas segitiga:
L = ½ × a × t

Keliling segitiga:
K = s₁ + s₂ + s₃

Keterangan:
a = alas segitiga
t = tinggi segitiga
s₁ = sisi pertama
s₂ = sisi kedua
s₃ = sisi ketiga

2.	Identifikasi Input-Proses-Output
Untuk menyelesaikan permasalahan tersebut, diperlukan beberapa data masukan yang akan diproses menggunakan rumus luas dan keliling segitiga. Identifikasi input, proses, dan output yang digunakan adalah sebagai berikut.

Komponen	Keterangan 
Input	Alas (a), tinggi (t), sisi 1 (s1), sisi 2 (s2), dan sisi 3 (s3)
Proses	Menghitung luas dengan rumus L = ½ × a × t, kemudian menghitung keliling dengan rumus K = s1 + s2 + s3

Output	Nilai luas dan keliling segitiga

3.	Pseudocode
ALGORITMA LuasKelilingSegitiga
INPUT a, t, s1, s2, s3
luas ← (a × t) / 2
keliling ← s1 + s2 + s3
OUTPUT luas, keliling
SELESAI
4.	Flowchart


<img width="348" height="737" alt="image" src="https://github.com/user-attachments/assets/0994a621-f703-4b5f-b0fc-8e1e35ec56bb" />















5.	Test Case
Test Case	Alas	Tinggi	Sisi 1	Sisi 2	Sisi 3	Luas	Keliling
1	6	4	6	5	5	12	16
2	10	8	10	8	6	40	24
	Pengujian dilakukan menggunakan dua data uji untuk memastikan program dapat menghitung luas dan keliling segitiga dengan benar. Hasil yang diperoleh dari program dibandingkan dengan hasil perhitungan secara manual. Pada kedua test case, hasil program sesuai dengan hasil yang diharapkan.
6.	Implementasi Python
Algoritma yang telah dibuat kemudian diimplementasikan ke dalam bahasa pemrograman Python. Program menerima nilai alas, tinggi, dan letiga sisi segitiga sebagai input, kemudian menghitung luas dan keliling berdasarkan rumus yang telah ditentukan.
alas = float(input("Masukkan alas: "))
tinggi = float(input("Masukkan tinggi: "))
sisi1 = float(input("Masukkan sisi 1: "))
sisi2 = float(input("Masukkan sisi 2: "))
sisi3 = float(input("Masukkan sisi 3: "))

luas = 0.5 * alas * tinggi
keliling = sisi1 + sisi2 + sisi3

print("Luas segitiga =", luas)
print("Keliling segitiga =", keliling)
Program meminta pengguna memasukkan alas, tinggi, dan panjang ketiga sisi segitiga. Nilai alas dan tinggi digunakan untuk menghitung luas, sedangkan ketiga sisi digunakan untuk menghitung keliling. Setelah proses perhitungan selesai, program menampilkan hasil luas dan keliling segitiga.
7.	Hasil Pengujian
Setelah program dibuat, dilakukan pengujian menggunakan dua data yang telah ditentuksn pada test case. Pengujian dilakukan dengan memasukkan nilai ke dalam program melalui terminal pada VS Code. Hasil yang ditampilkan kemudian dibandingkan dengan hasil perhitungan yang telah dilakukan sebelumnya.
Test Case	Hasil yang diharapkan	Hasil Program	Keterangan
1	Luas = 12 cm2, keliling = 16 cm	Luas = 12.0, 
Keliling = 16.0	Sesuai
2	Luas = 40 cm2, Keliling = 24 cm	Luas = 40.0 , 
Keliling = 24.0	Sesuai
Berdasarkan hasil pengujian, program menghasilkan nilai yang sesuai dengan perhitungan yang diharapkan pada kedua test case. Dengan demikian, program dapat digunakan untuk menghitung luas dan keliling segitiga berdasarkan data yang dimasukkan oleh pengguna.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/656bd73b-4c48-4b17-a1f9-875dbe89d515" />

 
Gambar Test Case 1
 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b24582e8-6d50-4210-a85e-27f30fc34a56" />

Gambar Test case 2
