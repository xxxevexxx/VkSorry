### VKSorry | LP module
>VKSorry module позволяет управлять разными функциями VK из любого чата.
---
## Навигация
1. [Переменные](#Переменные)
2. [Установка](#Установка)
3. [Команды](#Команды)
>Все ссылки кликабельны.
---
## Переменные
|  *  | Переменная   |     Описание     |  *  |
|:---:|--------------|:----------------:|:---:|
|  *  | `{USER}`     |  Реплай:Ссылка   |  *  |
|  *  | `{PASS}`     |   Пароль от VK   |  *  |
|  *  | `{LOGIN}`    |   Логин от VK    |  *  |
|  *  | `{ENTER}`    |  Перенос строки  |  *  |
|  *  | `{PARAMS}`   |     Параметр     |  *  |
|  *  | `{COMMAND}`  |     Команда      |  *  |
|  *  | `{CPREFIX}`  |  Префикс команд  |  *  |
|  *  | `{SPREFIX}`  | Префикс скриптов |  *  |
|  *  | `{TOKENVKA}` |  Токен VKAdmin   |  *  |
|  *  | `{TOKENVKS}` |  Токен VKSorry   |  *  |
* [⬆️Навигация](#Навигация)
---
# Установка
## Получаем токен [VKAdmin](https://vk.cc/9NCoPi).
- Листаем в самый низ, нажимаем [Разрешить].
- Копируем то-что находится в URL адресе страницы.
### Переходим в личные сообщения с [группой](https://vk.com/lpvks).
- Пишем - `/create`
- - Получаем - ✅ &#60;VKSLP Module&#62; Session created.
- Пишем - `/vka {ENTER} {TOKENVKA}`
- - Получаем - ✅ &#60;VKSLP Module&#62; Token VKA updated.
- Пишем - `/restart`
- - Получаем - ✅ &#60;VKSLP Module&#62; Session restarted.
### Проверяем - `{CPREFIX}` инфо

## Получаем токен [VKSorry](https://vk.com/lpvks).
- Отключаем 2Хфакторную аутентифиакцию.
- Вспоминаем логин и пароль от страницы.
### Переходим в личные сообщения с [группой](https://vk.com/lpvks).
- Пишем - `/stop`
- - Получаем - ✅ &#60;VKSLP Module&#62; Session stopped.
- Пишем - `/vks {ENTER} {LOGIN} {ENTER} {PASS}`
- - Получаем - ✅ &#60;VKSLP Module&#62; Token VKS updated.
- Пишем - `/restart`
- - Получаем - ✅ &#60;VKSLP Module&#62; Session restarted.
### Проверяем - `{CPREFIX}` инфо
* [⬆️Навигация](#Навигация)
---
## Команды
- [ ] [Скрипты](#Скрипты)
  * [Информация](#Информация-скриптов)
  * [Статистика](#Статистика-скриптов)
- [ ] [Функции](#Функции)
  * [Информация](#Информация-аккаунта)
  * [Статистика](#Статистика-аккаунта)
* [⬆️Навигация](#Навигация)
---
## Скрипты
### Информация скриптов
- `{SPREFIX}` __инфо__ - Информация о состоянии скриптов
>Отображает состояние скриптов
### Статистика скриптов
- `{SPREFIX}` __стата__ - Статистика работы скриптов
>Отображает количество выполненых действий
### Автолайк
- `{SPREFIX}` __автолайк__ - Включает/Выключает Автолайк
>Лайкает ленту уведомлений
### Автоприем
- `{SPREFIX}` __автоприем__ - Включает/Выключает Автоприем
>Принимает заявки в друзья
### Автоуведомления
- `{SPREFIX}` __автоуведы__ - Включает/Выключает Автоуведомления
>Ставит уведомления по комментарию
### Автоотписка
- `{SPREFIX}` __автоотп__ - Включает/Выключает Автоотписка
>Отклоняет отправленные заявки
### Автопилот
- `{SPREFIX}` __автопилот__ - Включает/Выключает Автопилот
>Сочитает в себе несколько скриптов
### Авторекомендации
- `{SPREFIX}` __автореки__ - Включает/Выключает Авторекомендации
>Отправляет заявки рекомендованным друзьям
### Автостатус
- `{SPREFIX}` __автостатус__ - Включает/Выключает Автостатус
>Автоматически меняет статус
### Автоонлайн
- `{SPREFIX}` __автоонл__ - Включает/Выключает Автоонлайн
>Всегда отображает онлайн страницы
### Автооффлайн
- `{SPREFIX}` __автоофл__ - Включает/Выключает Автооффлайн
>Всегда отображает оффлайн страницы
* [⬆️Навигация](#Навигация)
---
## Функции
### Информация аккаунта
- `{CPREFIX}` инфо - _Профиль аккаунта в боте_
### Статистика аккаунта
- `{CPREFIX}` стата - _Статистика аккаунты_
>Тут должно быть что-то написано
* [⬆️Навигация](#Навигация)


