# Лабораторные работы за осенний семестр 2020

В `master` ветке данного репозитория присутствуют актуальные задания, включая 
распределение протоколов по студентам.

# Прогресс

Легенда:

| Символ   | Значение                                                                                   |
| --       | --                                                                                         |
|          | Работа не сдана или находится на рассмотрении                                              |
| +        | Работа принята                                                                             |
| !        | Работа рассмотрена, требуется демо                                                         |
| ?        | Работа рассмотрена, но требует доработки                                                   |
| -        | Работу сдавать не требуется                                                                |
| -------- | --------                                                                                   |
| SSH ключ | [Отправить SSH ключ преподавателю](https://insysnw.github.io/labs/900-ssh-keygen/)         |
| Л.1a     | [TCP чат](https://insysnw.github.io/labs/01-tcp-chat/)                                     |
| Л.1б     | [TCP чат](https://insysnw.github.io/labs/01-tcp-chat/) (неблокирующие сокеты)              |
| Л.2c     | [UDP сервер существующего протокола](https://insysnw.github.io/labs/02-udp-real-protocol/) |
| Л.2к     | [UDP клиент существующего протокола](https://insysnw.github.io/labs/02-udp-real-protocol/) |
| Л.3      | Задание из методички                                                                       |

## Группа 201

| ФИО              | SSH ключ | Л.1a                                          | Л.1б                                          | Л.2c | Л.2к | Л.3 |
| --               | --       | --                                            | --                                            | --   | --   | --  |
| Антропова А.А.   | +        |                                               |                                               |      |      |     |
| Белов Е.А.       | +        |                                               |                                               | tftp | dhcp |     |
| Буй К.Д.         | +        |                                               |                                               | tftp | dns  |     |
| Гладкова Е.Д.    | +        |                                               |                                               |      |      |     |
| Голзицкий Н.С.   | +        |                                               |                                               |      |      |     |
| Гуляев Д.В.      |          |                                               |                                               |      |      |     |
| Данилов А.И.     | +        |                                               |                                               | dhcp | ntp  |     |
| Казанджи М.А.    | +        |                                               |                                               | ntp  | snmp |     |
| Киселев Н.Д.     | +        |                                               |                                               | dns  | tftp |     |
| Лялин А.С.       | +        |                                               |                                               |      |      |     |
| Натура А.А.      | +        |                                               |                                               | snmp | dns  |     |
| Никитин И.Н.     | +        |                                               |                                               |      |      |     |
| Романов А.Л.     | +        |                                               |                                               | dns  | dhcp |     |
| Свечников Р.А.   | +        |                                               |                                               | dhcp | dns  |     |
| Сибагатулин А.Ф. |          |                                               |                                               |      |      |     |
| Товпеко К.А.     | +        | [?](https://github.com/insysnw/2020h2/pull/2) | [?](https://github.com/insysnw/2020h2/pull/2) | dns  | ntp  |     |
| Черноног С.А.    | +        |                                               |                                               |      |      |     |
| Шаляпин Г.А.     | +        |                                               |                                               |      |      |     |

## Группа 203

| ФИО             | Ssh ключ | Л.1a | Л.1б | Л.2с | Л.2к   | Л.3 |
| --              | --       | --   | --   | --   | --     | --  |
| Ворошилов А.А.  | +        |      |      |      |        |     |
| Гусев Н.С.      |          |      |      |      |        |     |
| Зарецкая Е.С.   |          |      |      |      |        |     |
| Иванов И.Д.     | +        |      |      | dns  | ntp    |     |
| Калашников Р.А. |          |      |      | dns  | snmp   |     |
| Костарев В.И.   | +        |      |      | dhcp | snmp   |     |
| Любченкова А.А. | +        |      |      | tftp | dns    |     |
| Меньшов П.А.    | +        |      |      | dns  | tftp   |     |
| Морозов Е.С.    | +        |      |      | dns  | dhcp   |     |
| Никитина Д.С.   | +        |      |      |      |        |     |
| Овсянников Е.А. | +        |      |      |      |        |     |
| Орлова П.А.     | +        |      |      | tftp | dns    |     |
| Пентегов А.О.   | +        |      |      |      |        |     |
| Семёнов Д.С.    | +        |      |      | dhcp | dns    |     |
| Середин К.В.    | +        |      |      | dhcp | ntp    |     |
| Трушин И.А.     | +        |      |      | tftp | dhcp   |     |
| Черникова А.С.  | +        |      |      | tftp | ntp    |     |
| Шелепов В.А.    | +        |      |      | dhcp | tftp   |     |

# Требования к отчету:

* Инструкция по использованию;
* Инструкция по сборке/установке;
* Описание используемого протокола;
  * Своего для первой и третьей лабораторной;
  * Используемого подмножества для второй;
* ???
* PROFIT

Отчет можно писать как в сообщении к PR-у, так и присылать в иных 
форматах (`.pdf`, `.docx`, `.txt` и т.п.).

# Порядок сдачи

* Fork от данного репозитория
* Push каждой лабораторной в отдельную ветку
* Создание отдельного PR на каждую лабораторную
* Ставите label по сдаваемой лабе (`First lab`, `Second lab`, `Third lab`)

При создании PR, в качестве напоминалки, сделан шаблон.
