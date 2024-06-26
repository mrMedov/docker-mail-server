# Docker Mail Server

## PostgreSQL
[Реляционная база данных]

**Up to date(June 2024) PostgreSQL 14 needs to be updated. End of support in November 2026 may cause critical security issues.**

* Настройки в блоке [PostgreSQL](.env) файла .env
* 

## Exim4
[MTA или агент передачи почты]

## Dovecot

* Версия указана в блоке [Dovecot](.env) файла .env

## Postfixadmin

* Настройки в блоке [PostfixAdmin](.env) файла .env

## Rainloop

* Блок [contacts](volumes/rainloop/data/_data_/_default_/configs/application.ini) в файле application.ini

## Redis

* Настройки в блоке [Redis](.env) файла .env

## Rspam

* Настройки в блоке [Rspam](.env) файла .env

## Clamav