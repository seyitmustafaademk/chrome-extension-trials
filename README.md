# CHROME EXTENSIONS
Google Chrome için basit eklenti çalışmaları;

## Hello World
  Eklentiye tıklandığında açılan popup sayfasındaki inputa girilen yazıyı, yine popup sayfasında bulunan başlık bölümünde "Hello, " şeklinde gösteriyor.
  
## Budget Manager
  Bu eklenti çok çok basit düzeyde cüzdan eklentisidir. Eklentiye tıklandığında, açılan popup sayfasında 'Limit' ve 'Para' gösteriliyor. Popup sayfasından para eklenebiliyor. Eklentinin ayarlar sayfasından, 'Limit' belirlenebiliyor ve sıfırlanabiliyor. Chrome içerisindeki ehrhangi bir sayfada, ekrandaki bir bölüm yazı seçilip sağ tıklanırsa 'Para Ekle' bölümü tıklanabilir oluyor. Eğer ki seçilen yazı sadece sayısal değer içeriyorsa 'Para Ekle' tıklandığında, eklentiye para ekliyor ve Windows Bildirim alanında gözüken bildirim gösteriyor. Para ekleme, Para >= Limit olduğunda veya Limit sıfırlandığında aynı şekilde bildirim gösteriyor.
  * Kullanılan Özellikler:
    - Depolama
    - Bildirimler
    - Ayarlar Sayfası
    - Chrome Sağ Tık Menüsü

## Page Font Style
  Eklentinin kod yapısında belirtilen css/class'ına, eklentinin popup sayfasından color değeri ataması yapılabiliyor. Bu eklenti kullanıldığı sayfaya css ve javascript injection yapıyor.
  
## Speak
  Chrome'da açık olan herhangi bir sayfada, herhangi bir yazı seçilip sağ tık menüsünden 'Speak' seçilirse yazı sesli okunur.
  * Kullanılan Özellikler:
    - Chrome TTS
    - Chrome Sağ Tık Menüsü
## Wikit
  Chrome'da açık olan sayfada herhangi bir metin seçilip sağ tıklanırsa, açılan menüden 'Wikit' tıklandığında yeni sayfa açılarak Wikipedia araması yapar.
  * Kullanılan Özellikler:
    - Chrome Sağ Tık Menüsü
