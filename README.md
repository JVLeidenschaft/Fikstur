# Futbol Fikstur Programi

Bu program aşağıdaki şartlara göre yapılmıştır;
+ Kullanıcıya sunulan bir form üzerinden ligde bulunacak takım sayısı ve girilen sayıya göre takımların isimleri sisteme girilmelidir.
+ Takım isimleri tamamlandıktan sonra fikstür oluştur formu ile takımların yapacakları müsabakalara yönelik maç programı oluşturulacaktır.
+ Müsabakalar için oluşturulacak fikstür takım sayısı ile ilişkilidir. Ligde 10 takım olduğu varsayıldığında bir takımın diğer 9 takımla maç yapması gerekmektedir. Bu maçlar Ev sahibi Deplasman usulüne göre planlanacaktır. Toplamda 1 takımın yapacağı 9 maç biri kendi sahasında diğeri rakip takımın sahasında olmak üzere 18 maça çıkacaktır.
+ Fikstür oluşturulurken lig iki bölüm olarak düşünülmelidir. İlk yarıda 1 takım 9 takımla maç yapacak 2. Yarıda aynı program Ev sahibi Deplasman olarak değiştirilecektir.
+ Fikstür oluşturulurulması bir buton yardımı ile otomatik olarak gerçekleştirilmelidir. Butona her basıldığında rasgele oluşturulacak fikstür bir önceki program ile aynı olmamalıdır.
+ Rasgele fikstür oluşturulurken 3 ve 4. Maddelerde bahsedilen kurallar kontrol yapıları ile mutlaka denetlenmeldir.
+ Sonuç girme ekranında hafta hafta maç skorları sisteme girilebilmelidir. Bu ekrandan bütün haftaların sonuçları girildikten sonra puan tablosuna işlenmelidir.(Sonuçlar rasgele oluşturulabilir.Maç skorları)
+ Puan tablosunda bir takımın galibiyet, beraberlik, malubiyet, attığı gol, yediği gol, averaj (Attığı gol – yediği gol), puan bilgileri bulunacaktır.
+ Puan hesap edilirken Galibiyet 3 Puan Beraberlik 1 Puan Malubiyet 0 Puan olarak işlenecektir.
+ Kullanıcı herhabi bir hafta sonucu girdikten sonra puan tablosunu güncel olarak görebilecektir.
+ Sisteme takım isimlerinin girişi tamamlanmadan fikstür oluşturma ve sonuç girme formları kullanıcıya gösterilmeyecektir.


## Kurulum

Projeyi klonlayın ve gerekli bağımlılıkları yükleyin:

```bash
git clone https://github.com/JVLeidenschaft/FutbolFiksturProgrami.git
cd FutbolFiksturProgrami
npm install
