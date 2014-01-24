Summary
-------

Парсер производственного календаря <http://www.superjob.ru/proizvodstvennyj_kalendar/>

Также имеется уже готовый json и pickle файл со структурой.

+ work - рабочий
+ holiday - нерабочий
+ short - сокращенный день


On Debian/Ubuntu
----------------

    apt-get install python-bs4 python-simplejson python-distribute python-wsgiref git
    git clone https://github.com/AyumuKasuga/russian_workdays
    cd russian_workdays
    python ./parser.py
