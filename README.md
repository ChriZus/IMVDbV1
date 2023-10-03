# PHP wrapper for IMDBv API

## Installation

```json
{
    "require": {
        chrizus/imvdbv1": "dev-master"
    }
}
```

## Usage

```php
require __DIR__ . '/vendor/autoload.php';

$imvdb = new IMVDb\API('');

$result = $imvdb->searchVideo('cheap thrills');
```

## License

MIT License
