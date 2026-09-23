# Web Programlama - Hafta 1: Semantik HTML ve Etkinlik Portalı

Bu depo, Web Tasarımı ve Programlama dersi kapsamında temel HTML5 standartları, anlamsal (semantik) etiket kullanımı ve erişilebilirlik ilkeleri uygulanarak geliştirilen statik web sayfalarını içerir.

Proje, örnek bir üniversite/kampüs etkinlik yönetim arayüzü (Kariyer Günleri 2026) üzerinden yapılandırılmıştır.

---

## 📌 İçerik ve Sayfa Yapısı

Proje temel olarak 3 bağlantılı HTML sayfasından oluşmaktadır:

* **`etkinlikler.html` (Ana Sayfa / Liste):** Yayındaki tüm etkinliklerin listelendiği ana sayfa.
* **`etkinlik-detay.html` (Detay Sayfası):** Belirli bir etkinliğe ait afiş görseli, tarih, yer ve kontenjan gibi meta bilgilerin anlamsal listeler (`<dl>`, `<dt>`, `<dd>`) ve `<time>` etiketleriyle sunulduğu sayfa.
* **`etkinlik-ekle.html` (Detay / Etkinlik Ekle):** Yeni etkinlik girişleri veya içerik detayları için tasarlanmış form/giriş şablonu.

---

## 🛠️ Kullanılan Teknolojiler ve Standartlar

* **HTML5:** Modern ve geçerli sayfa iskeleti (`<!DOCTYPE html>`).
* **Anlamsal (Semantic) Web:** Ekran okuyucular ve SEO uyumluluğu için `<header>`, `<nav>`, `<main>`, `<article>`, `<figure>`, `<figcaption>` ve `<footer>` etiketleri.
* **Meta & Formatlama:** Türkçe karakter desteği için `UTF-8` karakter kümesi ve zaman damgaları için makine tarafından okunabilir ISO formatlı `<time datetime="...">` kullanımı.

---

## 📂 Dosya Hiyerarşisi

```text
web-ders-1/
├── afis.jpg               # Etkinlik tanıtım görseli
├── etkinlik-detay.html    # Etkinlik detay sayfası
├── etkinlik-ekle.html     # Yeni etkinlik giriş sayfası
├── etkinlikler.html       # Etkinlik listesi (Ana sayfa)
└── README.md              # Proje dokümantasyonu
