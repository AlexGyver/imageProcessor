# imageProcessor
Программа для преобразования изображений в битмап код. Для работы нужна [Java](https://www.java.com/ru/download/)
![КАРТИНКА](https://github.com/AlexGyver/imageProcessor/blob/master/docs/image.jpg)

## Возможности
- Поддержка популярных форматов изображений
- Встроенный редактор:
	- Перемещение/масштаб/поворот
	- Яркость/контрастность
	- Оттенки серого
	- Инверсия
	- Дисеринг (для OLED)
	- Порог (преобразовать в ЧБ)
	- Постеризация
	- Кисть
- Сохранение отредактированного изображения в файл
- Несколько вариантов кодировки:
	- OLED (вертикальный байт), 8 пикселей в байте, чёрный и белый (0-1)
	- 8 пикселей в байте, чёрный и белый (0-1)
	- 1 пиксель в байте, чёрный и белый (0-1)
	- 1 пиксель в байте, оттенки серого 8 бит (0-255)
	- RGB232, 1 пиксель в uint8
	- RGB565, 1 пиксель в uint16
	- RGB888, 1 пиксель в uint32
- Настройка ширины и высоты
- Добавление слова PROGMEM
- Инверсия битмапа
- Отражение по горизонтали и вертикали
- Сохранение в файл, копирование в буфер обмена 

## Управление
- Слайдеры можно перемещать колесом мыши (навести и вращать)
- Изображение можно перемещать удерживанием колеса мыши
- Изображение можно масштабировать вращением колеса мыши

## Скачать релиз v1.5.1
- [Windows 32](https://github.com/AlexGyver/imageProcessor/releases/download/1.5.1/application.windows32.zip)
- [Windows 64](https://github.com/AlexGyver/imageProcessor/releases/download/1.5.1/application.windows64.zip)
- [Linux 32](https://github.com/AlexGyver/imageProcessor/releases/download/1.5.1/application.linux32.zip)
- [Linux 64](https://github.com/AlexGyver/imageProcessor/releases/download/1.5.1/application.linux64.zip)
- [Linux arm64](https://github.com/AlexGyver/imageProcessor/releases/download/1.5.1/application.linux-arm64.zip)
- [Linux armv6hf](https://github.com/AlexGyver/imageProcessor/releases/download/1.5.1/application.linux-armv6hf.zip)

## Исходник
Программа сделана в [Processing](https://processing.org/). Используется библиотека **controlP5**, установить можно через встроенный менеджер библиотек (*Набросок/Импортировать библиотеку/Добавить библиотеку.../Libraries/* Искать **controlP5**). Также для работы Processing нужна [Java](https://www.java.com/ru/download/).

## Версии
- v1.0 - поехали
- v1.1 - добавил другие варианты вывода, инверсию и флип по Х и У, расширенный help
- v1.2 - изменена логика перемещения изображения, добавлено перемещение удерживанием колеса мыши и масштаба - вращением
- v1.3 - добавлен выбор между одномерным и двумерным битмапом
- v1.4 - исправлены ошибки, добавлено имя битмапа
- v1.5 - добавлен формат RGB323, исправлены ошибки
- v1.5.1 - исправлена ошибка при запуске в релизах