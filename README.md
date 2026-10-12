# ECG Recorder açıklama sayfası

Türkçe, mobil uyumlu statik site. `index.html` doğrudan açılabilir. HTML, CSS ve JavaScript dışında çalışma zamanı veya kurulum gerektirmez.

## Önizleme

Proje klasöründe `python3 -m http.server 8876` çalıştırın. Ardından `http://localhost:8876` adresini açın.

## İçerik kaynakları

- TÜSEB 2026-B2 kapsamlı başvuru formu
- Başvuru eki: patlatılmış görünümler PDF'i
- https://cardiapp26.github.io/ecg-ble/crowpanel/ (12 Ekim 2026 tarihinde incelendi)

Formdaki tasarım ve kabul hedefleri, tamamlanmış özelliklerden ayrı sunulur. Site bir başvuru projesini açıklar; destek onayı veya klinik ürün onayı iddiası içermez. PDF yerel olarak kopyalandı, çizimlerin PNG önizlemeleri PDF'den oluşturuldu. Başvuru DOCX'i siteye dağıtılmadı.

## Yayınlama

`index.html`, `style.css`, `app.js` ve `assets/` klasörünü aynı yapıyla statik sunucuya veya GitHub Pages deposuna yükleyin. Sayfa göreli dosya yolları kullanır ve alt dizinde çalışır. Mevcut kayıt arayüzüne dış bağlantı verir.
