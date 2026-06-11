# Project-UAS-Algoritma-Pemrograman
#Program 1
#Kode Python
teks = input("Masukkan teks: ")

jumlah_kalimat = teks.count(".")
kata = teks.split()
jumlah_kata = len(kata)

print("Teks tersebut memuat",
      jumlah_kalimat,
      "kalimat dan",
      jumlah_kata,
      "kata.")
