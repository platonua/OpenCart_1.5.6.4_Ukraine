# Модуль OpenCart 1.5.6.4 для Украины

## Установка:

* Распаковать архив в корень сайта.

* В админ панеле перейти Extensions → Payments → Platon.

* Нажите "Install", потом "Edit".

* В настройках указать ключ и пароль. Настройте статусы транзакций Pending для Order Status и Refunded как Refunded Order Status.

* Установить значение платежного метода в статус Enabled.

## Ссылка для коллбеков:
https://ВАШ_САЙТ/index.php?route=payment/platon/callback

## Тестирование:
В целях тестирования используйте наши тестовые реквизиты.

| Номер карты  | Месяц / Год | CVV2 | Описание результата |
| :---:  | :---:  | :---:  | --- |
| 4111  1111  1111  1111 | 02 / 2022 | Любые три цифры | Не успешная оплата без 3DS проверки |
| 4111  1111  1111  1111 | 06 / 2022 | Любые три цифры | Не успешная оплата с 3DS проверкой |
| 4111  1111  1111  1111 | 01 / 2022 | Любые три цифры | Успешная оплата без 3DS проверки |
| 4111  1111  1111  1111 | 05 / 2022 | Любые три цифры | Успешная оплата с 3DS проверкой |
