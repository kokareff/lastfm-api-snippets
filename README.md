lastfm-api-snippets
===================

Пара забавных скриптов, использующих API last.fm

### Начало использования

Чтобы начать использовать - зайдите на страницу http://www.lastfm.ru/api/account/create, зарегистрируйтесь, получите api_key и добавьте его в config.

### Сравнение списков артистов

Дальше можно просто запустить ./compare.sh <user1> <user2>, например:

````
./compare.sh panzersoldat <ваш_никнейм>
````

и вы увидите, насколько совпадают наши вкусы, с полным списком прослушанных нами обоими артистов.
