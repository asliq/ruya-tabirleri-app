# 🌙 Rüya Tabirleri - Türkçe Rüya Yorumları

Modern ve kapsamlı Türkçe rüya tabirleri uygulaması. AI destekli yorumlar, sesli arama ve detaylı içerik ile rüyalarınızı anlamlandırın.

## ✨ Özellikler

### 📚 Kapsamlı Rüya Sözlüğü
- **100+ Türkçe rüya tabiri**
- **Detaylı yorumlar** her tabir için
- **5 farklı senaryo** ve anlamları
- **Duygusal bağlam** açıklamaları
- **Pratik öneriler** ve tavsiyeler

### 🔍 Gelişmiş Arama Sistemi
- **Hızlı arama** rüya tabirlerinde
- **Detaylı içerikte arama** (semboller, duygular, tavsiyeler)
- **Filtreleme** ve sonuç sıralama
- **Arama geçmişi** ve öneriler

### 🤖 AI Destekli Yorum
- **Kişiselleştirilmiş rüya yorumları**
- **Detaylı analiz** ve açıklamalar
- **Pratik tavsiyeler** ve öneriler
- **Duygusal durum** değerlendirmesi

### 🎤 Sesli Özellikler
- **Sesli arama** mikrofon ile
- **Text-to-Speech (TTS)** tüm içerik için
- **Sesli komutlar** navigasyon için
- **Türkçe dil desteği**

### ⭐ Favori Sistemi
- **Favori tabirleri kaydetme**
- **Hızlı erişim** kayıtlı tabirlere
- **Senkronizasyon** cihazlar arası
- **Kategorilendirme** ve düzenleme

## 🚀 Kurulum

### Gereksinimler
- Node.js 18+ 
- npm veya yarn
- Expo CLI
- Expo Go uygulaması (mobil)

### Adımlar

1. **Projeyi klonlayın**
```bash
git clone https://github.com/ruya-tabirleri/ruya-tabirleri.git
cd ruya-tabirleri
```

2. **Bağımlılıkları yükleyin**
```bash
npm install
```

3. **Uygulamayı başlatın**
```bash
npm start
```

4. **Expo Go ile test edin**
- Expo Go uygulamasını indirin
- QR kodu tarayın veya URL'yi girin

## 📱 Kullanım

### Ana Sekmeler

#### 🔍 Sözlük
- Rüya tabirlerini arayın
- Detaylı içerikleri görüntüleyin
- Sesli arama yapın
- Navigasyon butonlarını kullanın

#### ⭐ Favoriler
- Beğendiğiniz tabirleri kaydedin
- Hızlı erişim için organize edin
- Senkronizasyon yapın

#### 🤖 Yapay Zeka
- Rüyanızı detaylı olarak yazın
- AI yorumu alın
- Sesli okuma yapın
- Tavsiyeleri takip edin

### Arama İpuçları

- **Doğrudan arama**: "yılan", "su", "altın"
- **Duygusal arama**: "korku", "huzur", "mutluluk"
- **Sembolik arama**: "düşman", "fırsat", "engel"
- **Kategori arama**: "maddi", "manevi", "aile"

### Sesli Komutlar

- **"Önceki sayfa"** - Önceki tabire git
- **"Sonraki sayfa"** - Sonraki tabire git
- **"Favorilere ekle"** - Favorilere ekle/çıkar
- **"Seslendir"** - Metni sesli oku
- **"Özet"** - Kısa özet ver

## 🏗️ Teknik Detaylar

### Teknolojiler
- **React Native** - Mobil uygulama framework'ü
- **Expo** - Geliştirme platformu
- **TypeScript** - Tip güvenliği
- **Expo Router** - Navigasyon
- **AsyncStorage** - Yerel veri saklama
- **Expo Speech** - Text-to-Speech

### Mimari
- **Tab-based navigation** - Ana navigasyon
- **Stack navigation** - Detay sayfaları
- **Component-based** - Yeniden kullanılabilir bileşenler
- **State management** - React hooks
- **Local storage** - Favoriler ve ayarlar

