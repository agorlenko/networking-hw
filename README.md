### Задание:

Из 5 unit-тестов были удалены или исправлены некоторые строки(в таких местах проставлены TODO-шки).

Необходимо их починить, при этом не трогая любой другой код(aka read-only код), не отмеченный todo-шками.

Тесты проверяют конкретную функциональность или всю схему целиком(как например NIO и AIO).

В комментариях к TODO-шкам даются пояснения к реализации удалённой логики.

### Формат сдачи:

* fork-нуть себе этот репозиторий
* сделать его приватным(у гитхаба нет простой кнопки для этого, поэтому придётся сделать дупликат репозитория из консоли(см. ссылку "duplicate" в настройках форченного репозитория))
* добавить меня в collaborators вашего приватного репозитория(НЕ ФОРЧЕННОГО!)
* починить тесты, закомитить изменения в отдельную ветку, создать PR и назначить меня ревьюером

### Критерии оценки:

0 баллов, если ошибка при команде: `mvn clean test`

-2 за тест, если изменён read-only код

+1 балл, если тест проходит

+1 балл, если тест принят на ревью

Итого, 5 тестов, оценка от -10 до 10.

### Дедлайн:

10.02.2019 включительно