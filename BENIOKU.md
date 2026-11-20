# Asistanım – Android uygulaması

Bu klasör, "Levent Şanlı · Asistanım" sayfasını telefonda uygulama olarak açan bir Android projesidir.
Sayfa `app/src/main/assets/index.html` dosyasındadır; internet olmadan da çalışır.

## APK'yı almanın en kolay yolu (bilgisayara bir şey kurmadan): GitHub

1. github.com'da ücretsiz bir hesap açın ve **New repository** ile yeni bir depo oluşturun (ör. `asistanim`).
2. Depo sayfasında **uploading an existing file** bağlantısına tıklayın.
3. Bu klasörün **içindeki her şeyi** (`.github` klasörü dahil) sürükleyip bırakın ve **Commit changes**'e basın.
   - Gizli `.github` klasörü görünmüyorsa: Windows'ta Görünüm → Gizli öğeler; Mac'te Cmd+Shift+. ile gösterin.
4. Üstteki **Actions** sekmesine gidin. "APK oluştur" işi kendiliğinden başlar (birkaç dakika sürer).
5. İş yeşil tik aldığında üzerine tıklayın; en altta **Asistanim-APK** dosyasını indirin, zip'i açın: `app-debug.apk`.

## Telefona kurma

1. `app-debug.apk` dosyasını telefona gönderin (e-posta, Google Drive veya kabloyla).
2. Dosyaya dokunun. Android "bilinmeyen kaynaklardan yükleme" izni isterse bu dosya için izin verin.
3. **Yükle**'ye basın. Ana ekranda "Asistanım" simgesi çıkar.

## Alternatif: Android Studio

Android Studio'yu kurun → **Open** ile bu klasörü açın → **Build → Build App Bundle(s) / APK(s) → Build APK(s)**.

## Bilmeniz gerekenler

- Uygulamadaki veriler telefonda saklanır; Claude içindeki sayfayla **otomatik eşitlenmez**.
- Sesli komut Android'in konuşma tanımasını (Google), sesli yanıt Android'in sesli okumasını kullanır.
- Claude'a bağlı özellikler (genel sorulara yanıt, ✨ ile metin yazdırma, Instagram verisini güncelleme)
  yalnızca Claude içindeki sayfada çalışır. Uygulamada bunların yerine hazır şablonlar ve temel komutlar kullanılır.
- Sayfayı güncellemek için yeni `index.html` dosyasını `app/src/main/assets/` içine koyup APK'yı yeniden oluşturun.
