# Week - NULL
```Hafta veya Ödev Sayısı (Ödev-4)```

# Homework 
İş Yönetim Sistemi<br/>
Amaç<br/>
-	Bir işyerindeki iş takiplerinin yapılabilmesi için geliştirilecek uygulamadır
-	Program, küçük veya orta ölçekli işyerlerine hitap edecektir
-	İlgili kişiler tarafından işlerin açılması ve işi alan veya iş atanan kişinin işi çözmesi bek-lenmektedir.<br/>
İsterler<br/>
-	Personel Giriş<br/>
•	Sisteme giriş oturum açılarak yapılmalıdır.
•	E-mail ve parola ile giriş yapılmalıdır.
•	Giriş yapıldıktan sonra sistem geçerliliği 1 gün olacak şekilde bir token üretilmelidir
-	Personel Kayıt<br/>
•	Personel Adı(Zorunlu)
•	Personel Soyadı(Zorunlu)
•	E-Mail(Zorunlu)
•	Cep Tel No
•	Departman(Zorunlu)
•	Yetki(Personel, Yönetici, Admin)(Zorunlu)<br/>
Sadece Yönetici ve Admin yetkisine sahip kullanıcılar personeli kayıt edebilmelidir.
Personel kayıt olduktan sonra ilgili kişiye 6 haneli random bir parola üretilerek ilgili kişinin mailine gönderilmelidir. Veri tabanında parolaya karşılık gelen şifre tutulmalıdır.(istediğiniz şifreleleme algoritmasını seçebilirsiniz. MD5, SHA1, vb…)<br/>
-	Personel Parola Değiştirme<br/>
•	Personel parolasını değiştirebilmelidir.
•	Parola değiştirme esnasında eski parola kontrolü de yapılmadır.<br/>
-	Yeni Talep Oluşturma<br/>
•	Talep başlığı girilmeli
•	Departman seçilmeli(işin gideceği departman)
•	Öncelik durumu seçilmeli(kritik, acil, vb…)
•	Departmana bağlı konu seçilmeli(önceden hazırlanmış listeden çekilmeli)
•	İşe başlama ve bitiş tarihi girilebilmeli(bu tarihler opsiyonel olmalı)
•	İçerik
Bilgileri girilerek talep oluşturma yapılmalıdır.<br/>
-	İş Listeleme<br/>
•	Kişinin çalıştığı departmana göre işlerin listelenmesi sağlanmalı<br/>
-	Talep no
-	Talep başlığı
-	Öncelik Departman
-	İşin açılma tarihi
-	Talep eden kişi bilgileri listelenmelidir
-	İş Atama<br/>
•	Kişi kendi departmanına gönderilen iş listesinden kendine iş seçebilecektir. Kendi üzerine iş alma. Bir iş alındıktan sonra başka kişiye atanması engellenecektir.<br/>
-	İş Üzerinden Yazışma<br/>
•	İşi açan ve alan kişi iş üzerinden yazışma yapabilecek.<br/>
-	İşin Detayının Görüntülenmesi<br/>
•	İş Bilgileri
•	İşi alan kişi bilgileri
•	İş üzerinde yazışmalar görüntülenebilecek<br/>
Pekiştirilecek Kavramlar<br/>
-	N-Katmanlı Mimari tasarımı(sunum, servis, entity, iş katmanı, dal katmanı)
-	OOP(class, nesne, interface, kalıtım, çoklu kalıtım, yapıcı metod, kapsülleme)
-	ORM-Entityframework
-	Mapper yapısı kurma ve kullanma
-	Transaction yönetimi(UnitOfWork pattern)
-	Repository,generic repository pattern
-	Generic metod, generic class, generic interface
-	Depency injeciton
-	JWTToken dağıtma ve kullanma
-	REST Api tasarımı
-	Web Api Setup ayarları
-	UML oluşturma
-	UML’i okuyarak veri tabanı oluşturma
-	Veri tabanı:Tablo, Kolon, Primary Key , Foreign Key, Unique key



## Homework Description

```Ödevi yetiştiremedim yapabildiğim kadarını paylaştım ```


## Author

```Muhammed Görkem Acır```
