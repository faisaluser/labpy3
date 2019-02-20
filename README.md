# labpy3
# **latihan1.py**
```python
import random
n=str(input("masukan nilai N: "))
for x in range (1,6):
 print("data ke:",x,"=>",random.uniform(0.0,0.5))
print('selesai')
```
# **penjelasan algoritma**

- [x] masukan nilai N 

- [x] gunakan for range (untuk mengulang data dari 1-5) Perulangan for disebut counted loop (perulangan yang terhitung)

- [x] cetak data dan memasukan (random.uniform kurang dari 0.5) mengacak nilai kurang dari data yang ditentukan

- [x] jika selesai RUN/jalankan programnya.
# **output**
![untitled3](https://user-images.githubusercontent.com/46892500/53070210-f8b6f700-3510-11e9-9a53-38cfa00fcedb.jpg)
# **latihan2.py**
```python
max=0
while True:
	a=int(input("masukan bilangan:"))
	if a ==0:
		break
	if a>max:
		max=a
print("bilangan terbesar:",max)
```
# **penjelasan algoritma**
- [x] masukan nilai max =0

- [x] gunakan while True.perulangan while disebut uncounted loop (perulangan yang tak terhitung)

- [x] gunakan if (jika memasukan bilangan nol maka perulangan  akan berhenti). if dalam Python dijalankan untuk memeriksa apakah kondisi       ini adalah bernilai benar atau salah.

- [x] selanjutnya,gunakan if (untuk mencari nilai max = bilangan terbesar,lalu run/jalankan programnya).

# **output**
![untitled5](https://user-images.githubusercontent.com/46892500/53070288-3ddb2900-3511-11e9-9fb6-cadd530df9a7.jpg)
# **latihan3.py**
```python
a = 100000000

for x in range(1,9):
    if(x>=1 and x<=2):
        b =a*0
        print("Laba Bulan ke-",x," :",b)
    if(x>=3 and x<=4):
        c=a*0.1
        print("Laba Bulan ke-",x," :",c)
    if(x>=5 and x<=7):
        d=a*0.5
        print("Laba Bulan ke-",x," :",d)
    if(x==8):
        e=a*0.2
        print("Laba Bulan ke-",x," :",e)
total = b+b+c+c+d+d+d+e
print("\ntotal : ", total)     
```
# **penjelasan algoritma**
- [x] masukkan nilai a

- [x] gunakan for untuk perulangan dari 1 sampai 8.Perulangan for disebut counted loop (perulangan yang terhitung)

- [x] lalu gunakan if pertama untuk menentukan laba bulan ke 1 dan ke 2.masukan variabel (b) kalikan nilai (a) dengan data bulan 1 dan 2.
cetak (x) dan (b)

- [x] lalu gunakan if kedua untuk menentukan laba bulan ke 3 dan ke 4.masukan variabel (b) kalikan nilai (a) dengan data bulan 3 dan 4.
cetak (x) dan (c)

- [x] lalu gunakan if ketiga untuk menentukan laba bulan ke 5 sampai ke 7.masukan variabel (b) kalikan nilai (a) dengan data bulan 5 sampai 7.
cetak (x) dan (d)

- [x] lalu gunakan if keempat untuk menentukan laba bulan ke 8.masukan variabel (b) kalikan nilai (a) dengan data bulan 8.
cetak (x) dan (e)

- [x] lalu total keseluruhan.

- [x] cetak total

# **output**
![untitled7](https://user-images.githubusercontent.com/46892500/53070397-9c080c00-3511-11e9-85b3-614108ac3f7f.jpg)
