# Nama : Anindha Latiefa Zahra
# NIM : 312210323
# Kelas : TI.22.A.3

# Latihan 1
#Penggunaan end 

![Screenshot (55)](https://user-images.githubusercontent.com/115516800/198232154-0c5fefe7-57fd-4df3-9ce1-c1e60957e2f9.png)

#Penggunaan separator 

![Screenshot (56)](https://user-images.githubusercontent.com/115516800/198232466-b073c1bb-1373-4a48-b8a0-0e16e4abfadd.png)

#String format 1

![Screenshot (57)](https://user-images.githubusercontent.com/115516800/198232592-a4ef4d23-4d20-4118-9774-db243bec8edc.png)

#string format 2

![Screenshot (58)](https://user-images.githubusercontent.com/115516800/198232696-39ceafc2-da64-4053-b381-b99b38ea38a6.png)

#Hasil Latihan 1

![Screenshot (59)](https://user-images.githubusercontent.com/115516800/198232891-4324f0f9-e5d9-446a-b438-def4ffc0e70c.png)
![Screenshot (60)](https://user-images.githubusercontent.com/115516800/198232956-f424e882-bdb1-4bcf-b3c5-fe833ebbd617.png)

# Latihan 2
#Masukkan variable

![Screenshot (61)](https://user-images.githubusercontent.com/115516800/198233194-b680e1d9-9962-4ad6-8175-2f152c368395.png)

#Konversikan nilai variable

![Screenshot (62)](https://user-images.githubusercontent.com/115516800/198233378-85c1a0f5-82a5-40c6-8da8-4395ac1851ee.png)

#Hasil Latihan 2

![Screenshot (63)](https://user-images.githubusercontent.com/115516800/198233615-2575a657-ef15-47ef-85e1-b120b3ec5eb6.png)
 
 # Latihan 3
 #string kode belah ketupat
 string = ""
print("LATIHAN 3")
print("Rini Ariza")
print("312210337")
x = 5
bar = x
# Looping Baris
while bar >= 0:
	# Looping Kolom Spasi Kosong
	kol = bar
	while kol > 0:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri
	kiri = 1
	while kiri < (x - (bar-1)):
		string = string + " * "
		kiri = kiri + 1
	# Looping Kolom Bintang Sisi Kanan
	kanan = 1
	while kanan < kiri -1:
		string = string + " * "
		kanan = kanan + 1

	string = string + "\n\n"
	bar = bar - 1

bar = 1
# Looping Baris
while bar <= x:
	kol = bar+1
	# Looping Kolom Spasi Kosong
	while kol > 1:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri
	kiri = 0
	while kiri < (x - bar):
		string = string + " * "
		kiri = kiri + 1
	# Looping Kolom Bintang Sisi Kanan
	kanan = kiri
	while kanan > 1:
		string = string + " * "
		kanan = kanan - 1

	string = string + "\n\n"
	bar = bar + 1
print (string)
 
#Hasil belah ketupat 

![Screenshot (54)](https://user-images.githubusercontent.com/115516800/198234305-38ffb779-bca5-4cdf-9709-91569e2b93a3.png)

# Latihan 4
#Flowchart luas dan keliling lingkaran

![Flowchart](https://user-images.githubusercontent.com/115516800/198234562-512d5748-e696-4e2b-a354-3af463cc861b.jpg)

#Menghitung luas lingkaran 

![Screenshot (66)](https://user-images.githubusercontent.com/115516800/198235461-d15523a0-8384-4b6d-81b0-9e5ba9301cdd.png)

#Hasil Latihan 4

![Screenshot (67)](https://user-images.githubusercontent.com/115516800/198236380-f5ae11d5-5168-45e1-8530-1c67e375342f.png)
