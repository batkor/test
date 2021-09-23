---
title: Установка Drupal Composer
slug: /install
tags:
  Drupal Commerce установка
  Drupal установка Интернет Магазина
---
## Требования
- Drupal Commerce работает только на версии Drupal 8.5.0 или выше;
- Рекомендуется установить значение `memory_limit` равным или больше 256Mb в настройках PHP;
- Drupal Commerce устанавливается только через [Composer](https://getcomposer.org/);
- Для PHP необходимо установить расширение [BC Math](https://www.php.net/manual/en/intro.bc.php).

Что бы полностью реализовать все преимущества Drupal Commerce,
вы всегда должны вести разработку локально.

## Новый проект
Следующая команда скачает ядро Drupal + модуль Drupal Commerce и
остальные зависимости в папку `my_store`:
```shell
composer create-project drupalcommerce/project-base mystore --stability dev
```
Установите CMS Drupal как обычно или обратитесь к [Энциклопедии] (https://druki.ru/wiki/9/installation)
Drupal Commerce будет включен автоматически.

Подсказка:
> Папка `bin` содержит любые бинарные исполняемые библиотеки,
> [Drush](https://www.drush.org/latest/),
> [PHPUnit](https://www.drupal.org/docs/automated-testing/phpunit-in-drupal/running-phpunit-tests) и другие.
>
> Папка `web` это `docroot` вашего проекта;
>
> Команды `composer` всегда запускаются из папки вашего проекта `my_store`

change
