# Скрипт для добавления/очистки/удаления пользователей в файловой системе приложения WebTours 1.0

### Перед использованием
- установите все необходимые библиотеки для python (файл requirements.txt прилагается)
> py -m pip install -r requirements.txt
- синхронизируйте заголовки пользователей с Users.dat файлом основого скрипта VUgen &ensp; (требует настройки самого скрипта LOGIN, PWD и тд.)

## Примеры использования
создать 100 файлов пользователей с автоматической генераций логина/пароля/имени/фамилии и др. данных (симуляций ручного создания аккаунта в WebTours):
> ```py user.py -add 100```

очистить данные всех бронирований текущих пользователей (начальные данные пользователей: логин/пароль и тд. будут сохранены)
> ```py user.py -clear y```

удалить всех пользователей в системе
> ```py user.py -rmall y```

возможно использование сразу 2 ключей при вызове скрипта: пример - удаление старых аккаунтов/добавление 100 файлов пользователей
> ```py user.py -rmall y -add 100```

*файл аккаунта jojo не будет тронут ни в одной из операций*

ps Thanks Nikolay Batalin for support
