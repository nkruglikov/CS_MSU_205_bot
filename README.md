# CS_MSU_205_bot
[Телеграм-бот-помощник 205 группы](https://telegram.me/CS_MSU_205_bot)

Для работы с Telegram API используем [pyTelegramBotAPI](https://github.com/eternnoir/pyTelegramBotAPI)

Pull requests are welcome! 👾

TODO:

- [x] Расписание
- [ ] Доработать интерфейс запроса условий из задачников. Сделать команду, после которой появляется клавиатура с доступными книгами, а после выбора книги дать вводить номер самой задачи. Или оставить как есть? На обсуждение.
- [ ] /now — где, когда, и во сколько ближайшая или текущая пара + писать, сколько осталось до ее начала или "Прямо сейчас" в случае, если она уже идет
- [ ] /timetable — полное расписание, печатать аналогично выдаче по дням
- [ ] Имена преподавателей
- [ ] Домашнее задание
- [ ] Важная информация (Отмена занятий, информация о контрольных, зачетах)
- [ ] Учебные материалы (Книги, методички, листочки)
- [ ] Отдельный бот для администрирования контента основного бота ([Николай Кругликов](https://github.com/nkruglikov))
- [x] Киллер-фича: по учебнику и номеру задачи скидывает ее условия ([Алексей Эльнатанов](https://github.com/InvalidPointer))
- [ ] Распарсить еще пару задачников :3 ([Алексей Эльнатанов](https://github.com/InvalidPointer))
- [ ] Еще более киллер-фича: скидывает написанный билет к экзамену по его номеру.
- [ ] Впилить аналитику бота, чтобы понимать, какими командами будут пользоваться, а какими — нет. Можно заюзать яндексовкий Botan.

Refactoring:

- [ ] Избавиться от hard-coded обработки запроса условий задачи: вынести список задачников и путей к ним в отдельный файл.
- [ ] Оформить исходники так, чтобы любой другой группе было достаточно вписать свои данные и запустить бота на своем сервере.
