
#  CultureApp

CultureApp, kullanıcıların kültürel etkinlikleri, içerikleri ve programları kolaylıkla keşfetmesini, saklamasını ve takip etmesini sağlayan bir mobil uygulamadır. Modern tasarımı, kullanıcı dostu arayüzü ve güçlü özellikleri ile kullanıcıların kültürel dünyaya daha aktif katılımını amaçlamaktadır.

---

##  Projenin Amacı

Bu projenin temel amacı, kullanıcıların kültürel içeriklere (kitap, film, dizi, sergi vb.) dair favori listeleri oluşturabilmesi, içerikleri filtreleyebilmesi ve tercihlerine göre kültürel yönelimlerini yönetebilmesini sağlayan bir platform sunmaktır.

---

##  Teknik Detaylar

- **Flutter:** Uygulamanın temel geliştirme platformu.
- **Firebase Authentication:** Giriş, kayıt ve kullanıcı kimlik doğrulama işlemleri için kullanıldı.
- **Supabase:** (Yahya Çınar tarafından) bazı backend servisleri için denendi/test edildi.
- **SQLite:** (Muhammed İhsan Çakır tarafından) veritabanı işlemleri için alternatif çözümler sunuldu.
- **Firestore (Firebase):** Kullanıcıya ait içeriklerin saklanması için tercih edilen veritabanı.
- **Provider:** Durum yönetimi için kullanıldı.
- **HTTP:** API istekleri için kullanıldı.

---

##  Öne Çıkan Özellikler

- **Google ve GitHub ile Giriş:** Firebase Authentication ile sosyal hesapla kolay giriş.
- **Kültürel İçerik Yönetimi:** Dizi, film, kitap, müzik vb. içeriklerin eklenmesi, düzenlenmesi ve favorilenmesi.
- **Tema Seçimi:** Karanlık ve açık mod arasında geçiş yapabilme.
- **Responsive UI:** Tüm cihaz boyutlarına uyumlu modern tasarım.
- **Arama ve Filtreleme:** İçerikler arasında arama ve kategoriye göre filtreleme.
- **Firestore ile Canlı Veri:** Veriler gerçek zamanlı olarak güncellenir.

---

##  Kullanılan Teknolojiler

- Flutter
- Firebase Authentication & Firestore
- Supabase (backend testi için)
- SQLite (lokal veritabanı araştırması)
- Provider (State Management)
- HTTP (API istekleri)

---

##  Sayfaların Görevleri ve İçerikleri

### 1. Giriş Ekranı (`login_screen.dart`)
- Google, GitHub veya e-posta ile giriş yapılabilir.
- Başarılı giriş sonrası ana sayfaya yönlendirme.
- Modern UI ve hata yönetimi.

### 2. Kayıt Ol Ekranı (`register_screen.dart`)
- E-posta ve şifre ile yeni kullanıcı oluşturma.
- Şifre eşleşme kontrolü.
- Kayıt sonrası kullanıcı bilgileri Firestore’a yazılır.

### 3. Ana Sayfa (`home_screen.dart`)
- Kullanıcıyı karşılayan mesaj ve öne çıkan kültürel içerikler.
- Gradient ve kart tabanlı modern tasarım.
- Navigasyon drawer ile diğer sayfalara geçiş.

### 4. İçerik Listesi Ekranı (`content_list_screen.dart`)
- Tüm eklenen içeriklerin listelenmesi.
- İçerik detayına geçiş, favori butonları.

### 5. Yeni İçerik Ekleme Ekranı (`add_content_screen.dart`)
- Başlık, tür, açıklama ve medya türü girilerek içerik eklenmesi.
- İçeriği Firestore’a kaydetme.

### 6. Favoriler Ekranı (`favorites_screen.dart`)
- Kullanıcının favorilere eklediği içerikleri gösterir.
- Favoriden çıkarma özelliği.

### 7. Ayarlar Ekranı (`settings_screen.dart`)
- Tema değiştirme (karanlık/açık mod).
- Hesap bilgileri ve çıkış yapma.

---

##  Proje Ekibi ve Katkılar

- **Abdullah Karaynir:**  
  🔹 Proje yöneticisi ve tam zamanlı geliştirici.  
  🔹 Firebase entegrasyonu, tüm sayfaların geliştirilmesi, UI/UX, Authentication, veri yönetimi gibi tüm temel yapıdan sorumludur.

- **Yahya Çınar:**  
  🔹 Supabase tarafında backend veri yapıları testleri ve alternatif çözüm araştırmaları yapmıştır.

- **Muhammed İhsan Çakır:**  
  🔹 SQLite üzerinden lokal veri saklama ve yapı testlerinden sorumludur.

---

##  Ek Özellikler

- **Drawer Menü & Uzak Logo API kullanımı**
- **Login sonrası kullanıcıya özel yönlendirme**
- **Firebase üzerinden kullanıcı verilerinin saklanması**
- **Firestore’da içerik listesi örnekleri**
- **Tema yönetimi (Provider)**
- **Kodun modüler ve sürdürülebilir yapıda olması**

---

##  Geliştirme Ortamı

- Android Studio
- Dart 3.0.0 ve Flutter 3.19.0+
- Firebase Console
- GitHub (özel repo)
- Adobe XD (taslak UI)

---

##  İletişim

Proje hakkında öneri, görüş veya katkı sunmak isterseniz benimle GitHub üzerinden iletişime geçebilirsiniz.

> Hazırlayan: **Abdullah Karaynir**
