# Docker Mail Server

Для удобства и эстетики рекомендуется переименовать родительский каталог в mailserver ^_^

Good luck!
![cat](https://cat.site:83)

## PostgreSQL
[Реляционная база данных]

**Up to date(June 2024) PostgreSQL 14 needs to be updated. End of support in November 2026 may cause critical security issues.**

* Настройки в блоке [PostgreSQL](.env) файла .env

## Exim4
[MTA или агент передачи почты]

* Настройки Exim4 находятся загружаются в файле [exim.conf](volumes/etc/exim4/), объявляются же они в conf.d выше
* Главный для нас конфиг [100.main.conf](volumes/etc/exim4/conf.d/100.main.conf)
* Ключи в папке [dkim](volumes/etc/exim4/dkim) необходимо переименовать

## Dovecot
[Cвободный IMAP и POP3-сервер]

* Версия указана в блоке [Dovecot](.env) файла .env
* Оба конфига лежат по пути volumes/etc/[dovecot](volumes/etc/dovecot/)

## Postfixadmin

* Настройки в блоке [PostfixAdmin](.env) файла .env
* Оба конфига лежат по пути volumes/etc/[postfixadmin](volumes/etc/postfixadmin/)

## Rainloop

* Блок [contacts](volumes/rainloop/data/_data_/_default_/configs/application.ini) в файле application.ini

## Redis

* Настройки в блоке [Redis](.env) файла .env

## Rspam

* Настройки в блоке [Rspam](.env) файла .env
* Путь /build/rsmap/etc/rspamd/

## Clamav
