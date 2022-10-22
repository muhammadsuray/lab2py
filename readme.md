#tugas bahasa pemrograman pertemuan ke-5

<br>
Nama : Muhammad Rizki <br>
Kelas : TI.22.B1<br>

### DAFTAR ISI <br>
| No | Description | 
| ----- | ----- |
| 1 | [Install Python](#Install-Python)|
| 2 | [latihan 1](#Latihan-1) |
| 3 | [latihan 2](#Latihan-2) |
| 4 | [latihan 3](#Latihan-3) |

## Install Python
1. download python pada halaman web python [di sini](https://python.org)
2. buka lalu centang bagian *add python to PATH* lalu klik install now
3. Instalasi Selesai, klik close

<br><br>

## Latihan 1
* buat file latihan1.py
* tulis kode seperti contoh

```python
#menampilkan tulisan 'Hello' di layar
print("Hello")
#menampilkan tulisan 'Saya sedang belajar python' di layar
print("Saya sedang belajar python")
```
* lakukan run file
* maka akan muncul program yang dijalankan

```
Hello
Saya sedang belajar python
```


## Latihan 2
* buat file latihan2.py
* tulis kode seperti contoh

``` python
# menjumlahkan dua bilangan menggunakan variabel a & b
a = 8
b = 6

print("Variabel a =",a)
print("Variabel b =",b)
print("hasil penjumlahan a + b =", a+b)
```
* lakukan running file
* maka akan muncul program yang dijalankan

```
Variabel a = 8
Variabel b = 6
hasil penjumlahan a + b = 14
```


## Latihan 3
* buat file latihan3.py
* tulis kode seperti contoh

```python
#input nilai variabel
a = input("masukan nilai pertama: ")
b = input("masukan nilai kedua: ")

#cetak nilai variabel
print("variabel a = ", a)
print("variabel b = ", b)

#cetak hasil kedua operasi variabel dengan string format
print("Hasil Penggabungan {1} & {0} = ".format(a,b) + str(a)+str(b))

#konversi nilai variabel 
a = int(a);
b = int(b);

print("Hasil penjumlahan {1} + {0} = %d".format(a,b) %(a+b))
print("Hasil pembagian {1} / {0} = %d".format(a,b) %(a/b))
```
* lakukan run file
* maka akan muncul program yang dijalankan, jangan lupa masukan angka

```
masukan nilai pertama: 6
masukan nilai kedua: 8
variabel a =  6
variabel b =  8
Hasil Penggabungan 8 & 6 = 68
Hasil penjumlahan 8 + 6 = 14
Hasil pembagian 8 / 6 = 0
```
