# 🙈 XSIDE Style Universe — AI Kombin Asistanı

> **Waikiki Challengers 2026 — Round 2**  
> Takım: **XO MOVERS**

<div align="center">

![XSIDE](https://img.shields.io/badge/XSIDE-Style%20Universe-FF3080?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyeiIvPjwvc3ZnPg==)
![Claude](https://img.shields.io/badge/Powered%20by-Claude%20Sonnet%204-B06EF3?style=for-the-badge)
![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react)
![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-222?style=for-the-badge&logo=github)

**[🚀 Canlı Demo →](https://zehrakolsuz.github.io/xside-platform)**

</div>

---

## 🌸 Proje Nedir?

XSIDE Style Universe, LC Waikiki'nin genç kadın markası **XSIDE** için geliştirilen yapay zeka destekli kişisel stil asistanı platformudur.

Tek bir `index.html` dosyasıyla çalışan bu uygulama; **AI kombin önerileri**, **gardrop analizi**, **müzik vibe eşleştirmesi** ve **topluluk özellikleriyle** Melis'in (hedef müşterimiz, 18-25 yaş) alışveriş deneyimini kökten dönüştürür.

---

## ✨ Özellikler

### 🙈 Xo — AI Stil Asistanı
- **Gerçek zamanlı AI** kombin önerileri (Claude Sonnet 4)
- **📎 Fotoğraf yükleme** → Kıyafet analizi + XSIDE kombinleri
- **📐 Fit & Kalıp Rehberi** — Oversize, Barrel, Bodycon kalıp açıklamaları
- **🧺 Kumaş Bakım Analizi** — Pamuk, Denim, Keten, Mesh talimatları
- Kupon + Kişisel Takip Kodu sistemi

### 🎵 Müzik Vibe → Kombin
- 6 müzik profili: K-Pop, Hip-Hop, Indie, Pop/Y2K, R&B, Alt/Rock
- Her vibe için AI destekli XSIDE kombin + fit + bakım önerisi
- `#XSIDEStyle` paylaşım → Otomatik kupon

### 👗 Dolabım — AI Gardrop Analizi
- Fotoğraf yükle → AI stilini analiz eder
- Eksik XSIDE parçalarını önerir
- TikTok/IG trend kombinleri
- Kişisel takip kodu ile sosyal medya entegrasyonu

### 🏪 Mağaza Ekranı
- Anlık stok takibi
- Ürün bazlı AI kombin önerisi
- Kumaş bilgisi + bakım rehberi
- Mağaza içi dokunmatik ekran moduna uygun

### 🎪 XSIDE Life — Topluluk
- Üniversite etkinlik takvimi (İTÜ, Marmara, YTÜ, Boğaziçi, Bilgi)
- #XSIDEStyleChallenge
- Trend & veri analizi paneli

---

## 🚀 Kurulum

### Seçenek 1: Direkt Aç (Sıfır Kurulum)
```bash
# Dosyayı indir ve tarayıcıda aç
open index.html
```

### Seçenek 2: GitHub Pages
```
1. Bu repoyu fork'la veya kendi repon olarak yükle
2. Settings → Pages → Branch: main / (root) → Save
3. https://kullaniciadi.github.io/xside-platform
```

### Seçenek 3: Local Server
```bash
# Python ile
python3 -m http.server 8080

# Node ile
npx serve .
```

---

## 🤖 AI Özelliklerini Aktif Etmek

Uygulama **demo modda** API key olmadan da çalışır. Gerçek AI için:

1. [console.anthropic.com](https://console.anthropic.com) adresinden ücretsiz hesap aç
2. API key oluştur (`sk-ant-...` ile başlar)
3. Uygulamayı aç → Üstteki **"API Key Ekle"** butonuna tıkla
4. Key'ini gir → Kaydet

> ⚠️ API key tarayıcıda `localStorage`'a kaydedilir. Production ortamında backend üzerinden kullan.

---

## 🏗️ Teknik Mimari

```
index.html (tek dosya, ~1.1 MB)
│
├── React 18 (CDN, Babel standalone)
├── Claude Sonnet 4 API
│   ├── /v1/messages endpoint
│   ├── Vision (fotoğraf analizi)
│   └── Text generation (kombin önerileri)
│
├── 5 Ana Sekme
│   ├── HomeTab      — Hub & özet
│   ├── MusicTab     — Müzik vibe → kombin
│   ├── ChatTab      — Xo AI asistan + fotoğraf
│   ├── WardrobeTab  — Gardrop analizi
│   └── CommunityTab — Etkinlikler & topluluk
│
└── Assets
    └── Xo Maskot GIF (base64, Zehra Nur Kolsuz tasarımı)
```

### Kullanılan Teknolojiler
| Teknoloji | Kullanım |
|---|---|
| React 18 | UI bileşenleri |
| Babel Standalone | JSX → JS dönüşümü |
| Anthropic Claude Sonnet 4 | AI kombin + görsel analiz |
| CSS Animations | Float, shimmer, fade efektleri |
| FileReader API | Fotoğraf yükleme |
| Clipboard API | Kupon kopyalama |
| localStorage | API key saklama |

---

## 📊 İş Değeri

| Metrik | Hedef |
|---|---|
| Sepet Ortalaması (AOV) | +%30 artış |
| Sepet Terk Oranı | -%25 azalma |
| UGC Paylaşım | %50+ kullanıcı |
| İade Oranı | -%20 azalma |
| Kampüs Erişimi | 5+ üniversite |

---

## 👥 Takım — XO MOVERS

| İsim | Rol |
|---|---|
| **Zehra Nur Kolsuz** | Maskot Tasarımı (Xo karakteri) & Konsept |
| **Şilan İnce** | Müşteri İçgörüsü & Sunum |
| **Asya Güngörsen** | Fikir Geliştirme & Kullanıcı Akışı |
| **Bilge Kırıcı** | Özellik Tasarımı & Mağaza Ekranı |
| **Rabia Esma Kaşgarlı** | Pazarlama & İş Modeli |
| **Fatih Çağal** | Teknik Geliştirme & Demo |

---

## 🎨 Tasarım Sistemi

```css
--pink:   #FF3080   /* Ana renk — Hot Rose */
--violet: #B06EF3   /* İkincil — Lavanta */
--gold:   #FFD166   /* Vurgu — Sıcak Altın */
--rose:   #FF8FA3   /* Soft Pembe */
--mint:   #A8FFD8   /* Başarı — Nane */
--dark:   #0C0818   /* Arkaplan — Derin Plum */
```

> Renk paleti 18-25 yaş kadın kitlesine özel tasarlandı. Mor-pembe tonu GenZ favorisi, altın vurgu ödül psikolojisi için.

---

## 📁 Dosya Yapısı

```
xside-platform/
│
├── index.html          # Tek dosya — tüm uygulama burada
├── README.md           # Bu dosya
├── xo_animated.gif     # Xo maskot animasyonu (opsiyonel, HTML içinde base64)
└── xo_transparent.png  # Xo maskot statik PNG
```

---

## 📜 Lisans

Bu proje **Waikiki Challengers 2026** yarışması için akademik amaçla geliştirilmiştir.  
XSIDE ve LC Waikiki markaları ilgili şirketlerin tescilli markasıdır.  
Xo maskot tasarımı © Zehra Nur Kolsuz

---

<div align="center">

**HAYAL ET · TASARLA · GELECEĞİN MODA DÜNYASINA MEYDAN OKU**

🙈 *Made with love by The XsiderS*

</div>
