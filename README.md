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
