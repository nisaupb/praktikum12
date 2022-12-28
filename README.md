# praktikum12
String

String Python adalah kumpulan karakter yang dikelilingi oleh tanda kutip tunggal, tanda kutip ganda, atau tanda kutip tiga. Komputer tidak memahami karakter; secara internal, ini menyimpan karakter yang dimanipulasi sebagai kombinasi dari 0 dan 1.

Setiap karakter dikodekan dalam karakter ASCII atau Unicode. Jadi kita dapat mengatakan bahwa string Python juga disebut kumpulan karakter Unicode.
Python String Format

Penjelasaan lengkapnya bisa dilihat disini
Latihan 1

txt = 'Hello World'
print(f"Teks = {txt}")
Menghitung jumlah karakter
print("Jumlah Karakter = ",len(txt))
Mengambil karakter terakhir
a = txt[-1]
print('Karakter Terakhir = ',a)
Mengambil karakter ke-2 sampai ke-4
b = txt[2:5]
print(f"Karakter ke-2 sampai ke-4 = {b}")
# Hilangkan spasi pada text 
c = txt.replace(" ","")
print("Spasi di hilangkan = ",c)
# Ubah teks menjadi huruf besar
d = txt.upper()
print(f"Teks menjadi huruf besar = {d}")
# Ubah teks menjadi huruf kecil
e = txt.lower()
print(f"Teks menjadi huruf kecil = {e}")
# Ganti karakter H dengan karakter J
f = txt.replace("H","J")
print(f"Menganti karakter H dengan J = {f}")

Latihan 2

txt = 'Hello, nama saya john, dan umur saya adalah {0} tahun'
print(txt.format(umur))

outout latihan 1 dan 2
![Screenshot (84)](https://user-images.githubusercontent.com/116271847/209821156-e2275319-a886-4690-8105-1267fc1d5d17.png)
![Screenshot (85)](https://user-images.githubusercontent.com/116271847/209821225-af55162a-9a9a-4f45-bba4-b8cae82bd860.png)
