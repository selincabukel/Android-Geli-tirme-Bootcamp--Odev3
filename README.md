# QuickBook – Otel Rezervasyon Android Uygulaması

QuickBook, kullanıcıların hızlı ve pratik bir şekilde otel rezervasyonu yapmasını kolaylaştırmak amacıyla geliştirilmiş modern bir Android kullanıcı arayüzüdür. Uygulama, Material Design ilkelerine uygun şekilde tasarlanmış ve çoklu dil desteğiyle donatılmıştır.

---

## 📱 Özellikler

- 🎨 **Tema & Renk Yönetimi**  
  Tüm renkler `colors.xml` dosyasında merkezi olarak tanımlanmıştır (`@color/koyugri`, `@color/anaRenk3turuncu`, vb.).

- 🌐 **Çoklu Dil Desteği (i18n)**  
  Uygulama hem Türkçe hem İngilizce olarak kullanılabilir.  
  - `res/values/strings.xml` – İngilizce metinler  
  - `res/values-tr/strings.xml` – Türkçe metinler
 
  -  🌍 Çoklu Dil Desteği – Örnekler

| Anahtar | Türkçe (`values-tr`) | İngilizce (`values`) |
|--------|-----------------------|----------------------|
| `text1` | Rezervasyon yaptırmak ister misin? | Do you want to book? |
| `signinsignupyazi` | Giriş Yap/Kaydol | Sign in/Sign Up |
| `fiyatlar` | 20$'dan başlayan fiyatlarla | Starting from $20 |
| `readyGoyazi` | Hadi gidelim! | Ready Go! |

- 🔤 **Özel Font Kullanımı**  
  Başlıklar için `Pattaya` yazı tipi kullanılmıştır (`@font/pattaya`).

- 📏 **Responsive Tasarım**  
  Tüm arayüz `ConstraintLayout` ile inşa edilmiştir. Bu sayede farklı ekran boyutlarında tutarlı görünüm sağlanır.

- 🖼️ **Görseller ve Bileşenler**  
  Otel resmi (`@drawable/wphotel`) ve `Material Chip`, `TextView`, `Button`, `Toolbar` gibi bileşenler kullanılmıştır.


  
  ## 👤 Geliştirici Bilgileri

- **İsim:** Selin Cabukel  
- **Teslim Tarihi:** 1 Mayıs 2025  
- **Proje:** Mobil Uygulama Geliştirme – Android UI Ödevi

## 📌 Notlar

- Bu proje yalnızca kullanıcı arayüzüne (UI) odaklanmaktadır. Giriş, kayıt veya veritabanı bağlantısı gibi işlemler henüz eklenmemiştir.
- Eğitim ve sunum amacıyla geliştirilmiştir.
