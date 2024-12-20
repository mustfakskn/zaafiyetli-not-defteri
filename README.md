# zaafiyetli-not-defteri

Proje Açıklaması

Bu proje, basit bir Not Defteri uygulamasıdır. Kullanıcılar, uygulama aracılığıyla not ekleyebilir, düzenleyebilir ve silebilir. Proje sırasında mobil uygulama güvenliği konusuna odaklanılmış ve farklı güvenlik zaafiyetleri eklenerek sömürü testleri gerçekleştirilmiştir. Firebase altyapısı kullanılarak kullanıcı kimlik doğrulama ve veri saklama işlemleri gerçekleştirilmiştir.

Kullanılan Teknolojiler

Programlama Dili: Java
Mobil Platform: Android (API 26+)
Veritabanı: Firebase Firestore
Kimlik Doğrulama: Firebase Authentication
IDE: Android Studio

Proje Özellikleri

Kullanıcı Giriş ve Kayıt:
Firebase Authentication kullanılarak kullanıcıların giriş yapması ve yeni bir hesap oluşturması sağlanmıştır.
Not İşlemleri:
Not ekleme, düzenleme ve silme işlemleri Firebase Firestore üzerinde gerçekleştirilmiştir.
Güvenlik Testleri:
Mobil uygulama güvenlik zaafiyetleri test edilmiş ve bu zaafiyetler sömürülerek projeye dahil edilmiştir.
Güvenlik Zaafiyetleri
Proje kapsamında şu güvenlik zaafiyetleri test edilip belgelendirilmiştir:

Eksik Kimlik Doğrulama:

Kullanıcı e-posta doğrulaması yapılmadan giriş sağlanabilmiştir.
Firebase güvenlik kuralları zaafiyeti ile herhangi bir kimlik doğrulama olmaksızın verilere erişim sağlanmıştır.
Güvensiz Veri Depolama:

Verilerin şifrelenmeden saklandığı durum analiz edilmiştir.
Firebase veritabanındaki kayıtların hassasiyetine dikkat çekilmiştir.
Yetkilendirme Eksiklikleri:

Bir kullanıcıya ait olan notlara başka bir kullanıcının erişimi sağlanmıştır.
Firebase güvenlik kuralları incelenmiş ve yetkilendirme zaafiyeti simüle edilmiştir.

Nasıl Çalışır?

Giriş/Kayıt: Kullanıcı, e-posta adresi ve şifre bilgisi ile kayıt olabilir ya da mevcut hesabına giriş yapabilir.
Not Ekleme: Kullanıcılar, not başlığı ve içeriği ekleyerek Firebase Firestore üzerinde not oluşturabilir.
Not Düzenleme/Silme: Kullanıcılar, mevcut notlarını düzenleyebilir veya silebilir.
Güvenlik Testleri: Proje içeriğinde yer alan zaafiyetler ile uygulamanın nasıl sömürülebileceği gösterilmiştir.

Android Studio ile açın ve Firebase bağlantı yapılandırmasını gerçekleştirin.
Bir Android cihaz ya da emülatör ile uygulamayı çalıştırın.
Test Araçları
Postman: Firebase veritabanına erişim ve veri manipülasyonu.
JADX: Uygulama kodlarının tersine mühendislik analizi.
Firebase Console: Veritabanı yönetimi ve güvenlik kuralları analizi.
