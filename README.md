[TOCM]
<details>
<summary>Конь в пальто</summary>


![Конь](https://github.com/KanstantsinYankun/AltiumHorseLibrary/assets/92923749/7db3f4b7-61cd-48c1-9d28-b666c0c99069) 

</details>



# Описание

 `При создании компонентов, важно соблюдать стандарты и нормы проектирования, установленные в индустрии, чтобы обеспечить совместимость и эффективность проекта. `
<br> Тут представлены:
- [ ] библиотеки SchLib
- [ ] библиотеки PcbLib
- [ ] легаси библиотеки присоединившихся участников
- [ ] библиотеки баз данных
- [ ] форматки ГОСТ для оформления чертежей
- [ ] шрифты ГОСТ
- [ ] настройки рабочей зоны альтиум
- [ ] ???

<br> `Соблюдение этих правил поможет обеспечить качественное проектирование компонентов для Altium Designer, упростить процесс проектирования печатных плат и изготовления прототипов.`

# Инструкция по установке
<details>
<summary>Инструкция</summary>


## Как начать пользоваться библиотекой
### В случае, если у вас нет гит-клиента:
* Скачать архив с файлами библиотеки, нажав кнопку "Clone or download", расположенную справа над списком файлов репозитория, и выбрав пункт "Download ZIP".
* Разархивировать скачанные файлы в папку, путь к которой не содержит национальных символов и пробелов. C:\AltiumHorseLibrary
* Запустить Altium Designer.
* Открыть панель Components, нажать кнопку правее названия в виде трех горизонтальных полосок, выбрать  "File-based Libraryes Preferences", выбрать вкладку "Installed".
* ![image](https://github.com/KanstantsinYankun/AltiumHorseLibrary/assets/92923749/c9f6f165-d9cb-4c2f-b7cc-1a916a3894c8)

* Нажать на кнопку "Install...", перейти по пути где лежит наш репозиторий и выбрать папку с бибилиотеками C:\AltiumHorseLibrary\hLIBs.
* Выбрать тип отображаемых файлов: All installable Libraryes
* В корневой папке библиотеки найти и выбрать все файлы, или только те что вам необходимы (если вам не нужна поддержка легаси).
* Нажать "Открыть" или "Open".
* Нажать "Close".
* Пользоваться : )
  
### В случае, если у вас есть гит-клиент:
* Нажать кнопку "Clone or download", скопировать появившуюся ссылку на репозиторий для гит-клиента.
* Клонировать репозиторий через гит-клиент на локальную машину.
* Установить библиотеку, повторив пункты 3 -- 10 из предыдущего списка.

### Установка файлов и программ:
В папке Additional
.TTF files - Russian GOST fonts, copy to "C:\Windows\Fonts" directory

Установка форматок


</details>

# Полезные ссылки и гайды
<details>
<summary>Ссылки и картинки</summary>

Альтиумовский обзор создания библиотечных компонентов
https://www.altium.com/ru/documentation/altium-designer/creating-file-based-library-components?version=18.1

Альтиумовский гайд куда тыкать что бы создать посадочную площадку компонента
https://www.altium.com/ru/documentation/altium-designer/creating-pcb-footprint?version=19.1

Полезный FAQ iXBT
https://forum.ixbt.com/topic.cgi?id=48:5410

Видео обьясняющее принцип библиотек баз данных
https://www.youtube.com/watch?v=yTLu0gdOo6c

</details>

<details>
<summary>Стандарты</summary>

![image](https://github.com/KanstantsinYankun/AltiumHorseLibrary/assets/92923749/4f0f0d9e-3849-4107-a094-e1735057dc20)

![image](https://github.com/KanstantsinYankun/AltiumHorseLibrary/assets/92923749/8e7aa3c9-5904-414e-b00f-a9d692dc94f5)



</details>

# Структура файлов

Таблица наименований библиотек и типов компонентов в них.
| Имя файла  | Назначение  | Стандарт названия компонента | 
| :------------ | :------------ | :------------ |
| Resistor 0402.IntLib |  |  |
| Resistor 0603.IntLib |  |  |
| Resistor 0805.IntLib |  |  |
| Resistor 1206.IntLib |  |  |
| Resistor 1210.IntLib |  |  |
| Capacitor 0402.IntLib |  |  |
| Capacitor 0603.IntLib |  |  |
| Capacitor 0805.IntLib |  |  |
| Capacitor 1206.IntLib |  |  |
| Capacitor 1210.IntLib |  |  |
| #SMDs                              | полупроводники в SMD |  |
| Inductors&Transformers.PcbLib      | моточные дроссели и трансформаторы |  |
| FilmCapacitors.PcbLib              | пленочные конденсаторы DIP |  |
| ElectrolytCapacitors.PcbLib        | электролитические конденсаторы DIP |  |
| Connectors Molex                   |  |  |
| Connectors.PcbLib                  |  |  |
| LEDs.PcbLib                        | светодиоды SMD, DIP |  |
| #MCUs                              |  |  |
| #FPGAs                             |  |  |
| Inductors.PcbLib, .SchLib | | |               
| Power_Converters IC's.PcbLib, .SchLib | LDO, преобразователи и тп.  | |
| Motor Driver ICs, Gate Drivers.SchLib | Драйверы||
| Transistors.SchLib | | |
| Transformers.PcbLib, .SchLib | Трансформаторы||
| Diodes.SchLib | | |
| Transistors, Diodes, etc.PcbLib| посадочные места под диоды и транзисторы||
| Crystals, Oscillators, Resonators.PcbLib, .SchLib|||
| MCU STM32 |Микроконтроллеры Stm32||
| DA, DD IC.PcbLib| посадочные места под микросхемы||
| Leds.PcbLib, .SchLib |Светодиоды||
| Capasitors_SMD_other|Конденсаторы остальных типоразмеров из Artix ||
| Resistors_other |Резисторы остальных типоразмеров из Artix||






Сохранено для обратной совместимости с легаси проектами
| Имя файла  | Первородный  |
| :------------ | :------------ |
| EPCOS.PcbLib                       | Саныч |
| LED.PcbLib                         | Руденск |
| Miscellaneous Devices.IntLib       | Саныч |
| SamacSys.PcbLib                    |  |
| SamacSys.SchLib                    |  |
| TNY.SchLib                         | Саныч |
| Connectors Molex.PcbLib            |  |
| Connectors Molex.SchLib            |  |
| SoM_Artix.PcbLib                   | Илья |
| SoM_Artix.SchLib                   | Илья |
| IC_InvenSense_MPU-6500_eec.SchLib | RnD Motorica |
| IC_InvenSense_MPU-6500_eec_0.PcbLib | RnD Motorica |
| STM32F0.SchLib | RnD Motorica |
| STM32F0.PcbLib | RnD Motorica |
|  |  |


# Правила принятые при создании компонентов
## Общие правила 
### Унификация базы комплектации
Единицы измерения - мм.
Использовать шрифт ГОСТ тип А из файла "ГОСТ тип А.ttf", который можно найти в репозитории.
Размер кегля - 10 для нумерации пинов, 14 для всего остального.
Сетка УГО компонентов - 2,5 мм.


### Назначение слоев  платы
для плат 
топ-бот внешняя медь
иннеры для внутренней
механика 2 (Board) контур платы
солдеры для вскрытия маски
оверлеи для шлка
Drill Drawing служебная инфа
механика 3 (или 15) для вспомогательных линий

## Правила SchLib
1. Название компонента. Название компонента должно быть четким, информативным и соответствовать стандартам названий компонентов. Желательно также указывать обозначение компонента согласно стандарту.

2. Размещение элементов. Элементы компонента (ножки, контакты, компоненты) должны быть размещены в соответствии с их функциональным назначением. Номера ножек должны соответствовать схеме символа компонента.

## Правила PcbLib


В  каждом футпринте обязательны слои:
1. TOP-BOT для меди контактных площадок (падов)
2. механика 1 для 3д модели
3. механика 15 для центра и установочного контура компонента(полный гарабарит)
4. Top-Bot OVERLAY для шелка и указания первого пина
5. Top-Bot SOLDER для вскрытия маски
Дополнительно:
   Первый пин разъема  - квадратный.
   Ориентация смд на шелке - снаружи компонента, не  под низом.
   Ориентация компонента в соответствии с IPC-7351 Component Zero Orientations Ориентация по стандарту ИПЦ должна быть как в катушке, что бы на автоматической линии не нужно было доворачивать каждый компонент.
   Добавлять дезигнаторы в  шелке, если не влезут  - размещать в  выносках



   Еще стандарты для изучения
IPC J-STD-001 Compliant solder joint goals
IPC-7352 & IPC-7351 Compliant calculations and naming conventions
IEC 61188-7 Compliant Default Zero Component Orientation
