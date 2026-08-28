# 🛡️ Sigorta Çapraz Satış Destek Sistemi (InsurTech KDS)
### *bGroup // SigortamRahat Karar Destek & Kural Motoru Prototipi*

> **"Doğru müşteriye, doğru zamanda, doğru poliçeyi sunun."**  
> Sigorta acenteleri ve teknik personeller için geliştirilmiş; müşteri profili, meslek risk puanı, demografi ve varlık verilerini analiz ederek nokta atışı çapraz satış (cross-sell) önerileri sunan istemci tabanlı (client-side) akıllı Karar Destek Sistemi (KDS).

[![Canlı Demo](https://img.shields.io/badge/Canlı%20Demo-Vercel-00f3ff?style=for-the-badge&logo=vercel&logoColor=white)](https://sigorta-capraz-satis-destek-sistemi.vercel.app/)
[![Ekosistem](https://img.shields.io/badge/Ekosistem-bGroup%20%2F%2F%20SigortamRahat-0aff00?style=for-the-badge)](#-ekosistem-mimarisi-bgroup--sigortamrahat)

---

## 🌐 Canlı Önizleme

Sistemi tarayıcınızda hemen test etmek için:  
👉 **[sigorta-capraz-satis-destek-sistemi.vercel.app](https://sigorta-capraz-satis-destek-sistemi.vercel.app/)**

---

## 🏛️ Ekosistem Mimarisi (bGroup // SigortamRahat)

Bu Karar Destek Sistemi (KDS), **bGroup** girişim ekosisteminin acente saha verimliliğini ve çapraz satış dönüşüm oranlarını artırma vizyonuyla inşa edilmiştir:

* **SigortamRahat (Model & Saha Katmanı):** 107+ meslek risk haritası, varlık etiketleri, boşluk (Gap) analizi metodolojisi ve acente satış argümantasyonu.
* **DATEX Tasarım (Mutfak Katmanı):** Cyber-Glass arayüz tasarımı, çift panelli analitik çalışma alanı ve yüksek çözünürlüklü A4 PDF teklif motoru.

---

## 🧠 Temel Yetenekler & KDS Mimarisi

### 1. Akıllı Kural Motoru (Rule-Based Engine)
* **107+ Meslek & Risk Ağırlığı:** Her mesleğe özel risk katsayısı (1-10) ve çoklu etiketleme (`HUKUK`, `OFIS`, `DIS_SAHA`, `BEDENSEL`, `ENFEKSIYON`, `YUKSEKTE_CALISMA` vb.).
* **Varlık & İlgi Alanı Eşleme:** Binek araçtan teknelere, evcil hayvandan çatı GES panellerine kadar varlık bazlı otomatik risk tespiti.
* **Demografik Zeka:** Yaş ve cinsiyet kırılımlarına göre otomatik risk önceliklendirmesi (Örn: 50+ yaş için Sağlık ve TSS ağırlığı artışı).

### 2. Gap (Boşluk) Analizi
* Müşterinin halihazırda sahip olduğu poliçeleri (Kasko, Trafik vb.) analizden anında düşer.
* Yalnızca müşterinin ihtiyaç duyduğu eksik tamamlayıcı ürünleri skorlayarak listeler.

### 3. Satış & Teklif Otomasyonu
* 📄 **A4 PDF Rapor Çıktısı:** Seçilen poliçeleri acente kaşe/imza formatına uygun kurumsal bir risk analiz raporuna dönüştürür.
* ✉️ **Tek Tık E-Posta Entegrasyonu:** Müşteri adına kişiselleştirilmiş satış argümanlarını içeren hazır e-posta taslağı oluşturur.

### 4. Lisanslama & Hibrit Veritabanı
* ⚡ **Dahili DB (Zero-Dependency):** Harici dosya gerektirmeyen bağımsız mimari.
* 📂 **Özel Excel Yükleme:** Acentelerin kendi özel `sigorta_db.xlsx` kural dosyalarını tek tıkla sisteme entegre edebilme esnekliği.
* 🔒 **Demo & PRO Modu:** 30 analizlik tarayıcı tabanlı demo sayacı ve PRO lisans doğrulama kapısı.

---

## 🛠️ Kullanılan Teknolojiler

* **HTML5 & CSS3:** Cyber Glassmorphism, CSS Grid, Flexbox, Print Medya Kuralları.
* **JavaScript (Vanilla JS ES6+):** Kural çıkarım algoritması, ağırlıklı skorlama matrisi, dinamik DOM yönetimi ve LocalStorage State takibi.
* **SheetJS (xlsx.full.min.js):** İstemci taraflı Excel veritabanı okuma ve ayrıştırma motoru.
* **Bootstrap 5 & FontAwesome:** Responsive grid ve modern arayüz ikon seti.

---

## 👨‍💻 Geliştirici & Ekosistem Kurucusu

**Batuhan Bayatlı**  
*Founder @ bGroup // Financial Analyst & InsurTech Developer*  

* 🔗 **LinkedIn:** [Batuhan Bayatlı](https://www.linkedin.com/in/batuhanbayatli/)
* 🐙 **GitHub:** [@batuhanbayatli](https://github.com/batuhanbayatli)
* 📧 **E-Posta:** bayatlibatuhan@gmail.com

---
*Copyright © 2026 Batuhan Bayatlı // SigortamRahat // bGroup. Tüm hakları saklıdır.*
