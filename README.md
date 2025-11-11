# 🛍️ Etsy Otomasyon Sistemi

API kullanmadan Etsy ürünlerinizi takip edin ve yönetin.

## 🌟 Özellikler

- **Ürün Takibi**: Etsy ürün linklerini kaydedin, fiyat ve notlar ekleyin
- **Etsy Arama**: Doğrudan Etsy.com'da arama yapın
- **Yerel Depolama**: Tüm verileriniz tarayıcınızda güvenle saklanır
- **İstatistikler**: Toplam ürün sayısı ve toplam değeri görüntüleyin
- **Responsive Tasarım**: Masaüstü ve mobil cihazlarda çalışır
- **Türkçe Arayüz**: Tam Türkçe dil desteği

## 🚀 Kullanım

1. `index.html` dosyasını herhangi bir web tarayıcısında açın
2. **Etsy'de Ara** bölümünü kullanarak Etsy'de ürün arayın
3. **Yeni Ürün Ekle** formunu kullanarak takip etmek istediğiniz ürünleri ekleyin
4. Ürünlerinizi yönetin: görüntüleyin, açın veya silin

## 💡 API'siz Nasıl Çalışır?

Bu araç tamamen **istemci tarafında** çalışır:
- Herhangi bir API anahtarına ihtiyaç duymaz
- Backend sunucusu gerektirmez
- Tüm veriler tarayıcınızın localStorage'ında saklanır
- Etsy'de arama yapmak için Etsy.com'u yeni sekmede açar
- Tamamen ücretsiz ve gizlilik önceliklidir

## 🔒 Güvenlik

- XSS koruması için tüm kullanıcı girdileri HTML-encoded
- Harici linkler güvenli şekilde açılır (`noopener noreferrer`)
- Hassas veri veya API anahtarı gerektirmez
- Veriler yalnızca yerel tarayıcınızda saklanır

## 📝 Özellikler

### Ürün Ekleme
- Ürün adı
- Etsy ürün linki
- Fiyat (₺)
- Notlar (opsiyonel)

### Ürün Yönetimi
- Ürünleri görüntüleme
- Etsy'de ürünü açma
- Ürün silme
- Ekleme tarihini görüntüleme

### İstatistikler
- Toplam ürün sayısı
- Toplam ürün değeri

## 🛠️ Teknik Detaylar

- **HTML5** için modern yapı
- **CSS3** ile gradient tasarım
- **Vanilla JavaScript** - framework yok
- **localStorage API** - veri kalıcılığı
- Bağımlılık yok - tamamen bağımsız

## 📱 Tarayıcı Uyumluluğu

- ✅ Chrome / Edge / Brave
- ✅ Firefox
- ✅ Safari
- ✅ Opera
- ✅ Modern mobil tarayıcılar

## 📄 Lisans

Bu proje açık kaynaklıdır ve serbestçe kullanılabilir.

## 🤝 Katkıda Bulunma

Katkılarınızı bekliyoruz! Pull request göndermekten çekinmeyin.
