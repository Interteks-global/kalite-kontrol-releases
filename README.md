# Kalite Kontrol — Android sürümleri

Bu depo yalnızca **Kalite Kontrol** Android uygulamasının yayınlanmış sürümlerini (APK) içerir. Kaynak kod burada değildir.

- Tabletlerdeki uygulama yeni sürümü bu deponun **en son Release**'inden (`version.json`) kendisi bulur, indirir ve kurulum ekranını açar.
- Her Release'te iki dosya vardır: `TekstilKontrol-<sürüm>-<kod>.apk` ve `version.json` (sürüm numarası, indirme adresi, SHA-256).
- Uygulama, indirilen dosyanın SHA-256 özetini, paket adını, sürümünü ve imza anahtarını doğrulamadan kurulum yapmaz.

Release'leri elle düzenlemeyin; yayın aracı (`npm run release:apk`) ile oluşturulur.
