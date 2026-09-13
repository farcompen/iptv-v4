# Cagan IP TV v0.4

Android / Android TV / TV Box için IPTV oynatıcı.

## v0.4

- v0.3 playlist menüsü ve player düzeltmeleri korunmuştur.
- Android TV / TV Box kumanda kullanımında focus alan playlist kartları daha belirgin hale getirildi.
- Kanal kartları focus aldığında daha açık arka plan, kalın yazı, parlak çerçeve ve hafif büyüme efekti uygulanır.
- Sol kategori menüsünde seçili kategori ile kumandanın o anda focus ettiği kategori ayrı görsel durumlarla gösterilir.
- `Tüm Kanallar` seçimi de aktif/focus durumunu belirgin biçimde gösterir.
- Focus geçişlerinde kısa ölçek animasyonu kullanılır.
- Mevcut çalışan GitHub Actions build yapısı değiştirilmemiştir.

## Remote config

```json
{
  "version": 1,
  "playlists": [
    {
      "name": "Liste 1",
      "url": "https://example.com/list1.m3u",
      "enabled": true
    },
    {
      "name": "Liste 2",
      "url": "https://example.com/list2.m3u",
      "enabled": true
    }
  ]
}
```

GitHub Actions secret adı: `CAGAN_CONFIG_URL`.
