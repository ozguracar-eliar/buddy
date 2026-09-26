# 🤖 Buddy

Bilgisayarında **yerel** çalışan, masaüstünde gezen bakır robot asistan. Sohbet eder, sesini duyar, düşünür, rüya görür, işlerini takip eder; istersen senin **kendi** Claude / ChatGPT hesabınla büyük işleri yaptırır.

## İndir

| Platform | İndir |
|---|---|
| 🍎 Mac (Apple Silicon: M1/M2/M3/M4, macOS 13+) | [Buddy-mac-arm64.zip](https://github.com/ozguracar-eliar/buddy/releases/latest/download/Buddy-mac-arm64.zip) |
| 🍏 Mac (Intel işlemcili, macOS 13+) | [Buddy-mac-x64.zip](https://github.com/ozguracar-eliar/buddy/releases/latest/download/Buddy-mac-x64.zip) |
| 🪟 Windows 10/11 (64 bit) | [Buddy-Setup.exe](https://github.com/ozguracar-eliar/buddy/releases/latest/download/Buddy-Setup.exe) (kurulum) · [zip](https://github.com/ozguracar-eliar/buddy/releases/latest/download/Buddy-windows-x64.zip) |
| 🤖 Android 9+ (64 bit, 6 GB+ RAM) | [Buddy-android.apk](https://github.com/ozguracar-eliar/buddy/releases/latest/download/Buddy-android.apk) |

## Kurulum (Mac)

1. Zip'i aç, **Buddy**'yi **Uygulamalar** klasörüne sürükle.
2. İlk açılışta: Buddy'ye **sağ tık → Aç**. “Açılamıyor” uyarısı çıkarsa: **Sistem Ayarları → Gizlilik ve Güvenlik** → en altta **Yine de Aç**. (Uygulama Apple imzalı değil; bu uyarı bir kez çıkar.)
3. Hoş geldin ekranında beyin (~1,2 GB) iner. Ses tanıma (~575 MB) ilk sesli konuşmada, görme (~670 MB) ilk resimde iner. Dosyalar resmi kaynaktan (Hugging Face) iner ve parmak iziyle doğrulanır.

Gereken: ~3 GB boş disk, 8 GB+ RAM önerilir.

## Kurulum (Windows)

1. **Buddy-Setup.exe**'yi çalıştır (yönetici izni gerekmez). İstersen zip'i bir klasöre çıkarıp Buddy.exe'yi de çalıştırabilirsin. Ek bir şey kurman gerekmez.
2. “Windows bilgisayarınızı korudu” uyarısı çıkarsa: **Ek bilgi → Yine de çalıştır** (uygulama imzalı değil).
3. İlk açılışta tarayıcıda hoş geldin ekranı açılır, beyin iner.
4. Robota tıkla → yaz; robota ya da **Sağ Ctrl**'e basılı tut → konuş. Görev çubuğundaki simge → menü.

Windows'ta henüz olmayanlar: ekranı okuma/tıklama, Mail, beceriler, Telegram sesli mesajları, telefondan bağlanma.

## Kurulum (Android)

1. APK'yı telefonda indir ve aç. “Bu kaynaktan uygulama yüklemeye izin ver” sorarsa izin ver → **Yükle**.
2. Açılınca mikrofon ve bildirim izni ister; beyin (~1,2 GB) iner — Wi-Fi'de olman iyi olur.
3. 🎙'ye dokun ve konuş; 🗂 ile ajanda, hesaplar ve Telegram ayarları.

Android'de henüz olmayanlar: bilgisayar/telefon yönetme, beceriler; Claude/ChatGPT yalnızca API anahtarıyla.

## Neler yapar

- **Sohbet ve düşünme:** yerel Qwen3.5 2B modeli; gerektiğinde önce düşünür.
- **Ses:** robota ya da seçtiğin tuşa basılı tut, konuş. Ses bilgisayardan çıkmaz.
- **Sekreter:** “yapılacaklara ekle: raporu gönder yarın 15'te”, hatırlatmalar, sabah özeti, akşam değerlendirmesi.
- **Hafıza ve öğrenme:** kendinden bahsettikçe not alır (“📝 Not aldım”), “yanlış, sil” ile geri alırsın.
- **Rüya:** gece günü toparlar, sabah anlatır.
- **Bilgisayarı yönetme:** uygulama açma, ekranı okuma, tıklama (izin verirsen).
- **Telefon:** aynı Wi-Fi'de telefondan robotu görüp sesle konuş; ya da kendi Telegram botunla (QR ile kurulum), sesli mesaj dahil.
- **Güncelleme:** yeni sürüm çıkınca haber verir, onaylarsan kendini günceller.

## Claude / ChatGPT (isteğe bağlı)

Buddy kimsenin hesabını paylaşmaz; herkes **kendi** hesabını **Hesaplar** sekmesinden bağlar:

- **Aboneliğinle** (Claude Pro/Max, ChatGPT Plus): “Aracı kur” → “Tarayıcıda giriş yap”. Hesabın yoksa [claude.ai](https://claude.ai) / [chatgpt.com](https://chatgpt.com).
- **API anahtarınla** (kullandıkça öde): anahtar yalnızca senin bilgisayarında saklanır.
- **Hiçbiri:** Buddy tamamen yerel çalışır.

## Gizlilik

Konuşmaların, hafızan ve ayarların yalnızca bilgisayarında (`~/Library/Application Support/Buddy`) durur. İnternete yalnızca şunlar için çıkar: model indirme, güncelleme kontrolü, (bağlarsan) Telegram ve kendi Claude/ChatGPT hesabın.
