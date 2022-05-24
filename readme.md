# LogicProxy

Скрипт для проксирования серверов в случае блокировки.

## Для пользователей

Вам не сюда, вы ошиблись местом, наверное вы искали [это](https://github.com/LogicWorlds/LogicProxyInstaller/tree/main/).

## Для собственного хостинга скриптов(Pro LVL)

Устанавливаем node.js, клонируем репозиторий и выполняем действия ниже.

Перед выполнением скриптов прописываем:

```sh
sudo chmod +x start.sh delete.sh reload.sh
```

Для запуска выполняем:

```sh
./start.sh
```

Для отключения:

```sh
./delete.sh
```

Перезагрузка:

```sh
./reload.sh
```

А дальше уже на стороне клиента прописываем в hosts адресс сервера.  
Или модифицируем скрипы в папке client-script на адресс вашего сервера.
