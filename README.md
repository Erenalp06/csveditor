# CSV Editör

GitHub Pages üzerinde doğrudan çalışan, CSV verisini yapıştırarak tablo halinde görüntülemek için basit bir web uygulaması.

## Özellikler

- Sol panele CSV yapıştırınca anlık tablo önizlemesi
- Virgül, noktalı virgül, sekme ve dikey çizgi ayraçlarını otomatik algılama veya elle seçme
- Tırnak içindeki ayraçları, çift tırnakları ve bir hücre içindeki satır sonlarını doğru işleme
- Başlık satırı, satır/sütun sayısı ve kaydırılabilir tablo
- Büyük verilerde ilk 400 satır, istenirse devamını gösterme
- Tabloyu Excel/Sheets'e yapıştırmaya uygun sekmeli metin olarak kopyalama
- Tamamen istemci tarafında çalışma; CSV verisi hiçbir sunucuya gönderilmez

## GitHub Pages üzerinde yayınlama

1. `index.html` dosyasını `Erenalp06/csveditor` deposunun **main** dalına, kök dizine yükleyin (Add file → Upload files → Commit changes).
2. GitHub'da **Settings → Pages** bölümüne girin.
3. **Build and deployment → Source: Deploy from a branch** seçin.
4. **Branch: main**, **Folder: /(root)** seçeneklerini belirleyip **Save** deyin.
5. Yayın tamamlandığında adres: https://erenalp06.github.io/csveditor/

Uygulama tek bir HTML dosyasıdır. Node.js, npm, backend, build işlemi veya API anahtarı gerektirmez.

## Lokal kullanım

`index.html` dosyasına çift tıklayarak tarayıcıda açabilirsiniz.

## Güvenlik

CSV verisi tarayıcıda işlenir ve ağ üzerinden yüklenmez. Hücreler HTML olarak yorumlanmaz; düz metin olarak gösterilir.