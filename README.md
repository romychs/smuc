# SMUC2

## Spectrum Multi Unit Controller

Оригинальный модуль SMUC (Scorpion & MOA Universal Controller), был расчитан на работу с клоном компьютера ZX Spectrum Scorpion.
Данный вариант является переработкой оригинальной схемы участниками форума zx-pk.ru и может использоваться с различными клонами, имеющими ZX-BUS.

Схема устройства основана на дискретной схеме SMUC Владислава Семченко (Vladislav Semchenko), реализована на CPLD фирмы ALTERA Евгением Ивановым (Ewgeny Ivanoff).
Некоторые изменения в схеме добавлены для увеличения совместимости с современными машинами (ZXM-Phoenix и др.) Валерием Ткачуком (Valery Tkachuck).
Печатная плата разработана и изготовлена Дмитрием Михальченковым (Dmitry Mikhalchenkov).

В папке [Originals](Originals) собраны материалы по варианту контроллера, разработанному участниками форума zx-pk.ru.

[Тема на форуме SMUC на дискретах и ПЛИС](https://zx-pk.ru/threads/1360-smuc-na-diskretakh-i-plis.html)

## Возможности контроллера
* Интерфейс IDE для подключения HDD, CD
* Память NVRAM 2k, для сохранения настроек
* Энергонезависимые часы типа DS1287, DS12887, M146818, 512ВИ1.
* Проограммная совместимость с ранее выпускавшимся SMUC 1.X, фирмой Scorpion, за исключением контроллера прерываний и интерфейса ISA8, которые в данной реализации отсутствуют.


## Мой вариант
В папке [My](My), приведена оцифрованая мной схема, печатная плата и герберы.


