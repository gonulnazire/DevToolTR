# 🚀 DevToolTR

### Doğru geliştirici aracını, doğru proje için seç.

DevToolTR, yazılım geliştiricileri ve özellikle üniversite öğrencileri için geliştirici araçlarını karşılaştıran ve proje ihtiyaçlarına göre araç önerileri sunan web tabanlı bir platformdur.

Proje, **Agent Reviews** yaklaşımından ilham alınarak geliştirilmiş; ancak Türkiye'deki yazılım öğrencilerine yönelik olarak yerelleştirilmiş ve yeni özelliklerle genişletilmiştir.

---

## 🎯 Projenin Amacı

Geliştiriciler bir proje geliştirirken;

- Hangi framework'ü kullanmalıyım?
- Flask mı FastAPI mi?
- React mi Vue mu?
- Hangi veritabanı benim projem için daha uygun?
- Öğrenci olarak hangi araç daha kolay?
- Türkiye'deki geliştiriciler için hangi araç daha uygun?

gibi sorularla karşılaşmaktadır.

**DevToolTR**, bu karar sürecini daha kolay hale getirmeyi amaçlar.

---

## 💡 İlham Kaynağı

Bu proje, **Agent Reviews** tarafından kullanılan geliştirici araçlarını değerlendirme ve karşılaştırma yaklaşımından ilham alınarak geliştirilmiştir.

Ancak DevToolTR yalnızca bir kopya değildir.

Projeye özellikle Türkiye'deki yazılım öğrencilerini hedefleyen özellikler eklenmiştir:

- 🇹🇷 Türkiye Uygunluk Skoru
- 🎓 Öğrenci Uygunluk Skoru
- 🤖 AI Advisor
- 🔍 Araç arama ve kategori filtreleme
- ⚖️ Araç karşılaştırma
- ⭐ Kullanıcı değerlendirmeleri
- 📊 Dinamik puanlama
- 💾 LocalStorage ile kullanıcı verilerinin saklanması

---

## ✨ Özellikler

### 🔎 Geliştirici Araçlarını Keşfetme

DevToolTR içerisinde farklı kategorilerde geliştirici araçları bulunmaktadır.

Desteklenen araçlardan bazıları:

- Flask
- FastAPI
- Django
- React
- Vue
- PostgreSQL
- MongoDB
- Supabase
- Firebase
- Streamlit

---

### 🤖 AI Advisor

Kullanıcı;

- Proje türünü
- Yazılım seviyesini
- İhtiyaçlarını

belirterek kendisine uygun geliştirici araçlarını keşfedebilir.

MVP sürümünde öneri sistemi **kural tabanlı (rule-based)** olarak çalışmaktadır.

Sistem mimarisi ileride gerçek bir LLM/API entegrasyonuna uygun şekilde tasarlanabilecek yapıdadır.

---

### 🇹🇷 Türkiye Skoru

Araçlar yalnızca genel özelliklerine göre değil, Türkiye'deki geliştiriciler ve öğrenciler açısından da değerlendirilmektedir.

Örneğin:

- Öğrenme kolaylığı
- Topluluk desteği
- Kullanım yaygınlığı
- Öğrenci projelerine uygunluk

gibi kriterler dikkate alınmaktadır.

---

### 🎓 Student Score

Öğrencilerin araç seçimini kolaylaştırmak amacıyla araçlara öğrenci uygunluk puanı verilmiştir.

Bu özellik özellikle üniversite öğrencilerinin proje geliştirirken daha kolay karar vermesini amaçlamaktadır.

---

### ⚖️ Araç Karşılaştırma

Örneğin Flask ve FastAPI karşılaştırılarak:

- Öğrenci uygunluğu
- Performans
- Öğrenme kolaylığı
- Türkiye uygunluğu

gibi kriterler üzerinden değerlendirme yapılabilir.

---

### ⭐ Kullanıcı Yorumları

Kullanıcılar araçlar hakkında:

- Puan verebilir
- Yorum yazabilir
- Kullandıkları aracı belirtebilir

Girilen değerlendirmeler tarayıcının **LocalStorage** alanında saklanmaktadır.

Kullanıcı yorumları sonucunda araçların ortalama puanları dinamik olarak güncellenmektedir.

---

## 🛠️ Kullanılan Teknolojiler

| Teknoloji | Kullanım Alanı |
|---|---|
| HTML5 | Sayfa yapısı |
| CSS3 | Arayüz ve tasarım |
| JavaScript | Etkileşim ve uygulama mantığı |
| LocalStorage | Kullanıcı yorumlarının saklanması |
| Git | Versiyon kontrolü |
| GitHub | Kod deposu |
| GitHub Pages | Web sitesinin yayınlanması |

---

## 🧠 Proje Mimarisi

DevToolTR şu anda tek dosyalı bir MVP olarak geliştirilmiştir.

```text
DevToolTR
│
├── index.html
│   ├── HTML
│   ├── CSS
│   └── JavaScript
│
└── LocalStorage
    └── Kullanıcı yorumları
