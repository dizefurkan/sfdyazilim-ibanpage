# SFD Yazılım - QR Ödeme & İletişim Sayfaları

Bu depo, **SFD Yazılım** tarafından geliştirilen statik **QR Ödeme & İletişim Sayfaları**nı barındırmaktadır.

Bu sayfalar sayesinde işletmeler, müşterileriyle aşağıdaki bilgileri tek bir QR kod üzerinden paylaşabilir:

- 💳 Şahsi ve kurumsal banka hesap bilgileri
- 📋 Tek dokunuşla IBAN kopyalama
- 📞 Telefon ve iletişim bilgileri
- 📧 E-posta adresi
- 📍 İşletme konumu (Google Maps)
- 📱 Mobil uyumlu tasarım

## Yapı

```text
/
├── index.html                 # Landing Page
├── example/                   # Örnek sayfa (Mock Data)
│   └── index.html
├── customer-name/
│   └── index.html
└── assets/
```

Her müşteri kendi klasörü altında bağımsız bir statik HTML sayfasına sahiptir.

## Teknolojiler

- HTML5
- CSS3
- GitHub Pages

JavaScript framework'ü veya build süreci kullanılmamaktadır.

## Yayın

Bu proje GitHub Pages üzerinden yayınlanmaktadır.

## Yeni Müşteri Ekleme

Yeni bir müşteri eklemek için:

1. Yeni bir klasör oluşturun.
2. `index.html` dosyasını kopyalayın.
3. Müşteri bilgilerini güncelleyin.
4. Değişiklikleri GitHub'a gönderin.

Örnek:

```text
customer-name/
└── index.html
```

Ardından sayfa aşağıdaki adresten erişilebilir olacaktır:

```
https://dizefurkan.github.io/sfdyazilim-ibanpage/customer-name/
```

## İletişim

📧 **E-posta**

sfdyazilim@gmail.com

📷 **Instagram**

https://instagram.com/sfdyazilim

---

© 2026 SFD Yazılım
