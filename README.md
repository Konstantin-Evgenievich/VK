# VK

Вообще все индивидуально, и нужно смотреть под конкретную задачу.
Если в общем - файлы хранятся в файловой системе, в БД хранятся имена и пути к файлам.
Все по своему делают, у крупных сетей поиск и хранение как правило разнесены по разным серверам - одни сервера занимаются поиском, а другие хранением и отдачей контента.


SQLite

плюсы:
Высокая производительность;
Компактность;

минусы:
кроссплатформенность;
бесплатная и открытая библиотека, даже для коммерческого
использования.

небогатая функциональность;
не поддерживает сетевой доступ;
не поддерживает транзакции;
не поддерживает хранимые процедуры;
не поддерживает триггеры;
нет режима восстановления информации;
не поддерживает репликацию;
и т.д.


Ms SQL

плюсы:
высокая интегрированность с технологиями и продуктами
Microsoft;
Языки описания пользовательских функций Transact-Sql
.NET.

минусы:
проприетарность;
не поддерживает шардинг;
целевая программная платформа ОС Microsoft Windows.

Oracle

плюсы:
встроенное обнаружение отказов БД, автоматический анализ и
исправление ошибок;
прозрачное масштабирование;
самая высокая отказоустойчивость среди конкурентных решений

минусы:
проприетарность.


MySQL

плюсы:
наличие различных backend для хранения данных в файловой
системе;
отложенное построение неуникальных вторичных индексов.

минусы:
проприетарная лицензия для продуктов с закрытым исходным
кодом;
меньшая чем у PostgreSQL, Oracle, MsSQL производительность;
слабые средства анализа производительности.


PostgreSQL

плюсы:
наличие функционального инструмента оптимизации SQL запросов;
продвинутые средства настройки производительности;
полнотекстовый поиск;
Open Source лицензия(PostgreSQL license, аналогичная BSD и MIT license).

минусы:
плохо поддерживает шардинг;
разработка ведется на добровольных началах, но на очень
высоком техническом уровне.



// сделаю  на выходных 8-9 июня


// По опыту: Делал инвентарную книгу для списания
