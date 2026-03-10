# 🛒 Market Listem

**Çevrimdışı çalışan, hafif ve hızlı bir alışveriş listesi PWA uygulaması.**

![Market Listem Logo](logo.svg)

---

## ✨ Özellikler

- 📦 **Çevrimdışı destek** — Service Worker ile internet olmadan da çalışır
- 💾 **Kalıcı veri** — `localStorage` ile veriler tarayıcıda saklanır
- ✅ **Tamamlama** — Ürünleri tamamlandı olarak işaretleyin
- 🗑️ **Silme** — Animasyonlu silme işlemi
- 🔊 **Ses efektleri** — Web Audio API ile doğal sesler
- 📱 **PWA desteği** — Ana ekrana eklenebilir, uygulama gibi çalışır
- 📊 **Sayaç** — Kalan ürün sayısını anlık gösterir
- 🎨 **Duyarlı tasarım** — Mobil ve masaüstü uyumlu

---

## 🚀 Kullanım

```bash
# Repoyu klonla
git clone https://github.com/kullaniciadi/market-listem.git

# Klasöre gir
cd market-listem
```

Herhangi bir yerel HTTP sunucusu ile açın:

```bash
# Python ile
python3 -m http.server 8000

# Node.js ile (npx)
npx serve .
```

Tarayıcıda `http://localhost:8000` adresine gidin.

> ⚠️ Service Worker'ın çalışması için `http://localhost` veya HTTPS gereklidir.

---

## 📂 Dosya Yapısı

```
market-listem/
├── index.html      # Ana uygulama
├── manifest.json   # PWA manifest dosyası
├── sw.js           # Service Worker (çevrimdışı destek)
├── logo.svg        # Uygulama logosu
└── README.md       # Bu dosya
```

---

## 🌐 GitHub Pages ile Yayınlama

1. Repoyu GitHub'a push edin
2. **Settings → Pages → Source: main branch / root** seçin
3. Birkaç dakika sonra `https://kullaniciadi.github.io/market-listem` adresinde yayına girer

---

## 🛠️ Teknolojiler

| Teknoloji | Kullanım |
|-----------|----------|
| HTML5 / CSS3 / JS | Temel uygulama |
| Service Worker API | Çevrimdışı önbellekleme |
| Web App Manifest | PWA desteği |
| Web Audio API | Ses efektleri |
| localStorage | Veri kalıcılığı |

---

## 📄 Lisans

MIT © 2024
