# AVR_DIP_Programmer | Адаптер для AVR DIP программатора

Содержание
----
1. <a href="https://github.com/maestro-102/uv_chandelier#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5">Описание</a>
2. <a href="https://github.com/maestro-102/uv_chandelier#%D1%84%D0%BE%D1%82%D0%BE%D0%B3%D1%80%D0%B0%D1%84%D0%B8%D0%B8">Фотографии</a>
3. <a href="https://github.com/maestro-102/uv_chandelier#%D1%85%D0%B0%D1%80%D0%B0%D0%BA%D1%82%D0%B5%D1%80%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B8">Характеристики</a>
4. <a href="https://github.com/maestro-102/uv_chandelier#%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B5-%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B4%D0%BB%D1%8F-%D0%BF%D1%80%D0%BE%D1%81%D0%BC%D0%BE%D1%82%D1%80%D0%B0-%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2">Программы для просмотра файлов</a>
5. <a href="https://github.com/maestro-102/uv_chandelier#%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0">Структура проекта</a>

Описание
----
Последняя печатная плата (на настоящий момент), выполненная методом ЛУТ. Ультрафиолетовые светодиоды заказывал на общеизвестной площадке у "товарищей". Гасящие резисторы для поверхностного монтажа на каждый светодиод. Плата выполнена с возможностью собираться в матрицу (в случае, если придется засвечивать платы большего размера). Размер (грубо) 100х150 мм. Пока хватает...

Фотографии
----
<a href="https://github.com/maestro-102/AVR_DIP_Programmer/blob/master/images/1.jpg" target="_blank">
    <img src="https://github.com/maestro-102/AVR_DIP_Programmer/blob/master/images/1.jpg?raw=true" width=30% alt="preview">
</a>

<a href="https://github.com/maestro-102/AVR_DIP_Programmer/blob/master/images/2.jpg" target="_blank">
    <img src="https://github.com/maestro-102/AVR_DIP_Programmer/blob/master/images/2.jpg?raw=true" width=30% alt="preview">
</a>

Характеристики
----
Напряжение внешнего питания 9 - 12В

Программное обеспечение для просмотра файлов
----

1. Sprint Layout 6.0 - для проектирования печатных плат \
Расширение: \*.lay6 \
Ссылка: https://radioaktiv.ru/loads/softf/pcb/27881-sprint-layout-60-rus.html

2. Splan 7.0 - для черчения электрических схем \
Расширение: \*.spl7 \
Ссылка: http://splansoft.ru/

Структура проекта
----
Описание файловой структуры проекта:

    AVR_DIP_Programmer
    ├── image          - папка с фотографиями устройства
    ├── pcb            - печатная плата
    ├── shemas         - схема устройства
    └── README.md 
