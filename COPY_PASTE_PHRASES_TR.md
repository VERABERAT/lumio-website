# LUMIO - KOPİ-YAPIŞT CÜMLE LİSTESİ

## 🔐 GİRİŞ BİLGİLERİ

### E-posta:
```
test@lumio.app
```

### Şifre:
```
Lumio123!
```

---

## 📝 GÜNLÜK YAZILARI

### 1. Yazı - Başlık:
```
İlk günüm çok güzel geçti
```

### 1. Yazı - Açıklama:
```
Bugün sabah erken kalktım ve kahvaltı yaptım. Sonra biraz yürüyüş yaptım. Hava çok güzel ve rüzgar ferah idi. Öğle yemeği evde yedim. Akşam da biraz müzik dinledim ve dinlenme yaptım. Genel olarak bugün çok güzel bir gün oldu ve kendimi iyi hissettim.
```

### 2. Yazı - Başlık:
```
İkinci günüm daha da güzel oldu
```

### 2. Yazı - Açıklama:
```
Bugün çalışmalar çok verimli geçti. Yeni bir proje başladım ve çok ilginç bir konu. Öğleden sonra arkadaşlarla buluştuk ve eğlenceliyiz. Akşam eve gelince biraz dinlendim. Yarın için planlarım var ve heyecanlıyım.
```

---

## ✅ BAŞARI RAPORU ŞABLONU

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

✅ TEST 4: PAYWALL - BAŞARILI
   - Paywall açıldı
   - Fiyatlar doğru görüntülendi

✅ TEST 5: İKİNCİ YAZI - BAŞARILI
   - Day0 modal açılmadı
   - Yazı kaydedildi

✅ TEST 6: HESAP SİLME - BAŞARILI
   - Hesap silindi
   - Giriş sayfasına yönlendirildi

✅ TEST 7: DEEP LINKING - BAŞARILI
   - journal linki çalıştı
   - insights linki çalıştı
   - paywall linki çalıştı

✅ TEST 8: WIDGET - BAŞARILI
   - Widget görüntülendi
   - Veri senkronize oldu

✅ TEST 9: TRENDLER - BAŞARILI
   - Grafikler gösterildi
   - Veriler doğru

✅ TEST 10: VERİ İHRACATI - BAŞARILI
   - JSON indirildi
   - Veriler eksiksiz

✅ TEST 11: BİLDİRİMLER - BAŞARILI
   - Bildirim ayarlandı
   - Sistem loglarında görüldü
```

---

## ❌ HATA RAPORU ŞABLONU

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

## 🔗 FİREBASE URL'LERİ

### Firebase Console:
```
https://console.firebase.google.com
```

### Proje ID:
```
lumio-488709
```

---

## 💻 TERMİNAL KOMUTLARI

### Journal deep link:
```bash
xcrun simctl openurl booted "lumio://journal"
```

### Insights deep link:
```bash
xcrun simctl openurl booted "lumio://insights"
```

### Paywall deep link:
```bash
xcrun simctl openurl booted "lumio://paywall"
```

### Bildirim log izleme:
```bash
xcrun simctl spawn booted log stream --predicate 'eventMessage contains[cd] "LUMIO"' --level debug
```
