# VIT-Database-2


## ODEV 1: Sql Joins
Repo'da bulunan `onlinemarket.sqlite` database dosyasini bilgisayariniza indirin. `DB Browser for Sqlite` programinda `Open Database` secenegi ile `world.sqlite` veritabanini acin ve asagidaki sorulara cevaplar verecek SQL querylerini (sorgularini) yazin. Bir `cevaplar.txt` dosyasi olusturup her soru icin kullandiginiz SQL sorgunuzu ekleyin ve ardindan bu text dosyasini repoya yukleyin.
1. Siparisleri, siparis veren musterilerin bilgileri ile almak icin bir SQL sorgusu yazin.
2. Sipariş edilen ürünlerin isimlerini ve ilgili kategorilerini almak icin bir SQL sorgusu yazin.
3. Müşterilerin müşteri bilgilerini ve varsa sipariş detaylarını almak icin bir SQL sorgusu yazin.
4. Ürünlerin isimlerini, fiyatlarını ve varsa ilgili kategori adlarını almak icin bir SQL sorgusu yazin.
5. Aynı soyadını paylaşan müşterileri ve bu musterilere ait sipariş detaylarını almak için bir SQL sorgusu yazın.



## ODEV 2: Sql Joins 2
Repo'da bulunan `world.sqlite` database dosyasini bilgisayariniza indirin. `DB Browser for Sqlite` programinda `Open Database` secenegi ile `world.sqlite` veritabanini acin ve asagidaki sorulara cevaplar verecek SQL querylerini (sorgularini) yazin. Bir `cevaplar2.txt` dosyasi olusturup her soru icin kullandiginiz SQL sorgunuzu ekleyin ve ardindan bu text dosyasini repoya yukleyin.

1. "city" ve "country" tablolarını düşünün. Nüfusu 1 milyondan fazla olan her şehrin adını, ilgili ülke adını ve nüfusunu almak için bir SQL sorgusu yazın.

2. "city," "country" ve "countrylanguage" tablolarını kullanarak her ülkenin toplam nüfusunu ve resmi dil olarak İngilizce konuşan nüfusun yüzdesini almak için bir SQL sorgusu yazın. Sonuçları nüfusa göre azalan şekilde sıralayın.

3. "city" ve "country" tablolarını düşünün. Her şehrin adını, ilgili ülke adını, kıtasını ve yönetim şeklini almak için bir SQL sorgusu yazın. Yalnızca "Anayasal Monarşi" (Constitutional Monarchy) yönetim şekline sahip olan şehirleri dahil edin.

4. "city," "country" ve "countrylanguage" tablolarını kullanarak her şehrin adını, ilgili ülke adını ve resmi dil dışında konuşan nüfusun yüzdesini almak için bir SQL sorgusu yazın. Yalnızca yüzdesi %10'dan büyük olan şehirleri dahil edin.

5. "city" ve "country" tablolarını düşünün. Her şehrin adını, ilgili ülke adını, bölgesini ve devlet başkanını almak için bir SQL sorgusu yazın. Yalnızca nüfusu 100 milyondan fazla olan bölgelerde bulunan şehirleri dahil edin.



## ODEV 3: Python Sqlite
Bir Python programi olusturun ve sqlite3 modulu ile `world.sqlite` database'ine baglanin. Ardindan asagida yer alan sorulari yanitlayacak kodlari programiniza ekleyin.

1. X ülkesinin başkenti neresidir? (X kullanıcı inputu olacaktır)

2. X şehri hangi ulkede yer almaktadir? (X kullanıcı inputu olacaktır)

3. X bölgesinde konuşulan tüm dilleri listeleyin. (X kullanıcı inputu olacaktır)

4. X dilinin konuşulduğu şehirlerin sayısını bulunuz. (X kullanıcı inputu olacaktır)

5. Kullanıcıdan bir A bölgesi(region) ve bir B dili(language) alın. Eğer bu B dili, A bölgesindeki ülkelerin birinde resmi dil ise, o ülke(ler)in isim(ler)ini listeleyin. Eğer o bölgedeki hiçbir ülkede resmi dil değilse, "B dili A bölgesindeki hiçbir ülkede resmi dil değildir." şeklinde bir çıktı verin. (A ve B kullanıcı inputu olacaktır.)

6. Tüm kıtaları, o kıtalarda konuşulan dillerin sayısı ile birlikte bulunuz. (Bazı dillerin bir kıtada birden fazla ülkede konuşulduğunu unutmayın ve bunu dikkate alarak bir dili birden fazla kez hesaplamayın.)
