#Tugas bahasa pemrograman pertemuan ke-5

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
1. download python pada halaman web python [di sini](https://python.org) <br>
![download python](https://user-images.githubusercontent.com/115475511/197359893-312b55d5-740a-4ecb-8dd5-2e1ccb27bbf4.PNG)
2. buka lalu centang bagian *add python to PATH* lalu klik install now <br>
![install python](https://user-images.githubusercontent.com/115475511/197359900-a854eb05-44bd-48c0-a4b8-55dbd00ad7fa.PNG)
![install python2](https://user-images.githubusercontent.com/115475511/197359901-3d8c3ec5-4ae8-46b2-b477-3f34cd000690.PNG)

3. Instalasi Selesai, klik close <br>
![install success](https://user-images.githubusercontent.com/115475511/197359909-4d563154-b737-4d00-87d1-ba1a961aae2e.PNG)

<br><br>

## Latihan 1
* buat file latihan1.py
* tulis kode seperti contoh <br>
![code latihan1](https://user-images.githubusercontent.com/115475511/197359922-3dbf816a-0a5a-4958-b48e-62abd6a69e7d.PNG)

```python
#cetak tulisan 'Hello' di layar
print("Hello")
#cetak tulisan 'Saya sedang belajar python' di layar
print("Saya sedang belajar python")
```
* lakukan run file
* maka akan muncul program yang dijalankan <br>
![run latihan1](https://user-images.githubusercontent.com/115475511/197359966-08e16d58-ad2a-4fac-90a5-598a4258ef3e.PNG)
<br>
```
Hello
Saya sedang belajar python
```
<br>
## Latihan 2
* buat file latihan2.py
* tulis kode seperti contoh <br>

![code latihan2](https://user-images.githubusercontent.com/115475511/197359987-a4965e2f-9a14-4547-9974-2206d543190c.PNG)

``` python
# menjumlahkan dua bilangan menggunakan variabel a & b
a = 8
b = 6

print("Variabel a =",a)
print("Variabel b =",b)
print("hasil penjumlahan a + b =", a+b)
```
* lakukan running file
* maka akan muncul program yang dijalankan <br>
![run latihan2](https://user-images.githubusercontent.com/115475511/197360248-64841aa7-fc91-42c0-a08c-d8cec0da297a.PNG)


```
Variabel a = 8
Variabel b = 6
hasil penjumlahan a + b = 14
```


## Latihan 3
* buat file latihan3.py
* tulis kode seperti contoh
![code latihan3](https://user-images.githubusercontent.com/115475511/197359999-4fe3c58d-e192-4964-85ef-65e63f9955b8.PNG)

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
![run latihan3](https://user-images.githubusercontent.com/115475511/197360015-c7d57094-02fa-4b24-85b1-c09248b24688.PNG)


```
masukan nilai pertama: 6
masukan nilai kedua: 8
variabel a =  6
variabel b =  8
Hasil Penggabungan 8 & 6 = 68
Hasil penjumlahan 8 + 6 = 14
Hasil pembagian 8 / 6 = 0
```
