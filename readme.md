`sxrcan.db` Türkçe veritabanı modülüdür.
 BSON, JSON ve Yaml üzerine kurulmuştur.

-

`sxrcan.db` Modülünü kurmak için aşağıda bulunan kodu terminale yazın.

```shell
> npm i sxrcan.db@latest
```

Kurulumdan sonra Modülü hangi veritabanı stilinde kullanıcağınızı seçin.

-

```javascript
const { BsonDatabase,JsonDatabase,YamlDatabase } = require("sxrcan.db");

const db = new YamlDatabase();
```

Paket otomatik olarak `sercdb.<Veritabanı Uzantısı>` dosyası oluşturacaktır.


