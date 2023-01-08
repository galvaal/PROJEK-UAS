# PROJEK-UAS

# NAMA : Galva Al Godzali

# NIM : 312210356

# KELAS : TI.22.A.3

# Tugas membuat Package and Modul

Tugas yang diberikan memiliki soal sebagai berikut

![soal](https://user-images.githubusercontent.com/115516730/210776639-0ae445a9-a010-4fe7-b623-43abe885cd4f.png)

Penjelsan

#model

# Daftar_Nilai

•	data = {} untuk menampung list data yang nanti akan terinput

•	deklarasikan fungsi def tambah_data():

•	nama = input("Masukan nama: ") lalu tambahkan input nama, nim, nilai tugas, uts, uas

•	nilai_akhir = (nilai_tugas)*30/100 + (nilai_uts)*35/100 + (nilai_uas)*35/100  untuk nilai akhir diambil dari perhitungan 3 komponen nilai (nilai_tugas: 30%, nilai_uts: 35%, nilai_uas: 35%)

•	data[nama] = [nama, nim, nilai_tugas, nilai_uts, nilai_uas, nilai_akhir] kita akan masukkan data yang tadi kita input ke dalam `data[nama]'

•	lalu cetak print()

# Ubah Data

•	deklarasikan fungsi def ubah_data():

•	nama = input("Masukan nama untuk mengubah data: ") kita akan menginput data yang nanti akan di ubah

•	if nama in data.keys(): print("Mau mengubah apa?") jika 'nama' dari di dalam 'data' maka akan mengembalikan daftar menggunakan fungsi 'keys()' lalu di cetak lah 'print()'

•	sub_data = input("(Semua), (Nama), (NIM), (Tugas), (UTS), (UAS) : ") membuat menu ubah di dalam sub_data

•	if sub_data.lower() == "semua": ambil kata kunci 'semua' di dalam sub_data jika 'semua' maka input data[nama][1] = input("Ubah NIM:") data[nama][2] = int(input("Ubah Nilai Tugas: ")) data[nama][3] = int(input("Ubah Nilai UTS: ")) data[nama][4] = int(input("Ubah Nilai UAS: "))

•	data[nama][5] = data[nama][2] *30/100 + data[nama][3]*35/100 + data[nama][4] *35/100  kita dapatkan nilai akhir dengan diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%), ket: [5] = nilai_akhir, dimana [0] = nama

•	lalu cetak print("\nBerhasil ubah data!")

•	Jika kita ingin mengubah data tertentu maka elif sub_data.lower() == "nim": data[nama][1] = input("NIM:") dan berlaku juga untuk nilai tugas, UTS dan UAS

•	lalu cetak print("\nBerhasil ubah data!")

•	else: print("'{}' tidak ditemukan.".format(nama)) jika kita salah dalam memasukkan nama untuk mengubah data maka akan muncul 'nama tidak di temukan'

# Cari Data

•	deklarasikan fungsi def cari_data():

•	nama = input("Masukan nama untuk mencari data: ") kita akan menginput data yang nanti akan di cari

•	if nama in data.keys(): kita mengambil list 'nama' di dalam 'data' menggunakan pengkondisian

•	maka cetak print("| {0:14} | {1:9} | {2:5} | {3:5} | {4:5} | {5:5}" .format(nama, data[nama][1], data[nama][2], data[nama][3], data[nama][4], data[nama][5])) untuk menampilkan data yang tersedia

•	else: print("'{}' tidak ditemukan.".format(nama)) jika data yang kita input salah/tidak ditemukan maka akan tercetak 'nama tidak di temukan'
Hapus data

•	deklarasikan fungsi def hapus_data():

•	nama = input("Masukan nama untuk menghapus data : ") kita akan menginput data yang nanti akan di hapus

•	if nama in data.keys(): kita mengambil list 'nama' di dalam 'data' menggunakan pengkondisian

•	del data[nama] hapus semua 'nama' yang ada di dalam 'data'

•	jika sudah maka cetak print("sub_data '{}' berhasil dihapus.".format(nama))

•	else: print("'{}' tidak ditemukan.".format(nama)) jika data yang kita input salah/tidak ditemukan maka akan tercetak 'nama tidak di temukan'

# Hapus Data

•	deklarasikan fungsi def hapus_data():

•	nama = input("Masukan nama untuk menghapus data : ") kita akan menginput data yang nanti akan di hapus

•	if nama in data.keys(): kita mengambil list 'nama' di dalam 'data' menggunakan pengkondisian

•	del data[nama] hapus semua 'nama' yang ada di dalam 'data'

•	jika sudah maka cetak print("sub_data '{}' berhasil dihapus.".format(nama))

•	else: print("'{}' tidak ditemukan.".format(nama)) jika data yang kita input salah/tidak ditemukan maka akan tercetak 'nama tidak di temukan'

#View

# Input Nilai

•	menambahkan fungsi input yang nanti nya akan di deklarasikan di setiap module nya, def input_nama(): def input_nim(): dan yg lainnya, yang nanti akan di masukkan kedalam data={}

# View Nilai

•	deklarasikan fungsi def lihat_data(): Kita menggunakan kondisi percabangan if, ambil data dari data

•	lalu cetak print()

Maka OUTPUT yg didaptkan adalah

HURUF T

![huruf T](https://user-images.githubusercontent.com/115516730/211197627-a49c138d-4448-4010-ba41-efc57fb4c46c.png)

HURUF C

![huruf C](https://user-images.githubusercontent.com/115516730/211197639-99aaba6c-7431-4b96-a837-c8de88cf4d86.png)

HURUF U

![huruf U](https://user-images.githubusercontent.com/115516730/211197678-82f16a14-debf-476d-a133-999e1274c4bc.png)

HURUF L

![huruf L](https://user-images.githubusercontent.com/115516730/211197691-fbe34744-8414-4532-af96-2341a7c272a1.png)

HURUF H

![Huruf H](https://user-images.githubusercontent.com/115516730/211197710-5035281c-b848-4e95-9973-25e62d409c1b.png)

HURUF K

![huruf K](https://user-images.githubusercontent.com/115516730/211197720-a99f202e-dfb0-420d-881b-77c481b715fc.png)

Sekian penjelasan yang saya dampaikan jika masih ada kekurangan mohon dimaafkan dan teima kasih





















