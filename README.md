# Tugas_PBO-
Menghitung Luas Persegi
+print("=" * 50)
+print("=" + "Kalkulator Luas".center(48) + "=")
+print("=" * 50)

+while True:
+  print("Menu : " + "\n 1. Persegi" + ""
+ "\n 2. Persegi Panjang" + "\n 3. Lingkaran" + "\n 4. Segitiga" + "\n 5. Keluar")
+ pilihan = input( "Masukkan Pilihan Anda : ")
+ if pilihan == '1':
+     while True:
+         Sisi = float(input("Masukkan Pajang Sisi :"))
+         Luas_Persegi = Sisi * Sisi
+         print("Luas Persegi : ")
+         print(Luas_Persegi)
          konfirmasi = input("Masih ingin menghitung luas persegi? (y/n) :")
+         if konfirmasi == "y":
               print("")
+              break
+   elif pilihan == '2':
+       while True:
+           panjang = float(input("Masukkan Lebar Persegi : "))
+           Lebar = float(input("Masukkan Lebar Persegi :"))
+           Luas_Persegi_Panjang = Panjang * Lebar
+
+                     konfirmasi = input("Masih ingin menghitung luas persegi panjang? (y/n :"))
+                     if konfirmasi == "y":
+                          print("")
+                     else:
+                         break
+   elif pilihan == '3':
+       while True:
+           jari = float(input("Masukkan jari-jari lingkaran : "))
+                                           Luas_Lingkaran = 3.14*jari*jari
+           print("Luas Lingkaran : ")
+           print(Luas_Lingkaran)
+           konfirmasi = input("Masih ingin menghitung luas lingkaran? (y/n) :")
+           if konfirmasi == "y":
+               print("")
+           else:
+               break
+   elif pilihan == '4':
+       while True:
+           Alas = float(input("Masukkan Tinggi Segitiga : "))
+           Luas_Segitiga = 1/2*(Alas*Tinggi)
+           print("Luas Segitiga : ")
+           print(Luas_Segitiga)
+           konfirmasi = input("Masih ingin menghitung luas segitiga? (y/n) :")
+           if konfirmasi == "y":
+               print("")
+           else:
+               break
+   elif pilihan == '5':
+      break
+   else:
+       print("Perintah Tidak Ditemukan")
+       konfirmasi = input("Tekan tombol apapun untuk lanjut.")
+
+
+

print("Luas Persegi Panjang : ") 
