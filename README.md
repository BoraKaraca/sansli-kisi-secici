# Şanslı Kişi Seçici

Toplantı veya oturumlarda **konu başlığına** göre kimin ilk söz alacağını belirlemek için tek sayfalık bir çark uygulaması.

**Canlı demo:** [borakaraca.github.io/sansli-kisi-secici](https://borakaraca.github.io/sansli-kisi-secici/)

## Ne yapar?

- Kişi listesini girersin (alfabetik sıralanır)
- Konu / gündem başlığını yazarsın
- Çark döner; seçilen kişi **aynı oturumda tekrar çıkmaz**
- Herkes sırayla söz alır; son kişi için espirili özel akış vardır

## Teknik

- Tek dosya: `index.html` (HTML + CSS + JS)
- [GitHub Pages](https://pages.github.com/) ile yayınlanır
- Harici bağımlılık: [canvas-confetti](https://github.com/catdad/canvas-confetti) (CDN)

## Kullanım

1. Repoyu klonla veya `index.html` dosyasını indir
2. GitHub Pages’te `main` branch, kök dizin (`/`) olarak aç
3. İsimleri textarea’dan güncelle, **Listeyi Güncelle** ile kaydet

Sıfırlamak için **Seçimi Sıfırla** — liste kalır, sadece seçimler temizlenir.
