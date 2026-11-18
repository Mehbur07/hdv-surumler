# Hadi Ders Vakti — Kurulum Rehberi

Hadi Ders Vakti (HDV), ortaokul öğrencileri için Windows'ta çalışan bir ders çalışma
planlayıcısıdır. Okul ders programına göre haftalık çalışma planı hazırlar, konuları takip eder,
yapay zekâ ile konu anlatır ve test yapar.

## 1. İndir

👉 **[HDV-Kurulum.exe'yi indir](https://github.com/Mehbur07/hdv-surumler/releases/latest/download/HDV-Kurulum.exe)**
(yaklaşık 120 MB, Windows 10 ve 11)

Tarayıcı "Bu dosya yaygın olarak indirilmiyor" derse **⋯ → Sakla → Yine de sakla** seç.

## 2. Kur

1. İndirilen `HDV-Kurulum.exe` dosyasına çift tıkla.
2. Mavi bir **"Windows bilgisayarınızı korudu"** penceresi çıkabilir. Bu, uygulamanın ücretli bir
   dijital imzası olmadığı için çıkar; virüs olduğu anlamına gelmez.
   - **Ek bilgi**'ye tıkla.
   - Altta çıkan **Yine de çalıştır** düğmesine bas.
3. Kurulum kendiliğinden biter (yönetici şifresi istemez) ve uygulama açılır. Masaüstüne ve Başlat
   menüsüne **Hadi Ders Vakti** kısayolu eklenir.

## 3. İlk açılış

- Sihirbaz adını, sınıfını, okul türünü ve ders programını sorar. Ders programını elle girebilir
  ya da fotoğrafından okutabilirsin (fotoğraf için Gemini anahtarı gerekir).
- Konu anlatımı, test ve fotoğraftan okuma için **Ayarlar → Yapay zekâ (Gemini)** bölümüne ücretsiz
  bir Google Gemini anahtarı girmen gerekir. Ayarlar'daki rehber adım adım anlatır (18 yaşından
  küçüksen bir velinle birlikte al).

## Güncellemeler

Uygulama açıkken yeni sürüm olup olmadığına kendisi bakar ve arka planda indirir. Hazır olunca
bildirim gelir; uygulamayı kapatınca kurulur. İstersen **Ayarlar → Güncellemeler → Yeniden başlat
ve kur** ile hemen kurabilirsin. Verilerin güncellemede silinmez.

## Bilmen gerekenler

- **Pencereyi kapatınca** uygulama, bildirim gönderebilmek için saatin yanındaki simgede (sistem
  tepsisi) çalışmaya devam eder. Tamamen kapatmak için simgeye sağ tıklayıp **Çıkış** de. Bunu
  istemezsen **Ayarlar → Bildirimler** bölümünden kapatabilirsin.
- **Verilerin** yalnızca senin bilgisayarında, `%APPDATA%\Hadi Ders Vakti` klasöründe tutulur.
  Yapay zekâya adın ya da okulun gönderilmez.
- **Kaldırmak için:** Windows Ayarları → Uygulamalar → Yüklü uygulamalar → **Hadi Ders Vakti** →
  Kaldır. Verilerin silinmez; tamamen silmek istersen yukarıdaki klasörü de sil.

## Sorun mu var?

- **Uygulama açılmıyor:** Saatin yanındaki simgelere bak (⌃ okuna tıkla); uygulama orada açık
  olabilir. Simgeye tıklayınca pencere açılır.
- **Bildirim gelmiyor:** Windows Ayarları → Sistem → Bildirimler bölümünde **Hadi Ders Vakti**'nin
  açık olduğundan ve "Rahatsız etmeyin" modunun kapalı olduğundan emin ol. Ayarlar →
  Bildirimler → **Deneme bildirimi gönder** ile deneyebilirsin.
- **Antivirüs dosyayı engelledi:** İmzasız yeni uygulamalarda olabilir. Dosyayı yalnızca yukarıdaki
  bağlantıdan indirdiysen antivirüste "izin ver / güvenilir" seçebilirsin.

---

Bu repo yalnızca Hadi Ders Vakti'nin kurulum dosyalarını ve güncellemelerini dağıtmak içindir.
Tüm sürümler: [Releases](https://github.com/Mehbur07/hdv-surumler/releases)
