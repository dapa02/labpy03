LATIHAN 1 STRUKTUR KONDISI

int(input("masukan nilai a:")) untuk memasukkan nilai variable A
int(input("masukan nilai b:")) untuk memasukkan nilai variable B
if a>b maka a paling besar
print("A yang paling besar")
if b>a maka b paling besar
print("B yang paling besar")


LATIHAN 2 STRUKTUR KONDISI

data = [] untuk input data
for i in range(5):
y = int(input("Masukan Bilangan: ")) data.append(y) untuk mengurutkan data
list.sort(data) untuk mengurutkan data dari yang terkecil
print("Urutan bilangan",data)


LATIHAN 1 PERULANGAN

print("Tables")
for i in range(1,10): Uuntuk memasukan bilangan 1 sampai 9
print(i, end="\t") print()
for j in range(1,10):
for k in range(1,10):
print(j + k, end="\t")
print("\n")

LATIHAN 2 PERULANGAN

print ('Tampilkan n Bilangan Acak yang Lebih Kecil Dari 0.5') Untuk Menampilkan atau Mencetak kalimat Tampilkan N Bilangan Acak yang Lebih Kecil Dari 0.5
jumlah=int(input("Masukan Jumlah N : ")) Untuk menentukan jumlah input yang di inginkan sesuai tipe data yaitu interger tipe data bilangan bulat
import random*
i in range ( jumlah ) : Untuk Pengulangan dengan range jumlah
print("Data ke", 1+i,"=>", (random.uniform(0.1,0.5))) Untuk menampilkan atau mencetak urutan data sesuai jumlah inputan dengan hasil di bawah 0.5
