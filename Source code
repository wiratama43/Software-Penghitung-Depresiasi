def MetodeGarisLurus():
    print ("Metode Garis Lurus")
    Hargaperolehan = int(input("Masukkan Harga Perolehan: Rp "))
    Residu = int(input("Masukan nilai residu: Rp "))
    UmurEkonomis = int(input("Masukan umur ekonomis (Tahun): "))
    print("Depresiasi = " + str((Hargaperolehan - Residu)/ UmurEkonomis))

def MetodeSaldoMenurunGanda():
    print ("Metode Saldo Menurun Ganda")
    Hargaperolehan = int(input("Masukan harga perolehan : Rp "))
    UmurEkonomis = int(input("Masukan umur ekonomis (Tahun): "))
    print("Depresiasi = " + str((Hargaperolehan / UmurEkonomis)*2))
    
print("="*40)
print("     Aplikasi Penghitung Depresiasi")

def menu():
    print("="*40)
    print("Daftar Metode : ")
    print("1. Metode Garis Lurus")
    print("2. Metode Saldo Menurun Ganda")

    menu = int(input("Pilih Metode: "))
    if menu == 1:
        MetodeGarisLurus()
    elif menu == 2:
        MetodeSaldoMenurunGanda()
    
while True:
    menu()
    ulang = input(" \nApakah Anda Ingin Mencoba Lagi? [ya/tidak]")
    if ulang == "ya" or ulang == "YA":
        menu()
    else :
            break
