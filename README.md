# Aura Verde — Environmental Events Web App

Çok sayfalı bir front-end uygulaması: etkinlik listesi, etkinlik detayı, iletişim formu (datepicker), profil (görev/ilerleme), destek sayfası. jQuery/AJAX ile JSON/XML verileri yüklenir; küçük eklentilerle (typed, carousel) zenginleştirilir.

## Özellikler
- jQuery AJAX ile JSON/XML’den veri çekme (`assets/js/external-api.js`)
- jQuery UI (datepicker, progressbar) başlatma (`assets/js/jquery-ui/ui-init.js`)
- Form doğrulama (jQuery Validate, `assets/js/plugins/form-validate.js`)
- Typed yazı ve carousel eklentileri (`assets/js/plugins/typed-init.js`, `assets/js/plugins/carousel.js`)
- LocalStorage ile favoriler/ilerleme (Profile)
- Responsive tasarım ve temel a11y

## Teknolojiler
HTML5, CSS3, JavaScript, jQuery, jQuery UI, jQuery Validate, Typed.js, Slick Carousel, AJAX (JSON/XML)

## Sayfalar
- `index.html`: Ana sayfa, typed yazı, slideshow, yaklaşan etkinlikler (AJAX)
- `events.html`: Etkinlik listesi (AJAX)
- `eventdetail.html`: Görsel alan + abone ol bölümü
- `contact.html`: İletişim formu + jQuery UI datepicker
- `profile.html`: Sekmeler, günlük görevler, ilerleme (LocalStorage)
- `support.html`: STK kartları (flip effect) + basit yorum alanı
- `signup.html`: Giriş/Kayıt formları (jQuery Validate)
