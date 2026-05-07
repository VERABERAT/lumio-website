# LUMIO - DETAYLI TEST SENARYOLARı

## ÖNEMLİ NOTLAR
- Her test için yazılan cümleleri KOPİ-YAPIŞT yapabilirsin
- Türkçe yazılı adımları takip et
- Hata bulursan, ekran görüntüsü al ve bana göster

---

## TEST 1: HESAP OLUŞTURMA VE GİRİŞ

### Adım 1: Uygulamayı aç
**Ne yapacaksın:** Telefonuna veya simulatörüne Lumio uygulamasını kur ve aç.

**Bak şu şeylere:**
- Splash screen görsün (Lumio logosu)
- Giriş sayfası yüklensin

### Adım 2: E-posta ve şifre ile kaydol
**Yazacağın e-posta:**
```
test@lumio.app
```
**Yazacağın şifre:**
```
Lumio123!
```

**Ne yapacaksın:**
1. "Kaydol" butonuna tıkla
2. E-posta alanına `test@lumio.app` yaz
3. Şifre alanına `Lumio123!` yaz
4. "Kaydol" butonuna tıkla

**Bak şu şeylere:**
- Kaydolma başarılı oldu mu? (Evet = iyi, Hayır = hata)
- Ana sayfaya (Home) yönlendirildin mi?
- Hoşgeldin mesajı göründü mü?

---

## TEST 2: İLK GÜNLÜK YAZISI OLUŞTURMA

### Adım 1: Günlük uygulamasını aç
**Ne yapacaksın:**
1. Alt menüden "Günlük" veya "Journal" butonuna tıkla
2. "+" veya "Yeni Yazı" butonuna tıkla

**Bak şu şeylere:**
- Yazı oluşturma ekranı açıldı mı?
- Başlık ve açıklama alanları görünüyor mu?
- Duygu seçme butonu var mı?

### Adım 2: Yazı bilgilerini doldur
**Yazacağın başlık:**
```
İlk günüm çok güzel geçti
```
**Yazacağın açıklama:**
```
Bugün sabah erken kalktım ve kahvaltı yaptım. Sonra biraz yürüyüş yaptım. Hava çok güzel ve rüzgar ferah idi. Öğle yemeği evde yedim. Akşam da biraz müzik dinledim ve dinlenme yaptım. Genel olarak bugün çok güzel bir gün oldu ve kendimi iyi hissettim.
```

**Ne yapacaksın:**
1. Başlık alanına tıkla
2. Üstteki başlığı yaz
3. Açıklama alanına tıkla
4. Üstteki metni yaz

### Adım 3: Duygu seç
**Ne yapacaksın:**
1. Duygu seçme butonuna tıkla (5 farklı duygu görünmeli: Mutlu, Sakin, Endişeli, Üzgün, Kızgın)
2. "Mutlu" (Happy) duygusunu seç

**Bak şu şeylere:**
- 5 duygu butonu görünüyor mu?
- Seçtiğin duygu seçili göründü mü?

### Adım 4: Yazıyı kaydet
**Ne yapacaksın:**
1. "Kaydet" veya "Gönder" butonuna tıkla

**Bak şu şeylere:**
- Yazı kaydedildi mi?
- Başarı mesajı göründü mü?
- Yazılar listesine geri dönüldü mü?

---

## TEST 3: DAY0 MODALı (İLK YAZIDAN SONRA AI ÖNERİSİ)

### Adım 1: İlk yazıdan sonra modal açılması
**Ne yapacaksın:**
- Üst testte yazı kaydettikten sonra ekran ne oldu bak

**Bak şu şeylere:**
- **ÖNEMLİ**: "Day0" modal açıldı mı? (Ekranı kaplayan pencere)
- Modal'da şunlar yazıyor mu?
  - "AI İçgörün Hazır"
  - "Yapay zeka tarafından analiz edilen özel içgörü"
  - Yazıdan çıkarılan bir öneri (örn: "Bugün çok aktif ve produktif bir gündü!")

### Adım 2: Modal'ı kontrol et
**Ne yapacaksın:**
1. Modal içeriğini oku
2. "Kilidi Aç" veya "Unlock Pro" butonuna tıkla (eğer varsa)

**Bak şu şeylere:**
- AI öneri metni gerçekçi mi görünüyor?
- "Kilidi Aç" butonu Paywall'a yönlendiriyor mu?
- "Belki Daha Sonra" butonu modal'ı kapatıyor mu?

### Adım 3: Modal'ı kapat
**Ne yapacaksın:**
- "Belki Daha Sonra" butonuna tıkla

**Bak şu şeylere:**
- Modal kapandı mı?
- Ana sayfaya geri dönüldü mü?

---

## TEST 4: PAYWALL (ÜCRETLENDIRME EKRANI)

### Adım 1: Paywall'u aç
**Ne yapacaksın:**
1. Alt menüde "Profil" veya "Ayarlar" seçeneğini bul
2. "Upgrade to Pro" veya "Pro Olun" butonuna tıkla

