BIODATA
MUHAMAD WAFA MUFIDA ZULFI
312410334
TI.24.A4
BAHASA PEMOGRAMAN
LATIHAN 1
MEMBUAT PROGRAM MENENTUKAN NILAI AKHIR
DESKRIPSI
Program ini dirancang untuk menghitung nilai akhir mahasiswa berdasarkan beberapa komponen penilaian, seperti nilai UTS (Ujian Tengah Semester), UAS (Ujian Akhir Semester), dan tugas. Program akan menampilkan nilai akhir dan memberikan keterangan mengenai status kelulusan.

20% untuk nilai tugas
40% untuk nilai UTS
40% untuk nilau UAS
PENJELASAN PROGRAM
1.Input: Meminta nama siswa dan nilai UTS, UAS, serta tugas.

Perhitungan: Menghitung nilai akhir dengan bobot yang sesuai.

Keterangan: Menentukan apakah siswa lulus atau tidak berdasarkan nilai akhir.

Penentuan Huruf: Mengonversi nilai akhir menjadi huruf sesuai dengan kriteria yang diberikan.

Output: Menampilkan hasil perhitungan.

STRUKTUR PROGRAM
Input:

• Nama siswa

• Nilai UTS (float)

• Nilai UAS (float)

• Nilai Tugas (float)

Output:

• Nama siswa

• Nilai UTS

• Nilai UAS

• Nilai Tugas

• Nilai Akhir

• Nilai Huruf

• Keterangan ("LULUS" atau "TIDAK LULUS")

BERIKUT SCREENSHOT VISUALCODE
Screenshot 2024-10-25 142332
LATIHAN 2
MEMBUAT PROGRAM MENAMPILKAN GAJI KARYAWAN
DESKRIPSI
Program ini menerima input gaji, status keluarga (sudah berkeluarga atau belum), dan status kepemilikan rumah dari pengguna, kemudian melakukan beberapa pengecekan sebagai berikut:

Apakah gaji di atas UMR (Upah Minimum Regional).

Jika gaji di atas UMR, program akan mengecek apakah pengguna sudah berkeluarga untuk menentukan kewajibam mengikuti asuransi dan menabung.

Program juga mengecek apakah pengguna memiliki rumah untuk menentukan kewajiban membayar pajak rumah.

PENJELASAN PROGRAM
Input Data Karyawan:
Program meminta input dari pengguna untuk nama karyawan, gaji pokok, dan total potongan gaji. Menghitung Gaji Bersih:

Menghitung Gaji Bersih:

Gaji bersih dihitung dengan mengurangi gaji pokok dengan total potongan:

gaji_bersih

gaji_pokok − potongan

gaji_bersih=gaji_pokok−potongan
Output:

Program mencetak rincian gaji karyawan, termasuk nama, gaji pokok, potongan, dan gaji bersih.

STRUKTUR PROGRAM
• Input:

• Gaji (int)

• Status berkeluarga (Y/T)

• Status kepemilikan rumah (Y/T)

• Output:

• Apakah gaji sudah di atas UMR atau belum

• Kewajiban mengikuti asuransi jika sudah berkeluarga

• Kewajiban membayar pajak rumah jika punya rumah
GAJI DI BAWAH UMR
WhatsApp Image 2024-10-25 at 15 18 35_fde8077b

BERIKUT SCREENSHOT VISUALCODE
Screenshot 2024-10-25 142936
LATIHAN 3
PENGGUNAAN KONDISI OR
DESKRIPSI
Kondisi OR adalah operator logika yang digunakan untuk mengevaluasi dua atau lebih ekspresi kondisi. Dalam bahasa pemrograman Python, operator ini memungkinkan kita untuk memeriksa beberapa kondisi sekaligus. Jika salah satu atau lebih dari kondisi tersebut bernilai True, maka keseluruhan pernyataan akan dianggap True. Sebaliknya, jika semua kondisi bernilai False, maka hasilnya adalah False. Penggunaan kondisi OR sangat berguna dalam berbagai situasi di mana beberapa kondisi perlu dievaluasi. Operator ini memudahkan pengambilan keputusan dalam logika program, sehingga membuat kode menjadi lebih ringkas dan efisien. Dengan memahami cara kerja OR, programmer dapat menciptakan skrip yang lebih kompleks dan dinamis.