### Dosya Yapısı
```
ruya-tabirleri/
├── app/                    # Expo Router sayfaları
│   ├── (tabs)/           # Tab navigasyonu
│   ├── detail/           # Detay sayfaları
│   └── modal.tsx         # Bilgi modalı
├── components/            # Yeniden kullanılabilir bileşenler
├── constants/             # Sabitler ve renkler
├── data/                  # Rüya tabirleri verisi
├── lib/                   # Yardımcı fonksiyonlar
└── assets/                # Resimler ve fontlar
```

## 📊 Veri Yapısı

Her rüya tabiri için:
```json
{
  "slug": "yilan",
  "title": "Yılan",
  "content": "Kısa açıklama",
  "detailedContent": {
    "mainMeaning": "Ana anlam",
    "interpretations": [
      {
        "scenario": "Senaryo",
        "meaning": "Anlam",
        "advice": "Tavsiye"
      }
    ],
    "emotionalContext": "Duygusal bağlam",
    "practicalAdvice": ["Öneri 1", "Öneri 2"],
    "relatedSymbols": ["sembol1", "sembol2"],
    "positiveAspects": "Pozitif yönler",
    "warningSigns": "Uyarı işaretleri"
  }
}
```

## 🎨 Tasarım

### Renk Paleti
- **Primary**: #007AFF (Mavi)
- **Success**: #4CAF50 (Yeşil)
- **Warning**: #FFD700 (Altın)
- **Error**: #F44336 (Kırmızı)
- **Info**: #2196F3 (Mavi)
- **Background**: #F8F9FA (Açık gri)

### Tema Desteği
- **Light mode** - Varsayılan tema
- **Dark mode** - Otomatik sistem teması
- **Responsive design** - Tüm ekran boyutları
- **Accessibility** - Erişilebilirlik standartları

## 🔧 Geliştirme

### Geliştirme Komutları
```bash
npm start          # Geliştirme sunucusu
npm run android    # Android emülatör
npm run ios        # iOS simülatör
npm run web        # Web tarayıcı
npm test           # Test çalıştır
npm run build      # Production build
```

### Kod Kalitesi
- **TypeScript** - Tip güvenliği
- **ESLint** - Kod standartları
- **Prettier** - Kod formatı
- **Git hooks** - Otomatik kontroller

### Test
- **Jest** - Unit testler
- **React Native Testing Library** - Component testler
- **E2E tests** - End-to-end testler

## 📦 Dağıtım

### Expo Build
```bash
expo build:android    # Android APK
expo build:ios        # iOS IPA
expo build:web        # Web bundle
```

### Store Deployment
- **Google Play Store** - Android
- **App Store** - iOS
- **Web** - Progressive Web App

## 🤝 Katkıda Bulunma

### Katkı Süreci
1. Fork yapın
2. Feature branch oluşturun
3. Değişiklikleri commit edin
4. Pull request gönderin

### Geliştirme Kuralları
- **Conventional Commits** kullanın
- **TypeScript** ile yazın
- **Test coverage** %80+ olmalı
- **Code review** zorunlu

## 📄 Lisans

Bu proje **MIT** lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 🙏 Teşekkürler

- **Expo** ekibine harika platform için
- **React Native** topluluğuna
- **FontAwesome** ikonları için
- **Türkçe rüya tabirleri** kaynakları için

## 📞 İletişim

- **GitHub**: [@ruya-tabirleri](https://github.com/ruya-tabirleri)
- **Issues**: [GitHub Issues](https://github.com/ruya-tabirleri/ruya-tabirleri/issues)
- **Discussions**: [GitHub Discussions](https://github.com/ruya-tabirleri/ruya-tabirleri/discussions)

## 🔮 Gelecek Planları

- [ ] **Daha fazla rüya tabiri** ekleme
- [ ] **Çoklu dil desteği** (İngilizce, Almanca)
- [ ] **Offline mode** geliştirme
- [ ] **Push notifications** ekleme
- [ ] **Cloud sync** özelliği
- [ ] **AI model** geliştirme
- [ ] **Sosyal özellikler** ekleme
- [ ] **Analytics** ve raporlama

---

**⭐ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!**

**🌙 Rüyalarınızı anlamlandırın, hayatınızı keşfedin!**