**Bak şu şeylere:**
- Paywall açıldı mı?
- 2 farklı fiyat seçeneği var mı?

### Adım 2: Fiyatları kontrol et
**Bak şu şeylere:**
- **Aylık Plan**: $4.99/ay yazıyor mu?
- **Yıllık Plan**: $39.99/yıl yazıyor mu?
- Yıllık plan daha ekonomik gözüküyor mu? (Evet, %33 indirim olmalı)

### Adım 3: Özellikler listesi
**Bak şu şeylere:**
- Pro özellikleri şu şekilde yazıyor mu?
  - "Sınırsız AI İçgörüleri"
  - "Detaylı Analizler"
  - "Veri İhracatı"
  - "Reklam Yok"

### Adım 4: Test Satın Alma (SADECE SİMÜLATÖR/TEST CIHAZI İÇİN)
**ÖNEMLİ:** Eğer gerçek cihazda test ediyorsan, henüz satın alma yapma!

**Eğer simulatörde test ediyorsan:**
1. "Aylık Planı Satın Al" butonuna tıkla
2. Apple satın alma dialogu açılmalı
3. "Satın Al"ı tıkla (Test App Store'u kullanmalı, gerçek ücret çekilmez)

**Bak şu şeylere:**
- Satın alma dialogu açıldı mı?
- İşlem başarılı oldu mu?
- Pro özellikleri aktif oldu mu?

---

## TEST 5: İKİNCİ GÜNLÜK YAZISI (DAY0 MODAL OLMAMALI)

### Adım 1: Yeni yazı oluştur
**Ne yapacaksın:**
1. Günlük sekmesine git
2. "+" butonuna tıkla
3. Aşağıdaki bilgileri yaz

**Yazacağın başlık:**
```
İkinci günüm daha da güzel oldu
```
**Yazacağın açıklama:**
```
Bugün çalışmalar çok verimli geçti. Yeni bir proje başladım ve çok ilginç bir konu. Öğleden sonra arkadaşlarla buluştuk ve eğlenceliyiz. Akşam eve gelince biraz dinlendim. Yarın için planlarım var ve heyecanlıyım.
```

### Adım 2: Duygu seç
**Ne yapacaksın:**
1. Duygu seçme butonuna tıkla
2. "Mutlu" (Happy) duygusunu seç

### Adım 3: Kaydet
**Ne yapacaksın:**
1. "Kaydet" butonuna tıkla

**ÖNEMLİ - Bak şu şeylere:**
- **Day0 modal AÇILMAMALI** (sadece ilk yazıda açılmalı)
- Normal olarak yazı kaydedilmeli
- AI İçgörü normal şekilde gösterilmeli (ör: "Bu haftanın en mutlu günü!")

---

## TEST 6: HESAP SİLME (HATA KONTROLÜ)

### Adım 1: Ayarlar sayfasına git
**Ne yapacaksın:**
1. Alt menüde "Profil" veya "Settings" butonuna tıkla
2. Sayfayı aşağıya scroll et

**Bak şu şeylere:**
- "Hesabı Sil" veya "Delete Account" butonu görünüyor mu?

### Adım 2: Hesap silmeyi başlat
**Ne yapacaksın:**
1. "Hesabı Sil" butonuna tıkla
2. Uyarı dialogu açılacak

**Bak şu şeylere:**
- Uyarı mesajı var mı? ("Bu işlem geri alınamaz", vb)
- "Sil" ve "İptal" butonları var mı?

### Adım 3: Silmeyi onayla
**Ne yapacaksın:**
1. "Sil" butonuna tıkla

**Bak şu şeylere:**
- İşlem başarılı oldu mu?
- Giriş sayfasına yönlendirildin mi?
- Yükleme animasyonu göründü mü?

### Adım 4: Firebase Console'da Kontrol Et (ÖNEMLİ!)
**Ne yapacaksın:**
1. Web tarayıcıda Firebase Console'a git: https://console.firebase.google.com
2. "lumio-488709" projesini seç
3. "Firestore" → "Veri" sekmesine tıkla
4. "users" koleksiyonunda `test@lumio.app` kullanıcısını ara

**Bak şu şeylere:**
- Kullanıcı verisi silinmiş mi?
- "entries" ve "insights" alt koleksiyonları temiz mi?
- Hiç veri kalması gerekmiyor!

---

## TEST 7: DEEP LINKING (DERİNLEMESİNE BAĞLANTI)

**ÖNEMLİ:** Bu test Xcode Terminal'de veya Cihaz Ayarlarında yapılır.

### Adım 1: Uygulama kapalıyken deep link aç
**Ne yapacaksın:**
Terminal'de bu komutu çalıştır:
```bash
xcrun simctl openurl booted "lumio://journal"
```

**Bak şu şeylere:**
- Uygulama açıldı mı?
- Günlük sayfasına gitti mi?

### Adım 2: İçgörüler sayfasına git
**Terminal'de:**
```bash
xcrun simctl openurl booted "lumio://insights"
```

**Bak şu şeylere:**
- İçgörüler sayfasına yönlendirildin mi?

### Adım 3: Paywall'a git
**Terminal'de:**
```bash
xcrun simctl openurl booted "lumio://paywall"
```

**Bak şu şeylere:**
- Paywall açıldı mı?

---

## TEST 8: WIDGET TESTİ

### Adım 1: Widget ekle
**Ne yapacaksın:**
1. Home Screen'de widget ekle butonu tıkla
2. Lumio widget'ını ara ve seç
3. 4 farklı widget var mı?
   - Hızlı Yazı (Quick Entry)
   - Son Giriş (Last Entry)
   - İçgörü (Insight)
   - Seri Gün (Streak)

**Bak şu şeylere:**
- Widget görünüyor mu?
- Hata göstermiyor mu?

### Adım 2: Widget verisi senkronize oldu mu?
**Ne yapacaksın:**
1. Lumio uygulamasını aç
2. Yeni bir yazı oluştur
3. Kaydet
4. Home Screen'e dön

**Bak şu şeylere:**
- Widget yeni yazıyı gösteriyor mu?
- Veri senkronize oldu mu?

---

## TEST 9: TREND ANALİZİ

### Adım 1: Trends sayfasına git
**Ne yapacaksın:**
1. Alt menüde "Trendler" veya "Trends" seçeneğine tıkla

**Bak şu şeylere:**
- Duygu grafikleri açıldı mı?
- Geçmiş yazılardan veri gösteriyor mu?

### Adım 2: Grafikleri kontrol et
**Bak şu şeylere:**
- 7 günlük trend var mı?
- 30 günlük trend var mı?
- Duygu dağılımı doğru mı? (Çoğunlukla "Mutlu" gösterilmeli)

---

## TEST 10: VERİ İHRACATI

### Adım 1: Veri ihraç seçeneğini bul
**Ne yapacaksın:**
1. Profil → Ayarlar → Veri İhracatı (varsa)
2. Veya settings sayfasında "Export" butonu ara

**Bak şu şeylere:**
- Veri ihracatı seçeneği var mı?
- JSON, CSV, PDF formatları mümkün mü?

### Adım 2: JSON olarak ihraç et
**Ne yapacaksın:**
1. "JSON olarak İndir" butonuna tıkla

**Bak şu şeylere:**
- Dosya indirildi mi?
- Dosyada yazılar ve içgörüler var mı?

---

## TEST 11: BİLDİRİMLER (VARSA)

### Adım 1: Bildirim ayarlarını kontrol et
**Ne yapacaksın:**
1. Profil → Ayarlar → Bildirimler
2. Bildirimleri aç (toggle ON)
3. Saati ayarla (örn: 20:00)

**Bak şu şeylere:**
- Bildirim ayarları kaydedildi mi?
- Hata mesajı var mı?

### Adım 2: Bildirim test et (24 saat beklemek zorunda değilsin)
**Terminal'de (simulator'da):**
```bash
xcrun simctl spawn booted log stream --predicate 'eventMessage contains[cd] "LUMIO"' --level debug
```

