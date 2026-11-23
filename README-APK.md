# Kayı Obası – APK yapma adımları

Bu klasör hazır bir Android (WebView) projesidir. APK'yı GitHub sizin yerinize bulutta derler (bilgisayara Android Studio kurmak gerekmez).

1. github.com'da ücretsiz hesap açın, **New repository** ile boş bir depo oluşturun.
2. Bu klasörün **içindekileri** (app, .github, build.gradle, settings.gradle, gradle.properties…) depoya yükleyin (Add file → Upload files). `.github` klasörü gizli olabilir; yüklendiğinden emin olun.
3. Depoda **Actions** sekmesi → **APK olustur** → **Run workflow**. 3-6 dakika sürer.
4. Bitince çalıştırmaya tıklayın, en altta **KayiObasi-APK** dosyasını indirin, zip'ten `app-debug.apk` çıkar.
5. APK'yı telefona atın, açın; "bilinmeyen kaynaklardan yükleme" iznini verin.

Sesler: `SES-LISTESI.md` dosyasına bakın. mp3'leri `app/src/main/assets/ses/` içine koyup yeniden derleyin.

Alternatif: Android Studio ile klasörü açıp Build → Build APK.

Not: Bu proje burada derlenip telefonda denenmedi; ilk derlemede hata çıkarsa Actions günlüğünü bana yapıştırın.
