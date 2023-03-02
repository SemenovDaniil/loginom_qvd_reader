# loginom_qvd_reader
Импорт qvd-файлов в loginom

Для иcпользования компонента необходимо установить Python версий 3.6 - 3.9.

Настроить нужный итерпретатор python для Loginom можно по [инструкции] (**Параметры компонента: Python**) в меню Администрирование -> параметры.

Так же для работы компонента для указанного интерпертатора должна быть установлена [библиотека python qvd]

Скачанный пакет необходимо подключить к необходимому пакету в котором вы работаете через в меню Пакеты->Ссылки->Добавить. После этого при редактировании сценария в производных компонентах появится компонент qvd_reader.

Перетащив компонент на полотно, надо задать значение переменной на входящем порту, установив в нем путь до нужного файла.
Запустив работу компонента на выходе получим таблицу из qvd-файла.

[//]: #
   [инструкции]: <https://help.loginom.ru/userguide/admin/parameters.html#parametry-komponenta-python>
   [библиотека python qvd]: <https://pypi.org/project/qvd/>
