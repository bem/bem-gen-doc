Сам по себе пользовательского функционала не имеет, использовать нужно различные его модификации.

В общем виде работа с блоком осуществляется следующим образом:

1. С помощью `BEM.create(name, params)` создаем инстанс блока нужной модификации.
2. В момент создания вторым параметром передаем базовые параметры инстанса.
3. Используем полученный инстанс многократно, при необходимости переопределяя/доопределяя базовые 
параметры для конкретного запроса.