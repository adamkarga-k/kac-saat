# ⏳ Kaç Saat? — Ömür Muhasebesi ve Finansal Farkındalık

<p align="center">
  <img src="https://img.shields.io/badge/Lisans-MIT-amber.svg?style=flat-square" alt="Lisans MIT">
  <img src="https://img.shields.io/badge/JavaScript-Vanilla%20ES6+-f7df1e.svg?style=flat-square&logo=javascript&logoColor=black" alt="Vanilla JS">
  <img src="https://img.shields.io/badge/Tasar%C4%B1m-Mobile%20First-22c55e.svg?style=flat-square" alt="Mobile First">
  <img src="https://img.shields.io/badge/Ba%C4%9F%C4%B1ml%C4%B1l%C4%B1k-0%20(S%C4%B1f%C4%B1r)-blue.svg?style=flat-square" alt="Sıfır Bağımlılık">
  <img src="https://img.shields.io/badge/Gizlilik-%25100%20Cihazda-emerald.svg?style=flat-square" alt="Gizlilik Garantisi">
</p>

> *"Bir şey satın aldığınızda parayla değil, o parayı kazanmak için harcadığınız yaşam sürenizle ödersiniz. Ve ömrünüz, marketten tekrar satın alabileceğiniz bir şey değildir."*  
> — **José Mujica**

---

## 📖 Hakkında (Projenin Felsefesi ve Doğuş Hikayesi)

Modern tüketim toplumu bizi sürekli, düşünmeden ve hızlıca harcamaya teşvik eder. Dijital ödeme yöntemleri, tek tıkla siparişler ve taksit seçenekleri; harcanan parayı sadece soyut ve acısız birer dijital rakam haline getirmiştir. 

Oysa gerçekte harcanan şey rakamlar değil; **o parayı kazanabilmek için sabahın köründe çalan alarmlar, trafikte tükenen saatler, patron veya müşteri stresi ve en mühimi: bir daha asla geri gelmeyecek olan gençliğimiz ve ömrümüzdür.**

**Kaç Saat?**, insanları tüketimden bütünüyle mahrum bırakmak veya harcamalarını yargılamak için değil; satın alma tuşuna basmadan önce **bir anlık bilinç, derin bir nefes ve yüzlerde tatlı bir tebessüm** oluşturmak için geliştirildi. 

Türk kültürünün yüzyıllardır imbikten geçmiş ince mizahını (Nasreddin Hoca nükte ve fıkralarını, Bektaşi hazırcevaplığını, Temel zekasını ve yerinde atasözlerini) modern ve sade bir tasarım diliyle buluşturarak, soğuk bir hesap makinesini yaşayan bir **"Ömür Muhasebesi"** aracına dönüştürür.

---

## 💡 Nasıl Çalışır? (Hesaplama Metodolojisi)

Sistem, kullanıcının aylık net kazancı ve haftalık çalışma temposu üzerinden önce zamanının birim maliyetini çıkartır:

1. **Aylık Toplam Çalışma Saati:**
   $$\text{Aylık Mesai Saati} = \left(\text{Haftalık Çalışma Günü} \times \frac{52}{12}\right) \times \text{Günlük Saat}$$
2. **Saatlik ve Dakikalık Net Emeğin Değeri:**
   $$\text{Saatlik Değer} = \frac{\text{Aylık Net Maaş}}{\text{Aylık Mesai Saati}}$$
3. **Ürünün Ömür Bedeli:**
   $$\text{Gerekli Toplam Saat} = \frac{\text{Ürün Fiyatı}}{\text{Saatlik Değer}}$$

### 🎯 İkili Çıktı Standardı & Gerçek Hayat Takvim Süresi
Sistem sonucu kullanıcıya iki farklı perspektiften aynı anda sunar:
* **Mesai Kırılımı:** `7 iş günü, 2 saat`
  * 📅 **Gerçek Hayat Takvim Karşılığı:** Seçilen haftalık çalışma düzenine göre (hafta sonları dahil) gerçek ömrünüzden kaç hafta/ay gittiğini gösterir *(Örn: Haftada 5 gün çalışan birinde 25 iş günü = `1 ay, 1 hafta` olarak hesaplanır)*.