**Bak şu şeylere:**
- Bildirim sistem loglarında görünüyor mu?

---

## HATA RAPORU ŞABLONU

Hata bulursan, bana şu formatta yaz:

```
## HATA: [Hata Adı]
**Adım:** [Hangi adımda hata oluştu?]
**Beklenen:** [Ne olması gerekiyordu?]
**Gerçek:** [Ne oldu?]
**Ekran Görüntüsü:** [Varsa ekran görüntüsünü gönder]
**Telefon Model:** [iPhone 15, Simulator, vb]
**iOS Sürümü:** [16.0, 17.0, vb]
**Hata Mesajı:** [Eğer ekranda görüntülenen hata mesajı varsa]
```

---

## BAŞARILI TEST ÖRNEĞİ

Testi başarıyla tamamladıysan şu şekilde bildir:

```
✅ TEST 1: HESAP OLUŞTURMA - BAŞARILI
   - Hesap oluşturuldu
   - Giriş yapıldı
   - Ana sayfaya yönlendirildi

✅ TEST 2: İLK YAZI - BAŞARILI
   - Yazı kaydedildi
   - Duygu seçimi çalıştı

✅ TEST 3: DAY0 MODAL - BAŞARILI
   - Modal açıldı
   - AI içgörü gösterildi
```

---

## ÖNEMLİ NOTLAR
- Her testi sırasıyla yap
- Hata bulursan durma, diğer testleri de yap
- Firebase Console'da verileri kontrol et (TEST 6'da)
- Resmi cihazda değil, simulatörde başla
- Sorularım varsa bana sor!

**Başarılar! 🎉**
