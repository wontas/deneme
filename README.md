from colorama import Style, Fore
import datetime
tarih = datetime.datetime.now()

print(Fore.BLUE)
print("--> THT İstihbarat Ekibi Rapor Hazırlayıcı 'asintrema' v1.0")
print("--> Yazar: Aquamarine")
print("--> Not: Eğer cihazınızda 'thtistrapor' isimli bir txt dosyası bulunuyorsa, program hata verecektir.")
print(Style.RESET_ALL)
answ1 = input("\nNickiniz: ")
answ2 = input("\nTHT Profil Linkiniz: ")
answ3 = input("\nRapor Tarih Aralığı: ")
answ4 = input("\nKullanılan Hesap Linki: ")
answ5 = input("\nKullanılan Hesabın İsmi: ")
answ6 = input("\nHedefin Adı Soyadı: ")
answ7 = input("\nHedefin Telefon Numarası: ")
answ8 = input("\nHedefin Lokasyonu: ")
answ9 = input("\nHedefin Sosyal Medya Hesap Linki: ")
answ10 = input("\nHedefin IP Adresi: ")
answ11 = input("\nKullanılan IP Logger Linki: ")
print("\nRaporunuz hazırlanıyor...")
print("\nRaporunuzu asintrema'yı çalıştırdığınız dizinde bulabilirsiniz...")



f = open("thtistrapor.txt", "x")
f.write("*TurkHackTeam İstihbarat Ekibi Rapor*")
f.write("\nRaporun Oluşturulduğu Tarih: "+(tarih.strftime("%Y-%m-%d %H:%M:%S")))
f.write("\nNickiniz: "+answ1)
f.write("\nTHT Profil Linkiniz: "+answ2)
f.write("\nRapor Tarih Aralığı: "+answ3)
f.write("\nKullanılan Hesap Linki: "+answ4)
f.write("\nKullanılan Hesab İsmi: "+answ5)
f.write("\nHedefin Adı Soyadı: "+answ6)
f.write("\nHedefin Telefon Numarası: "+answ7)
f.write("\nHedefin Lokasyonu: "+answ8)
f.write("\nHedefin Sosyal Medya Hesap Linki: "+answ9)
f.write("\nHedefin IP Adresi: "+answ10)
f.write("\nKullanılan IP Logger Linki: "+answ11)



