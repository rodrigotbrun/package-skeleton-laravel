# :package_description

## Installation

```json
{
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/:vendor_slug/:package_slug.git"
        }
    ]
}
```

3. Install it with composer require as usual.

```bash
composer require :vendor_slug/:package_slug
```

## Development

### Composer install

```bash
docker run --rm -v $(pwd):/app composer install
```

### Run tests

```bash
docker run --rm -v $(pwd):/app composer test
```

