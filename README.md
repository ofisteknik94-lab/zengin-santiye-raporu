# Zengin İzolasyon Günlük Şantiye Raporu

## GitHub'a yükleme
1. ZIP dosyasını bilgisayarınıza çıkarın.
2. GitHub deposunda **Add file > Upload files** seçin.
3. ZIP içindeki dosyaların tamamını (klasörün kendisini değil) depo ana dizinine sürükleyin.
4. `index.html`, `sw.js`, `manifest.webmanifest`, `icon.svg` ve `README.md` dosyalarının depo kökünde olduğundan emin olun.
5. **Commit changes** ile yüklemeyi tamamlayın.

## Bu sürümde
- PDF'nin ilk sayfası fotoğrafsız rapor kapağıdır; logo, şantiye bilgileri, tarih, şantiye şefi, personel/çalışma ve malzeme bilgileri yer alır.
- Sonraki sayfalarda saha fotoğrafları ikişerli ve büyük boyutta sunulur.
- Personel ve malzeme metinleri satır kaydırır; uzun metinler kesilmez.
- Önbellek sürümü v18'e yükseltildi. Eski uygulama önbellekleri etkinleştirme sırasında güvenli şekilde temizlenir.
- Önbellek temizleme başarısız olsa bile uygulama arayüzüne JavaScript kodu basılmaz; çevrimiçi kullanım devam eder.
- PDF üretimi `pdf-lib` ile yapılır; `html2canvas` gerektirmez.

Not: Raporlar sunucuya kaydedilmez; PDF cihazda oluşturulur ve WhatsApp/e-posta ile paylaşılır.
