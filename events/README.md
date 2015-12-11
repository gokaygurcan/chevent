Etkinlik Eklemek
================

- Bu repository'yi forklayın
- events.json dosyasına etkinliği ekleyin

```javascript
{
  "name": "",        // (String)  (Zorunlu)   Etkinlik ismi
  "date": "",        // (String)  (Zorunlu)   Etkinliğin gerçekleşeceği tarih (gg.aa.yyyy)
  "free": true,      // (Boolean) (Zorunlu)   Etkinlik ücretsiz ise `true`, değilse `false` girin
  "image": "",       // (String)  (Zorunlu)   Etkinliğin görseli
  "url": "",         // (String)  (Zorunlu)   Kayıt ve detaylı bilgilerin bulunduğu link
  "description": "", // (String)  (Zorunlu)   Etkinlik hakkında birkaç cümleyi geçmeyecek açıklama
  "quota": "",       // (Number)  (Opsiyonel) Etkinlikte katılımcı sınırı var mı? Varsa kaç kişi?
  "speakers": [      // (Array)   (Opsiyonel) Konuşmacı listesi ve konu başlıkları
    {
      "name": "",    // (String)  (Zorunlu)   Konuşmacının ismi
      "subject": "", // (String)  (Opsiyonel) Konu başlığı
    },
    ...
  ],
  "location": {      // (Object)  (Opsiyonel) Etkinliğin yapılacağı yere ait konum bilgisi
    "latitude": 0.0  // (Number)  (Zorunlu)   Enlem
    "longitude": 0.0 // (Number)  (Zorunlu)   Boylam
  }
},
...
```

- Pull request gönderin :)
