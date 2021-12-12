# chatroom-react-test
Тестовое задание на React разработчика

## Описание приложения

Приложение Chat Room позволяет пользователю общаться с другими пользователями в приватном чате

## Стек технологий

- React
- Node
- Socket.io
- Bootstrap

## Запуск приложения

Для запуска приложения необходимо сделать следующее:

- Клонировать репозиторий

- Установить общие зависимости, а также зависимости сервера и клиента

- Выполнить команды запуска сервера, находясь в директории /server и /client поочередно

## Использование приложения

*Приложение еще находится в разработке*

Создание чата:

- После запуска клиента, перейти на начальную страницу (localhost:PORT/)

- Указать имя и нажать кнопку New Chat или клавишу Enter

- Будет создана новая комната, после чего в форме отобразится id новой комнаты

- Нажать кнопку New Chat или клавишу Enter

- Начать общаться

Приглашение пользователя:

- Передать другому пользователю строку адреса с указанием id комнаты (localhost:PORT/ROOM_ID)

- Другой пользователь должен сначала зайти на начальную страницу (localhost:PORT/), после чего вбить в строку браузера, переданную ссылку выше (localhost:PORT/ROOM_ID)

- В форме логина должно отобразиться поле с нужным id комнаты

- Указать имя и нажать кнопку Enter Chat или клавишу Enter

- Начать общаться