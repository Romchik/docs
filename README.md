Laravel 5
====

Документация на русском языке. Перевод официальной документации [https://github.com/laravel/docs](https://github.com/laravel/docs).

## Соглашения о формате

В начале каждого файла должна быть конструкция вида 

	git a49894e56c3ac8b837ba7d8687d94f6010cb1808

	---

где `a49894e56c3ac8b837ba7d8687d94f6010cb1808` - полный номер коммита в официальной англоязычной документации, последнего актуального на момент редактирования для данного файла. 
Историю коммитов для заданного файла можно смотреть так:

`https://github.com/laravel/docs/commits/4.1/facades.md`

Здесь 4.1 - имя ветки (`master`, `4.1`, `4.0`), а facades.md - название файла.

## Соглашение о терминах

Термины, встречающиеся в документации, переводим, если для них есть четкий устоявшийся перевод (например cache - кэш). Если есть сомнения (например, Service provider, Response или Input) - оставляем как есть. И каждый термин, переведенный или нет, оформляем в двойные скобки - например, `((кэш))` , `((сервис провайдер))`, `((route))`. На сайте в этих местах будет добавлен попап с подробной расшифровкой термина.

