# Ganjil-genap
Project Sederhana

print('\nMasukkan sebanyak 5 angka untuk membuktikan mana angka yang ganjil dan mana angka yang genap ')
count = 4
while (count >= 0):
    angka = (input('masukkan bilangan = '))     
    if int(angka) % 2 == 1:
        print ('bilangan {} adalah bilangan ganjil'.format(angka))
    else:
        print('bilangan {} adalah bilangan genap'.format(angka))
    count = count - 1

print("\nTerima kasih telah mencoba")
print(input("tekan enter untuk mengakhiri "))
