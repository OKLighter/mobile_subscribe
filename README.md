# mobile_subscribe
Тестовое задание по Python

1. Создать базу данных mobile.db
2. Создать таблицу mobile_users с колонками UserID (INTEGER), User_name (Text), Balance (INTEGER),
Mobile_tariff_ref (INTEGER), Activity (Text)
3. Создать таблицу mobile_tariff с колонками TariffID (INTEGER), Tariff (Text), Price (INTEGER)
4. Заполнение таблицы mobile_users:
    User1, 10000, 2, Yes
    User2, 10000, 3, Yes
    User3, 10000, 1, Yes
5. Заполнение таблицы mobile_tariff:
    1, Standard, 500
    2, VIP, 1000
    3, Premium, 1500

6. Задача кода производить ежемесячное списание денежных средств с баланса пользователей, в размере тарифа,
пока Статус колонки Activity = Yes. Как только на балансе пользователя недостаточно денежных средств для списания,
то Статус колонки Activity становится = No, и операции по данному пользователю больше не проводятся
7. Количество месяцев определяется вводом числа в консоль, через input()
8. Предусмотреть проверку на достаточную величину баланса, оповещение о недостаточности денежных средств,
невозможности уйти в минус.
9. Код в консоли должен начинаться с фразы "Введите период расчета: "
10. Добавить все необходимые проверки и добавить сообщения об успешной операции, ошибках и т.д.