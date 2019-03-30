# File manager for laravel-admin

File manager for Cloud Storage.

## Screenshot

![wx20170809-170104](https://user-images.githubusercontent.com/1479100/29113762-99886c32-7d24-11e7-922d-5981a5849c7a.png)

## Installation

```bash
composer require jxlwqq/file-manager
```

Add a disk config in `config/admin.php`:

```php
'extensions' => [
    'file-manager' => [
           // Select a local disk that you configured in `config/filesystem.php`
           'disk' => 'public'
    ],
],
```


Open `http://localhost/admin/file-manager`.

License
------------
Licensed under [The MIT License (MIT)](LICENSE).