PENJELASAN OR
Definisi Operator OR adalah operator logika yang digunakan untuk mengevaluasi dua atau lebih kondisi. Dalam Python, operator ini ditulis sebagai or. Jika salah satu dari kondisi tersebut bernilai True, maka keseluruhan ekspresi juga akan bernilai True. Sebaliknya, jika semua kondisi bernilai False, maka hasilnya adalah False.
Sintaksis Penggunaan dasar operator OR dalam Python adalah sebagai berikut:
if kondisi1 or kondisi2:
    # lakukan sesuatu
Contoh Penggunaan
a. Pemeriksaan Sederhana Misalnya, kita ingin mengecek apakah sebuah angka berada di luar rentang tertentu:

angka = 7
if angka < 5 or angka > 10:
    print("Angka tidak dalam rentang 5 hingga 10")
else:
    print("Angka dalam rentang 5 hingga 10")
b. Kelayakan dalam Konteks Bisnis Dalam bisnis, kita mungkin perlu memverifikasi kelayakan berdasarkan beberapa syarat:

gaji = 2500000
memiliki_rumah = True

if gaji > 5000000 or memiliki_rumah:
    print("Kelayakan pinjaman terverifikasi")
else:
    print("Kelayakan pinjaman tidak terpenuhi")
Jika gaji lebih dari 5.000.000 atau pemohon memiliki rumah, mereka dianggap layak untuk pinjaman.

c. Logika dalam Pendidikan Dalam konteks pendidikan, kita dapat menggunakan OR untuk mengevaluasi nilai siswa:

if a + b == c or b + c == a or c + a == b:
    print("BENAR")
else:
    print("SALAH")
Program ini memeriksa apakah jumlah dua bilangan sama dengan bilangan ketiga. Jika salah satu kondisi terpenuhi, outputnya adalah "BENAR".

Keuntungan Menggunakan OR
Menyederhanakan Kode: Operator OR memungkinkan kita untuk menggabungkan beberapa kondisi dalam satu pernyataan, yang membuat kode lebih bersih dan mudah dibaca.

Fleksibilitas: Dengan menggunakan OR, kita bisa menetapkan kriteria yang lebih fleksibel untuk logika keputusan.

KESIMPULAN
Operator OR adalah alat yang sangat berguna dalam pemrograman untuk mengevaluasi beberapa kondisi. Memahami cara kerjanya memungkinkan programmer untuk membuat logika yang lebih kompleks dan dinamis dalam aplikasi mereka. Jika ada yang ingin Anda tanyakan lebih lanjut, silakan beri tahu!

STRUKTUR PROGRAM
Input Data:
Menggunakan input() untuk meminta pengguna memasukkan nama, gaji, dan status kepemilikan rumah. Gaji diambil sebagai float untuk memungkinkan nilai desimal. Status kepemilikan rumah diubah menjadi boolean dengan membandingkan input dengan "Y".

Proses Logika Menggunakan OR:
Menggunakan pernyataan if untuk mengevaluasi apakah gaji lebih dari 5.000.000 atau jika pengguna memiliki rumah. Jika salah satu kondisi bernilai True, maka variabel kelayakan diatur menjadi "layak untuk mendapatkan pinjaman." Jika tidak, diatur menjadi "tidak layak untuk mendapatkan pinjaman."

Output Hasil:
Menggunakan print() untuk menampilkan hasil kepada pengguna, termasuk nama, gaji, dan kelayakan pinjaman.

BERIKUT HASIL SCREENSHOOT VISUALCODE
Screenshot 2024-10-25 143250
About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 1 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
Python
100.0%
Footer
