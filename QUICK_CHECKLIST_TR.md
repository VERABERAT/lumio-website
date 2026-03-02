# LUMIO - HIZLI TEST KONTROL LİSTESİ

> **Toplam Tahmini Süre:** ~45-60 dakika
> **Öneri:** Simulatörde başla, sonra gerçek cihazda dene

---

## ☑️ TEST 1: HESAP OLUŞTURMA VE GİRİŞ (~5 dk)

- [ ] Uygulama açıldı (splash screen göründü)
- [ ] Giriş sayfası yüklendi
- [ ] `test@lumio.app` ile kaydolundu
- [ ] Ana sayfaya yönlendirildi
- [ ] Hoşgeldin mesajı göründü

---

## ☑️ TEST 2: İLK GÜNLÜK YAZISI (~5 dk)

- [ ] Günlük sekmesine gidildi
- [ ] Yeni yazı ekranı açıldı
- [ ] Başlık yazıldı: "İlk günüm çok güzel geçti"
- [ ] Açıklama yazıldı (uzun metin)
- [ ] 5 duygu butonu görüntülendi
- [ ] "Mutlu" duygusu seçildi
- [ ] Yazı başarıyla kaydedildi

---

## ☑️ TEST 3: DAY0 MODAL (~3 dk)

- [ ] İlk kayıttan sonra Day0 modal açıldı
- [ ] "AI İçgörün Hazır" başlığı görüntülendi
- [ ] AI öneri metni gerçekçi göründü
- [ ] "Kilidi Aç" butonu Paywall'a yönlendirdi
- [ ] "Belki Daha Sonra" butonu modal'ı kapattı

---

## ☑️ TEST 4: PAYWALL (~5 dk)

- [ ] Paywall ekranı açıldı
- [ ] Aylık plan: $4.99/ay görüntülendi
- [ ] Yıllık plan: $39.99/yıl görüntülendi
- [ ] %33 indirim vurgusu göründü
- [ ] Pro özellikler listesi tam:
  - [ ] Sınırsız AI İçgörüleri
  - [ ] Detaylı Analizler
  - [ ] Veri İhracatı
  - [ ] Reklam Yok
- [ ] (Simulatörde) Test satın alma başarılı oldu

---

## ☑️ TEST 5: İKİNCİ GÜNLÜK YAZISI (~5 dk)

- [ ] İkinci yazı oluşturma ekranı açıldı
- [ ] Başlık ve açıklama yazıldı
- [ ] "Mutlu" duygusu seçildi
- [ ] Kaydetme başarılı oldu
- [ ] **Day0 modal AÇILMADI** ✅
- [ ] AI içgörü normal şekilde gösterildi

---

## ☑️ TEST 6: HESAP SİLME (~5 dk)

- [ ] Ayarlar sayfasında "Hesabı Sil" butonu bulundu
- [ ] Uyarı dialogu göründü ("Bu işlem geri alınamaz")
- [ ] "Sil" ve "İptal" butonları görüntülendi
- [ ] Silme işlemi başarılı oldu
- [ ] Giriş sayfasına yönlendirildi
- [ ] Firebase Console'da kullanıcı verisi silindi
- [ ] "entries" ve "insights" koleksiyonları temizlendi

---

## ☑️ TEST 7: DEEP LINKING (~5 dk)

- [ ] `lumio://journal` → Günlük sayfası açıldı
- [ ] `lumio://insights` → İçgörüler sayfası açıldı
- [ ] `lumio://paywall` → Paywall açıldı

---

## ☑️ TEST 8: WIDGET (~5 dk)

- [ ] 4 widget türü listelendi (Quick Entry, Last Entry, Insight, Streak)
- [ ] Widget Home Screen'e eklendi
- [ ] Widget görüntülendi (hata yok)
- [ ] Yeni yazı sonrası widget güncellendi

---

## ☑️ TEST 9: TREND ANALİZİ (~3 dk)

- [ ] Trendler sayfası açıldı
- [ ] Duygu grafikleri yüklendi
- [ ] 7 günlük trend görüntülendi
- [ ] 30 günlük trend görüntülendi
- [ ] Duygu dağılımı doğru (çoğunlukla "Mutlu")

---

## ☑️ TEST 10: VERİ İHRACATI (~3 dk)

- [ ] Veri ihracatı seçeneği bulundu
- [ ] JSON formatı mevcut
- [ ] JSON dosyası başarıyla indirildi
- [ ] Dosyada yazılar ve içgörüler mevcut

---

## ☑️ TEST 11: BİLDİRİMLER (~5 dk)

- [ ] Bildirim ayarları sayfası açıldı
- [ ] Bildirimler açıldı (toggle ON)
- [ ] Saat ayarlandı (20:00)
- [ ] Ayarlar kaydedildi (hata yok)
- [ ] Sistem loglarında bildirim görüldü

---

## 📊 TEST SONUÇ ÖZETİ

| Test | Sonuç | Not |
|------|-------|-----|
| TEST 1: Hesap Oluşturma | ☐ Başarılı / ☐ Hata | |
| TEST 2: İlk Yazı | ☐ Başarılı / ☐ Hata | |
| TEST 3: Day0 Modal | ☐ Başarılı / ☐ Hata | |
| TEST 4: Paywall | ☐ Başarılı / ☐ Hata | |
| TEST 5: İkinci Yazı | ☐ Başarılı / ☐ Hata | |
| TEST 6: Hesap Silme | ☐ Başarılı / ☐ Hata | |
| TEST 7: Deep Linking | ☐ Başarılı / ☐ Hata | |
| TEST 8: Widget | ☐ Başarılı / ☐ Hata | |
| TEST 9: Trend Analizi | ☐ Başarılı / ☐ Hata | |
| TEST 10: Veri İhracatı | ☐ Başarılı / ☐ Hata | |
| TEST 11: Bildirimler | ☐ Başarılı / ☐ Hata | |

---

## 🚀 KISA VERSİYON (Acele İçin)

Sadece kritik testleri yapmak istiyorsan:

1. ✅ **TEST 1** - Hesap oluştur ve giriş yap
2. ✅ **TEST 2** - İlk yazıyı kaydet
3. ✅ **TEST 3** - Day0 modal açıldığını doğrula
4. ✅ **TEST 4** - Paywall fiyatlarını kontrol et
5. ✅ **TEST 5** - İkinci yazıda Day0 modal açılmadığını doğrula
6. ✅ **TEST 6** - Hesabı sil ve Firebase'i kontrol et

Toplam süre: ~25-30 dakika

---

**Başarılar! 🎉**
