# Laravel Ru - Перевод компонентов Laravel v10-v11


## Установка
1. Установите репозиторий в .zip формате
2. Распакуйте папку в корень проекта
3. Зайдите в `config/app.php` и в поле `locale` и `faker_locale` укажите `ru`, оставив `fallback_locale` со значением `en`.
4. Выключить сервер, выполнить команду `composer dump-autoload` и включить сервер. 
5. Готово. Не забудьте добавлять в свой `Request` функцию `attributes()` для названия полей!

Рад, если поставите звезду данному репозиторию. Перевод выполнен мною и @MegaSa1nt.


## Кастомные переводы
Если вы хотите добавить кастомные или свои переводы:
1. Создайте PHP файл в папке `lang/ru` (и желательно с переводом в `lang/en` тоже).
2. Добавьте строку `declare(strict_types=1);`.
3. Добавьте `return` и добавляйте в него массив с переводами.
4. Введите в консоль `composer dump-autoload` (может занять некоторое время).
5. Готово!


## Статус работы
| Файл | Статус |
|-----------------|-----------------------------------------------------------|
| `actions`       | <span style="color:green">Завершено ✔️</span>            |
| `auth`          | <span style="color:green">Завершено ✔️</span>            |
| `http-statuses` | <span style="color:green">Завершено ✔️</span>            |
| `pagination`    | <span style="color:green">Завершено ✔️</span>            |
| `passwords`     | <span style="color:green">Завершено ✔️</span>            |
| `validation`    | <span style="color:green">Завершено ✔️</span>            |
