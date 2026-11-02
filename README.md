# Gardırobum

Kıyafetlerinin, ayakkabılarının, saat ve takılarının fotoğrafını çekip ekle; uygulama renk uyumu, mevsim ve ortama göre kombin önersin.

## APK'yı indir

[Releases](../../releases/latest) sayfasından en son `Gardirobum-*.apk` dosyasını telefonuna indirip aç. Android, bilinmeyen kaynaklardan kuruluma izin vermeni isteyebilir.

## Nasıl çalışır

- Android uygulaması, `app/src/main/assets/index.html` içindeki web uygulamasını gösteren bir WebView'dir.
- Parçalar ve kombinler telefonda (IndexedDB) saklanır. Uygulamayı kaldırırsan veriler silinir.
- "Fotoğraf çek" telefonun kamerasını, "Galeriden seç" galeriyi açar.
- `main` dalına her gönderimde GitHub Actions APK'yı derler ve yeni bir sürüm yayınlar.