* **Net Kesintisiz Saat:** `58.7 Saat` veya `3.520 Dakika` *(Harcanan zamanın mutlak büyüklüğünü kavramak için)*

---

## ✨ Öne Çıkan Özellikler

* ☀️ **Doğal ve Sıcak Açık Tema:** Yapay zekâ klişesi olan karanlık modlar ve neon ışıklar yerine; gözü yormayan sıcak kâğıt tonları (`#fbfaf8`), zarif amber detaylar ve yüksek kaliteli editoryal tipografi.
* 📱 **Mobile-First & Kusursuz Responsive:** Mobil cihazlarda tek elle hızlı giriş için tasarlanmış; masaüstü geniş ekranlarda ise ferah, ortalanmış ve dengeli bir kart yerleşimi sunar.
* 🎭 **333 Özgün Nükteli Kültürel Mizah Motoru:** Harcama seviyesine göre (ufak bir simit-çaydan, aylar süren büyük yatırımlara kadar 8 kademede) dinamik olarak devreye giren küfürsüz, ince Nasreddin Hoca, Bektaşi, Temel fıkraları ve Türk çarşı/esnaf nükteleri. Tek tıkla `🎲 Başka Nükte` butonuyla değiştirilebilir.
* 💼 **Sadeleştirilmiş Maaş Yönetimi:** Gelir ve mesai bilgileri girildikten sonra form kalabalığı gizlenir; sayfada sadece tek satırlık zarif bir özet ve `[Düzenle]` butonu yer alır.
* 🏷️ **Dinamik Örnekler & Özel Harcama Ekleme:** Standart örneklere ek olarak kullanıcı `+ Kendi Örneğini Ekle` modalı üzerinden dilediği harcama kalemini kaydedebilir. Bu kayıtlar tarayıcının yerel belleğinde saklanır.
* 📸 **Görsel Paylaşım Kartı Üreticisi (HTML5 Canvas):**
  * 📱 **Instagram Hikaye (9:16 - 1080×1920)**
  * 🖼️ **Kare Post (1:1 - 1080×1080)**
  * Ürünü, saat bedelini ve duruma özel fıkrayı yüksek çözünürlüklü estetik bir kart halinde üretir; tek tıkla PNG olarak indirilebilir veya panoya kopyalanabilir.
* 🔒 **Sıfır Veri Toplama (Privacy-First):** Girilen maaş, çalışma saati ve ürün fiyatları **asla hiçbir uzak sunucuya gönderilmez**. Her şey tamamen kullanıcının kendi cihazında (`localStorage`) işlenir.

---

## 🛠️ Teknik Altyapı & Mimari

Proje, gereksiz framework ve kütüphane şişkinliklerinden arındırılmış, maksimum hız ve sürdürülebilirlik odaklı modern web standartlarıyla inşa edilmiştir:

* **Çekirdek:** Saf Vanilla JavaScript (ES6+), Modern DOM API.
* **Tasarım & Tipografi:** Tailwind CSS (CDN), *Plus Jakarta Sans* ve *Newsreader* (Google Fonts).
* **Grafik Motoru:** HTML5 Canvas API (Yüksek DPI retina desteği, `roundRect` ve dinamik metin kaydırma algoritmaları).
* **Veri Kalıcılığı:** Web Storage API (`localStorage`).
* **Pano Entegrasyonu:** Asynchronous Clipboard API (`navigator.clipboard.write` ile doğrudan resim ve metin kopyalama).
* **Gecikme (Latency):** 0 milisaniye derleme ve çalışma süresi.

---

## 🚀 Çalıştırma

Herhangi bir sunucu kurulumu, `npm install` veya build adımına ihtiyaç yoktur:

```bash
# Projeyi klonlayın
git clone https://github.com/adamkarga/kac-saat.git

# Klasöre gidin
cd kac-saat

# index.html dosyasını herhangi bir tarayıcıda doğrudan açın
```

---

## 📄 Lisans

Bu proje [MIT Lisansı](LICENSE) kapsamında açık kaynak olarak sunulmuştur. Özgürce inceleyebilir, geliştirebilir ve kullanabilirsiniz.

---

## 👨‍💻 Hazırlayan

* **adamkarga** — [adamkarga.net](https://adamkarga.net)
