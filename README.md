# 🤖 Buddy

Bilgisayarında **yerel** çalışan, masaüstünde gezen bakır robot asistan. Sohbet eder, sesini duyar, düşünür, rüya görür, işlerini takip eder; istersen senin **kendi** Claude / ChatGPT hesabınla büyük işleri yaptırır.

## İndir

| Platform | İndir |
|---|---|
| 🍎 Mac (Apple Silicon: M1/M2/M3/M4, macOS 13+) | [Buddy-mac-arm64.zip](https://github.com/ozguracar-eliar/buddy/releases/latest/download/Buddy-mac-arm64.zip) |
| 🪟 Windows | yakında |
| 🤖 Android | yakında |

## Kurulum (Mac)

1. Zip'i aç, **Buddy**'yi **Uygulamalar** klasörüne sürükle.
2. İlk açılışta: Buddy'ye **sağ tık → Aç**. “Açılamıyor” uyarısı çıkarsa: **Sistem Ayarları → Gizlilik ve Güvenlik** → en altta **Yine de Aç**. (Uygulama Apple imzalı değil; bu uyarı bir kez çıkar.)
3. Hoş geldin ekranında beyin (~1,2 GB) iner. Ses tanıma (~575 MB) ilk sesli konuşmada, görme (~670 MB) ilk resimde iner. Dosyalar resmi kaynaktan (Hugging Face) iner ve parmak iziyle doğrulanır.

Gereken: ~3 GB boş disk, 8 GB+ RAM önerilir.

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
