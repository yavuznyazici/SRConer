# SRConer – SRC4 Sınav Hazırlık

SRConer, SRC4 (yurtiçi eşya-kargo taşımacılığı) sınavına hazırlık için çevrimdışı kullanılabilen Flutter uygulamasıdır.

## Özellikler
- 250 adet dört seçenekli çalışma sorusu
- Cevap seçildikten sonra doğru/yanlış renkli geri bildirim
- Doğru cevap ve kısa açıklama
- Yanlış cevaplanan soruları tekrar çözme
- İlerleme ve cevap geçmişini cihazda saklama
- Genel ve konu bazında başarı istatistikleri
- Başarı rozetleri

## GitHub üzerinden APK oluşturma (bilgisayarsız yöntem)
1. GitHub'da `SRConer` adında yeni bir depo (repository) oluştur.
2. Bu ZIP dosyasını `SRConer_Project.zip` adıyla deponun ana dizinine yükle.
3. Depoda `.github/workflows/build-apk.yml` yoluyla bir dosya oluştur ve ZIP içindeki aynı adlı workflow içeriğini bu dosyaya yapıştır.
4. `Actions` sekmesinden **Build SRConer APK** iş akışını çalıştır.
5. İşlem başarılı olursa çalıştırma sayfasının altındaki **SRConer-APK** dosyasını indir. ZIP içinden `app-release.apk` dosyasını çıkarıp Android telefona kur.

Workflow, kaynak ZIP'ini otomatik açar, eksik Android proje dosyalarını oluşturur ve APK'yı derler. Kaynak proje ZIP'i içinde `android/` klasörü bulunmaması normaldir.

## Soru bankası hakkında
Sorular eğitim amacıyla hazırlanmış çalışma sorularıdır; resmî çıkmış sınav soruları değildir ve resmî kurumlarca onaylandığı anlamına gelmez. Sınav öncesinde güncel mevzuat ve resmî duyurular kontrol edilmelidir.
