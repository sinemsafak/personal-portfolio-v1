
# Personal Portfolio V1

HTML5 ve CSS3 ile geliştirilmiş, mobil öncelikli, responsive ve iki dilli
kişisel portfolyo web sitesi.

## Özellikler

- Tek sayfalı statik web sitesi
- Türkçe ve İngilizce içerik
- CSS Grid ve Flexbox tabanlı düzen
- Mobil, tablet ve masaüstü ekranlara uyum
- Anlamsal HTML5
- Klavye navigasyonu ve görünür odak stilleri
- Harici JavaScript veya CSS kütüphanesi gerektirmez
- Backend veya veritabanı gerektirmez

## Dosya yapısı

```text
personal-portfolio-v1/
├── index.html
├── README.md
├── .gitignore
└── css/
    └── styles.css
```

## Gereksinimler

- Visual Studio Code
- Güncel bir web tarayıcısı
- İsteğe bağlı: VS Code Live Server eklentisi
- İsteğe bağlı: Git ve GitHub hesabı

## Yerel ortamda çalıştırma

1. Proje klasörünü VS Code ile açın.
2. `index.html` dosyasını bulun.
3. Dosyayı doğrudan tarayıcıda açın veya Live Server eklentisini kullanın.
4. Türkçe ve İngilizce içeriklere üstteki dil bağlantılarıyla gidin.

## Kişiselleştirme

### Kişisel bilgiler

`index.html` dosyasında aşağıdaki örnek değerleri değiştirin:

- `Adınız Soyadınız`
- `Your Name`
- `ornek@example.com`
- GitHub ve LinkedIn profil bağlantıları
- Hakkımda metinleri ve proje açıklamaları

HTML'deki `lang` değerlerini içerik diline uygun tutun.

### Projeler

Her proje `article.project-card` bileşeni içinde tanımlanır.
Başlıkları, açıklamaları, teknoloji etiketlerini ve örnek durum metnini
kendi çalışmalarınıza göre güncelleyin.

Gerçek proje bağlantısı ekleyecekseniz bağlantı metnini açıklayıcı tutun.

### Tasarım

Renkler ve ortak ölçüler `css/styles.css` dosyasının başındaki
`:root` bölümünde tanımlanmıştır.

Responsive düzenler şu kırılımları kullanır:

- Temel stiller: mobil
- 600 px ve üzeri: tablet ve geniş ekran düzeni
- 900 px ve üzeri: masaüstü proje kartları
- 360 px ve altı: dar ekran düzeltmeleri

## Dil kullanımı

Bu sürümde her iki dil de aynı HTML belgesinde bulunur.
Dil bağlantıları ilgili bölümün başlangıcına gider; içeriği gizlemez.

Yalnızca CSS ve HTML kullanıldığı için JavaScript tabanlı otomatik
dil değiştirme veya dil durumunu saklama özelliği yoktur.

## İletişim

E-posta bağlantısı `mailto:` kullanır. GitHub ve LinkedIn bağlantıları
örnek adreslerdir ve kişisel profil adreslerinizle değiştirilmelidir.

Bu proje bir backend veya mesaj gönderme formu içermez.

## Doğrulama

HTML:
https://validator.w3.org/

CSS:
https://jigsaw.w3.org/css-validator/

HTML dosyasını HTML doğrulayıcısına yükleyin veya URL üzerinden kontrol edin.
CSS doğrulayıcısında `css/styles.css` dosyasını seçerek doğrulayın.

Test sonuçlarını doğrulayıcı raporlarına göre değerlendirin.

## Sürüm

V1.0.0

## Lisans

Kişisel kullanım için hazırlanmış başlangıç projesi.
