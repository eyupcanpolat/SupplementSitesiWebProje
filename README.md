# 🏋️ BestSupplements - Spor Gıdaları E-Ticaret Sitesi

BestSupplements, protein tozları, vitaminler, amino asitler ve sporcu aksesuarları gibi spor gıdaları ve takviye ürünlerinin satışını gerçekleştiren modern ve kullanıcı dostu bir e-ticaret platformudur.

## ✨ Özellikler

### Kullanıcı Özellikleri
- 🛍️ Modern ve responsive tasarım
- 🔍 Gelişmiş ürün arama ve filtreleme sistemi
- 🛒 Dinamik sepet yönetimi
- ❤️ İstek listesi özelliği
- ⚖️ Ürün karşılaştırma
- 🔐 Kullanıcı giriş sistemi
- 💳 Çoklu ödeme yöntemi (Havale/EFT, Kredi Kartı)
- 📦 Sipariş takip sistemi
- ⭐ Ürün değerlendirme ve yıldızlama
- 📧 Newsletter abonelik sistemi
- 🗺️ Google Maps entegrasyonu

### Admin Panel Özellikleri
- 📊 Detaylı dashboard ve istatistikler
- 📈 Satış trendleri ve gelir analizi grafikleri
- 🎯 Sipariş yönetimi ve durum takibi
- 👥 Müşteri yönetimi
- 📦 Ürün yönetimi (CRUD işlemleri)
- 💰 Gerçek zamanlı gelir ve satış takibi

## 🛠️ Teknolojiler

### Frontend
- **HTML5** - Semantik yapı
- **CSS3** - Modern stil ve animasyonlar
- **JavaScript (ES5+)** - Dinamik işlevsellik

### Framework ve Kütüphaneler
- **Bootstrap 4** - Responsive grid sistemi ve UI bileşenleri
- **jQuery 3.x** - DOM manipülasyonu
- **Slick.js** - Carousel/slider animasyonları
- **noUiSlider** - Fiyat aralığı filtreleme
- **jQuery Zoom** - Ürün görsel yakınlaştırma
- **Font Awesome** - İkon kütüphanesi
- **Google Fonts (Montserrat)** - Tipografi

### Tasarım
- **Renk Paleti:**
  - Birincil: `#D10024` (Kırmızı)
  - Koyu: `#15161D` (Header)
  - Açık: `#FFFFFF` (İçerik)
  - Gri tonları: `#E4E7ED`, `#2B2D42`

## 📥 Kurulum


### Kullanıcı Arayüzü

1. **Ana Sayfa (`index.html`):**
   - Öne çıkan ürünleri görüntüleyin
   - Kategorilere göz atın
   - Newsletter'a abone olun

2. **Mağaza (`store.html`):**
   - Ürünleri kategori ve fiyat aralığına göre filtreleyin
   - Grid veya liste görünümü seçin
   - Ürünleri sepete ekleyin

3. **Ödeme (`checkout.html`):**
   - Fatura ve kargo bilgilerinizi girin
   - Ödeme yöntemini seçin
   - Siparişi tamamlayın

4. **Giriş (`login.html`):**
   - Kullanıcı girişi yapın
   - Admin paneline erişim sağlayın

### Admin Paneli (`admin.html`)

**Giriş Bilgileri (Demo):**
- E-posta: `admin@bestsupplements.com`
- Şifre: `admin123`

**Dashboard:**
- Toplam gelir, sipariş sayısı ve müşteri istatistiklerini görüntüleyin
- Haftalık satış trendi grafiğini inceleyin
- Aylık gelir analizini takip edin

**Sipariş Yönetimi:**
- Tüm siparişleri listeleyin
- Sipariş durumunu güncelleyin (Beklemede, İşleniyor, Kargoda, Teslim Edildi)
- Sipariş detaylarını görüntüleyin

## 📁 Proje Yapısı

\`\`\`
bestsupplements/
│
├── index.html              # Ana sayfa
├── store.html              # Mağaza/Ürünler sayfası
├── checkout.html           # Ödeme sayfası
├── login.html              # Giriş sayfası
├── admin.html              # Admin paneli
├── README.md               # Proje dokümantasyonu
│
├── css/                    # Stil dosyaları
│   ├── bootstrap.min.css   # Bootstrap framework
│   ├── style.css           # Ana stil dosyası
│   ├── font-awesome.min.css # İkon kütüphanesi
│   ├── slick.css           # Slider stilleri
│   └── nouislider.min.css  # Slider bileşeni
│
├── js/                     # JavaScript dosyaları
│   ├── jquery.min.js       # jQuery kütüphanesi
│   ├── bootstrap.min.js    # Bootstrap JS
│   ├── slick.min.js        # Slider plugin
│   ├── nouislider.min.js   # Range slider
│   └── main.js             # Ana JavaScript dosyası
│
├── img/                    # Ürün görselleri
│   ├── bcaa1.png
│   ├── d vitamini1.png
│   ├── kreatin1.png
│   ├── logo.png
│   └── ...
│
└── fonts/                  # Font dosyaları
    ├── fontawesome-webfont.ttf
    ├── fontawesome-webfont.woff
    ├── fontawesome-webfont.woff2
    └── ...
\`\`\`

## 📄 Sayfalar

### 1. Ana Sayfa (`index.html`)
- Hero slider bölümü
- Öne çıkan ürünler
- Yeni ürünler carousel
- En çok satanlar
- Newsletter formu
- İletişim bilgileri ve harita

### 2. Mağaza (`store.html`)
- Yan panel filtreleme sistemi
- Kategori filtreleri
- Fiyat aralığı slider'ı
- Grid/Liste görünüm değiştirme
- Ürün kartları (sepete ekle, hızlı görüntüle, istek listesi)

### 3. Ödeme (`checkout.html`)
- Fatura adresi formu
- Kargo adresi formu
- Sipariş özeti
- Ödeme yöntemi seçimi
- Şartlar ve koşullar

### 4. Giriş (`login.html`)
- Kullanıcı giriş formu
- Şifremi unuttum bağlantısı
- Admin paneli erişimi

### 5. Admin Paneli (`admin.html`)
- Dashboard istatistikleri
- Satış ve gelir grafikleri
- Sipariş yönetim tablosu
- Yan menü navigasyonu

## 🎛️ Admin Paneli

### Dashboard Metrikleri
- **Toplam Gelir:** ₺485,739 (%12.5 ↑)
- **Toplam Sipariş:** 1,248 (%8.3 ↑)
- **Aktif Siparişler:** 87 (%3.2 ↓)
- **Yeni Müşteriler:** 156 (%15.7 ↑)

### Grafikler
- **Haftalık Satış Trendi:** Line chart ile günlük satış takibi
- **Aylık Gelir Analizi:** Bar chart ile 12 aylık gelir karşılaştırması

### Navigasyon
- Dashboard
- Siparişler
- Ürünler
- Müşteriler
- Analizler

- Ayarlar

![IMG-20251207-WA0009](https://github.com/user-attachments/assets/ea07f633-036a-4ac8-8735-808c3a4f8985)

![IMG-20251207-WA0008](https://github.com/user-attachments/assets/963c23e3-682f-44a2-a645-77bb3a7b4633)


![WhatsApp Görsel 2025-12-07 saat 21 05 30_5630cd39](https://github.com/user-attachments/assets/9e224e56-e8b1-46b8-abce-0f8acdbe801d)
