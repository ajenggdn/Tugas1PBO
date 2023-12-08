1. -for i in range(1, 101):
Ini adalah struktur pengulangan for yang akan menjalankan blok kode di bawahnya sebanyak 100 kali (mulai dari 1 hingga 100). Setiap kali iterasi, nilai i akan diisi dengan nilai dari 1 hingga 100.

-if i % 10 == 0:
Ini adalah kondisi yang mengecek apakah nilai dari i habis dibagi 10 (artinya sisa bagi adalah 0) menggunakan operator modulo %. Jika hasil sisa bagi dari i dengan 10 adalah 0, maka kondisi ini terpenuhi.

-print("Diajeng Noviana Sari")
Jika nilai i habis dibagi 10, maka pernyataan ini akan dicetak, yaitu "Diajeng Noviana Sari".

-else:
Ini adalah bagian alternatif dari kondisi. Jika nilai i tidak habis dibagi 10, maka blok kode di bawah else yang akan dieksekusi.
print(i)
Jika nilai i tidak habis dibagi 10, maka nilai i akan dicetak.

Jadi, saat kode dijalankan:
Setiap angka dari 1 hingga 100 akan diiterasi.
Jika angka tersebut habis dibagi 10, maka akan mencetak "Diajeng Noviana Sari".
Jika angka tersebut tidak habis dibagi 10, maka akan mencetak nilai dari angka tersebut.
![image](https://github.com/ajenggdn/Tugas1PBO/assets/145746946/c2c74c80-69f8-466d-80b1-d8cc203503f6)

2.a
-for i in range(1, 11):
Ini adalah struktur pengulangan for yang akan melakukan iterasi dari 1 hingga 10 (range(1, 11)). Setiap iterasi, nilai i akan diisi dengan angka dalam rentang ini.

-if i % 2 == 0:
Ini adalah kondisi yang mengecek apakah nilai dari i habis dibagi 2 (artinya sisa bagi adalah 0) menggunakan operator modulo %. Jika hasil sisa bagi dari i dengan 2 adalah 0, maka kondisi ini terpenuhi dan angka tersebut merupakan angka genap.

-print(f"{i} adalah genap")
Jika nilai i habis dibagi 2, maka pernyataan ini akan dicetak, menampilkan pesan bahwa angka tersebut adalah genap.

-else:
Ini adalah bagian alternatif dari kondisi. Jika nilai i tidak habis dibagi 2, maka blok kode di bawah else yang akan dieksekusi.

print(f"{i} adalah ganjil")
Jika nilai i tidak habis dibagi 2, maka pernyataan ini akan dicetak, menampilkan pesan bahwa angka tersebut adalah ganjil.

	Kode ini memberikan contoh sederhana tentang bagaimana menggunakan loop for untuk iterasi melalui serangkaian angka dan menggunakan kondisi if-else untuk mengevaluasi apakah angka tersebut genap atau ganjil berdasarkan sisa bagi dengan 2.
![image](https://github.com/ajenggdn/Tugas1PBO/assets/145746946/d4b2992a-0e7f-4e9a-96da-780bb0ec89d6)

2.b
1.i = 1: Inisialisasi variabel i dengan nilai awal 1.

2.while i <= 10:: Ini adalah loop while yang akan berjalan selama nilai i kurang dari atau sama dengan 10. Selama kondisi ini terpenuhi, blok kode di dalamnya akan terus dieksekusi.

3.Pada setiap iterasi di dalam loop:

-if i < 5:: Ini adalah kondisi pertama yang mengecek apakah nilai i kurang dari 5. Jika benar, maka akan mencetak bahwa nilai i kurang dari 5.

-elif i == 5:: Ini adalah kondisi kedua yang mengecek apakah nilai i sama dengan 5. Jika benar, maka akan mencetak bahwa nilai i sama dengan 5.

-else:: Ini adalah blok alternatif jika kedua kondisi sebelumnya tidak terpenuhi, yang berarti nilai i lebih besar dari 5. Jika kondisi ini terpenuhi, maka akan mencetak bahwa nilai i lebih besar dari 5.

4.i += 1: Pernyataan ini meningkatkan nilai i dengan 1 setiap kali loop dieksekusi. Ini ditempatkan di bagian bawah loop untuk memastikan nilai i bertambah sehingga loop tidak berjalan secara tak terbatas (infinite loop).
![image](https://github.com/ajenggdn/Tugas1PBO/assets/145746946/788e0c6c-d5e2-4cd5-8177-a911c64097f3)

3.
1.import pandas as pd: Mengimpor library Pandas dengan alias 'pd'.
  
2.array_saya = [10, 20, 30, 40, 50]: Mendefinisikan sebuah array dengan nama 'array_saya' yang berisi beberapa nilai.
3.hasil_tabel = pd.DataFrame(columns=['Indeks', 'Nilai']): Membuat sebuah DataFrame kosong dengan dua kolom yaitu 'Indeks' dan 'Nilai'. Kolom-kolom ini akan diisi dengan indeks dan nilai dari array.

4.for indeks, nilai in enumerate(array_saya):: Melakukan loop melalui array menggunakan fungsi enumerate(), yang memberikan kemampuan untuk mengambil nilai dan indeks dari setiap elemen dalam array.

5.hasil_tabel.loc[indeks] = [indeks, nilai]: Menambahkan setiap elemen array ke dalam DataFrame kosong yang sudah dibuat sebelumnya. Di sini, loc[] digunakan untuk menetapkan nilai pada baris dengan indeks yang diberikan oleh enumerate() pada DataFrame.

6.hasil_tabel: Mengembalikan DataFrame 'hasil_tabel' yang telah diisi dengan nilai-nilai dari array.

	Hasil dari eksekusi kode ini akan menampilkan DataFrame yang berisi indeks dari elemen dalam array (mulai dari 0 sampai 4) dan nilai-nilai yang sesuai dengan array yang diberikan. 
![image](https://github.com/ajenggdn/Tugas1PBO/assets/145746946/dfbc7cb8-c858-4c6c-9fa2-c6ba1262dc45)










