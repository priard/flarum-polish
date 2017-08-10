# Polish Language Extension

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/flagrow/masquerade/license.md) [![Latest Stable Version](https://img.shields.io/packagist/v/Veriael/flarum-polish.svg)](https://github.com/Veriael/flarum-polish)

**PL** Polska paczka językowa Flarum. Zawiera:

- Tłumaczenia forum,
- Tłumaczenia panelu administratora,
- Tłumaczenia wszystkich domyślnych rozszerzeń dostarczanych wraz z instalacją Flarum.

**EN** Polish language pack for Flarum. Contains:

- All forum translations,
- Admin control panel (ACP) translations,
- Translations of all default extensions provided with Flarum installation.


### Instalacja

```bash
composer require veriael/flarum-polish
```

### Aktualizowanie

```bash
composer update veriael/flarum-polish
php flarum migrate
php flarum cache:clear
```

### Włączenie

Aby włączyć, wystarczy udać się do panelu administratora, po lewej kliknąć zakładkę "Extensions" i odnaleźć wśród innych rozszerzeń "Język Polski", po czym go zaznaczyć.

Teraz czyścimy cache przeglądarki i gotowe! Możemy wybrać język polski z listy w prawym górnym rogu forum...

...albo ustawiamy język polski jako domyślny dla naszego forum:
Wchodzimy w "Podstawy", później znajdujemy "Domyślny język", wybieramy z listy "Język polski" i zatwierdzamy.


### Przydatne linki

- [changelog](https://github.com/flagrow/masquerade/blob/master/changelog.md)
- [on github](https://github.com/flagrow/masquerade)
- [on packagist](http://packagist.com/packages/flagrow/masquerade)
- [issues](https://github.com/flagrow/masquerade/issues)

