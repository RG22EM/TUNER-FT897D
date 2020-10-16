# TUNER-FT897D Альфа версия
Коплект библиотек и пример скетчей для имитации устройств подключаемых к трансиверам марок YAESU FT-817/ FT-857/ FT-897 по CAT интерфейсу, работает как по HARDWARE так и SOFTWARE SERIAL.
Этот проект не состоялся бы если сообщество, в том числе радиолюбительское не проделало конкретные шаги по написанию улучшенных библиотек по работе с SoftWare серийными портами - CustomSoftwareSerial.h от Thuc Le https://github.com/ledongthuc/CustomSoftwareSerial, билиотеке оболочке для библиотек работающих с SoftWare, HardWare и USB_Serial портами - SomeSerial от Asuki Kono - https://github.com/asukiaaa/SomeSerial, тщательно переработанной Дмитрием -DetSimen  - https://github.com/DetSimen/FT879D библиотеки от  Author:  James Buck, VE3BUX   Web:  http://www.ve3bux.com, впервые библиотека была адаптирована UA6EM под версию ARDUINO IDE 1.8.Х.
Комплект библиотек позволит реализовать для трансиверов этих марок панель удалённого управления.
Развитие проекта видится в этом направлении.
# Особенности
Имена библиотек имеющих несовметимые отличия от оригинальных изменены!!!
# Установка
Просто скопируйте и разархивируйте библиотеку в каталог библиотек вашей версии IDE
# Отладка
Для отладки можно использовать библиотеку от Pavel Milanes, CO7WT, pavelmc@gmail.com оригинал библиотеки можно найти здесь - https://github.com/pavelmc/FT857d.
Посоветую использовать форк библиотеки со страницы UA6EM, в ней есть готовый пример позволяющий имитировать переключение диапазонов трансивера - https://github.com/UA6EM/FT857d
* NetEEPROM (Library to set or display the network settings of the bootloader)
