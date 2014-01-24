Summary
=======

Парсер производственного календаря <http://www.superjob.ru/proizvodstvennyj_kalendar/>
Также имеется уже готовый json и pickle файл со структурой.

+ work - рабочий
+ holiday - нерабочий
+ short - сокращенный день


Usage
=====

    apt-get install python-bs4 python-simplejson git
    git clone https://github.com/AyumuKasuga/russian_workdays
    cd https://github.com/AyumuKasuga/russian_workdays
    python ./parser.py
