# Описание проекта
Вы работаете в стартапе, который продаёт продукты питания. Нужно разобраться, как ведут себя пользователи вашего мобильного приложения.

Необходимо разобраться в поведении пользователей приложения, которое продает продукты питания. 
 - Для того, чтобы понять путь клиента до совершения покупки и узнать долю людей, которые «не отваливаются» и переходят на каждый следующий этап этого пути, необходимо изучить воронку продаж;
 - Также, необходимо исследовать результаты A/A/B-эксперимента. Дизайнеры захотели поменять шрифты во всём приложении, а менеджеры испугались, что пользователям будет непривычно. Договорились принять решение по результатам A/A/B-теста. Пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную — с новыми.
# Описание данных

**Структура — `/datasets/logs_exp.csv`**

- `EventName`	— название события
- `DeviceIDHash` — уникальный идентификатор пользователя
- `EventTimestamp` —	время события
- `ExpId` —  номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная
