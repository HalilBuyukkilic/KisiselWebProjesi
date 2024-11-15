# KisiselWebProjesi

- Asp.Net Mvc İle Kişisel Web Sitesi Entity Framework Code First Yapısı
  Kullanılarak Yapılmıştır.
- Proje Yapımında Ana Sayfa Ve Admin Login Sayfasında Sadece Html Ve
  Css Kullanılmıştır.
- Admin Teması w3schools Sidebar Bölümünden Alınmış Ve Üzerinde Bir Kaç
  Değişiklik Yapılmıştır.
- Admin Temasında Bootstrap CDN Eklenip Buton Ve Tablolar Bootstrap ile
  yapılmıştır.

# Projeden Görüntüler

**Admin Login Sayfası**
![Screenshot](https://user-images.githubusercontent.com/48470345/93140288-dbe1a600-f6ea-11ea-98a4-95059f0aef77.png)

**Admin Panel Ana Sayfa**
![Screenshot](https://user-images.githubusercontent.com/48470345/93140369-fddb2880-f6ea-11ea-8e81-1fae3399ad50.png)

**Admin Panel İkonlar Sayfası**
![Screenshot](https://user-images.githubusercontent.com/48470345/93140435-1c412400-f6eb-11ea-9d54-ab188097b071.png)

# Veri Tabanı Oluşturma

1.  Veri Tabanın Oluşturmak İçin **Web.Config** Dosya Ayarlarındaki
    `Data Source` Kısmına Kendi Sql Serverınızı Yazmanız Gerekiyor.
2.  Sonrasında Package Manager Console Kısmına `Enabled-Migrations`
    Yazıp Enter Tuşuna Basınız.
3.  Oluşan Configurations Dosyası İçeriğini `AutomaticMigrationsEnabled
= true;` Şeklinde Değiştiriniz.
4.  Sonrasında `update-database` Yazıp Enter Tuşuna Basınız.
5.  Bu İşlemleri Tam Olarak Yaptığınızda Veri Tabanı Oluşup Projeyi
    Başlattığınızda Proje Sorunsuz Çalışır.
