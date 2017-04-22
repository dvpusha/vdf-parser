## KeyValue encoder/decoder for various languages

Format: https://developer.valvesoftware.com/wiki/KeyValues

VDF may contain comments. However, they are not preserved during decoding.

### Installation Via Composer

Add the dependency:

```bash
composer require pusha/laravel-webmoney
```

### Usage

```php
use Pusha\VDFParser\VDF;

VDF::decode();
VDF::encode();
```

### License

See [license](LICENSE) file.