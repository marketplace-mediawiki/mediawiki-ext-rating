# Information / Информация

Интеграция рейтинга в статью.

## Install / Установка

1. Загрузите папки и файлы в директорию `extensions/MW_EXT_Rating`.
2. В самый низ файла `LocalSettings.php` добавьте строку:

```php
wfLoadExtension( 'MW_EXT_Rating' );
```

## Syntax / Синтаксис

```html
{{#rating: title = [TITLE]
  |count = [NUMBER]
  |icon-plus = fas fa-[ICON]
  |icon-minus = fas fa-[ICON]
}}
```

## Donations / Пожертвования

- [Donation Form](https://donation-form.github.io/)
