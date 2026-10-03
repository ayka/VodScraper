# VodScraper

Film ve dizileri arayıp **Türkçe altyazıyla** izlemek için Windows uygulaması. LookMovie2 ve Dizipal kaynaklarını
destekler; videolar programın içindeki oynatıcıda açılır.

## İndir

**[Son sürümü indir (Releases)](../../releases/latest)** → `VodScraper-Tasinabilir-1.0.0.zip`

1. Zip'i bir klasöre çıkarın (ör. `Belgeler\VodScraper`).
2. `VodScraperGui.exe` dosyasını çalıştırın. Kurulum gerekmez.

## Gereksinimler

- Windows 10 (1809 ve sonrası) veya Windows 11, 64-bit
- **Microsoft Edge WebView2 Runtime** — Windows 11'de ve güncel Windows 10'larda hazır gelir. Program açılışta
  "Oynatıcı bileşeni eksik" derse [buradan indirin](https://developer.microsoft.com/microsoft-edge/webview2/#download).
- .NET kurmanız gerekmez, program içinde gelir.

## Kullanım

- Üstten kaynak seçin (LookMovie2 / Dizipal), film veya dizi adını yazıp **Ara**.
- Afişe tıklayın: filmlerde **İzle**; dizilerde sezon seçip bölümün yanındaki **İzle**.
- Oynatıcıdaki ⚙ menüsünden ses (ör. Türkçe dublaj / İngilizce), altyazı dili ve kalite seçilir.
  Kaldığınız yer hatırlanır.
- Kısayollar: Boşluk oynat/duraklat, ←/→ 10 sn, ↑/↓ ses, F tam ekran, C altyazı, M sessiz.
- **M3U olarak kaydet** / **Sezonu kaydet**: kayıtlar `Belgeler\VodScraper` klasörüne gider.

## Notlar

- **"Windows kişisel bilgisayarınızı korudu" uyarısı:** Program kod imzalama sertifikasıyla imzalanmadığı için
  SmartScreen bu uyarıyı gösterebilir. **Ek bilgi → Yine de çalıştır** ile açabilirsiniz.
- Videolar programın içinden akar; program kapanınca oynatma da durur.
- Site adresi değişirse (Dizipal sık değişir) `DIZIPAL_URL` ortam değişkeniyle yeni adres verilebilir.

## Üçüncü taraf bileşenler

hls.js (Apache-2.0), libcurl-impersonate (MIT), AngleSharp (MIT), .NET (MIT), Microsoft WebView2.
Ayrıntılar: [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt)
