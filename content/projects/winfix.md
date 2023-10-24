+++
title = 'Winfix - Скрипт для исправления багов Windows 10/11'
date = 2023-04-10T15:30:59+05:00
tags = ['Windows 10/11', 'Скрипты']
+++
[Посмотреть на Github](https://github.com/0xd34db100d/winfix)


## Функции
Доступные на данный момент функции:
  * Clipboard - исправление буфера обмена Windows 10/11 (ctrl + c | ctrl + v не работает)! Используйте "Winfix.exe clipboard" в cmd или нажмите на кнопку.
  * Internet - очистка DNS-кэша Windows 10/11, обновление IP, сброс Winsock (проблемы с интернетом)! Используйте "Winfix.exe internet" в cmd или нажмите на кнопку.
  * Explorer - перезапустите explorer.exe (ошибки рабочего стола)! Используйте "Winfix.exe explorer" в cmd или нажмите на кнопку.

В будущем я планирую добавить еще больше функций!
## Установка
Существует два способа установки и использования данного скрипта:
<br>
1. [Скачать со страницы релизов](https://github.com/0xd34db100d/Winfix/releases/) и добавить его в переменные окружения.
2. Установить все зависимости и запустить его с помощью Python 3. 
* Зависимости:
  * readchar (`pip install readchar`)
  * psutil (`pip install psutil`)
  * customtkinter (`pip install customtkinter`)
## Скриншоты
 ![Скриншот](https://i.imgur.com/3G5WfXe.png)
***Сделано с <3***