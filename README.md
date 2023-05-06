# 9.2 «Кеширование Redis/memcached» - `Акиньшин С.Г.`

### Задание 1

Кеширование может помочь ускорить доступ к данным в базах данных и уменьшить нагрузку на серверы баз данных. Некоторые примеры проблем, которые могут быть решены с помощью кеширования в базах данных:

Частые запросы к базе данных: Если приложение часто запрашивает одни и те же данные из базы данных, кеширование может сократить время ответа, избежав необходимости каждый раз отправлять запрос к базе данных.

Нагрузка на сервер базы данных: Кеширование может помочь уменьшить нагрузку на сервер базы данных, так как приложение будет использовать кеш вместо отправки запросов к базе данных. Это может снизить нагрузку на базу данных и сократить время ответа.

Медленный доступ к данным: Если доступ к данным в базе данных занимает много времени, кеширование может помочь ускорить доступ к данным. Кеш может содержать копию данных, которые могут быть быстро извлечены и предоставлены приложению, сокращая время ответа.

Повторное использование запросов: Кеширование может помочь избежать повторного выполнения тех же самых запросов к базе данных, сохраняя результаты в кеше и предоставляя их в будущем. Это может уменьшить нагрузку на базу данных и ускорить выполнение запросов.

Высокая нагрузка на сеть: Если приложение работает на удаленном сервере, кеширование может помочь уменьшить нагрузку на сеть, так как данные могут быть загружены в кеш один раз и предоставлены приложению без необходимости повторной загрузки через сеть.


### Задание 2

1. `Установил memcached`
2. `Записал ключи`


![JPG](https://github.com/akinya1974/REDIS_Memcached/blob/main/JPG/status%20memcached.jpg)

![JPG](https://github.com/akinya1974/REDIS_Memcached/blob/main/JPG/Ключ.jpg)

![JPG](https://github.com/akinya1974/REDIS_Memcached/blob/main/JPG/Ключ-2.jpg)

### Задание 3

1. `Установил Redis`
2. `Записал данные`

![JPG](https://github.com/akinya1974/REDIS_Memcached/blob/main/JPG/status%20redis.jpg)

![JPG](https://github.com/akinya1974/REDIS_Memcached/blob/main/JPG/Redis%20key.jpg)

### Задание 4

1. `Работа с числами`

![JPG](https://github.com/akinya1974/REDIS_Memcached/blob/main/JPG/key5.jpg)