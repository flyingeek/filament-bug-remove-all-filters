# Filament Bug Report

## Installation

```sh
git checkout git@github.com:flyingeek/filament-bug-report.git

composer install

touch database/database.sqlite

php artisan migrate:fresh --seed

php artisan serve
```

## Steps to reproduce

- open http://127.0.0.1:8000/admin/users
- try to deactivate the filter

![Screenshot](docs/screenshots/filter-close-button-not-working.jpg "Remove a filter")
