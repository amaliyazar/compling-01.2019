# compling-01.2019
Сравнение анализаторов в Python

[Использованный текст](https://github.com/amaliyazar/compling-01.2019/blob/master/text.txt)

## Mystem

Для анализа текста использовалось Unix-приложение Mystem. Я сделала два варианта вывода, в одном из которых использовала опции -n, -c, -i, а в другом -n, -c, -i, -g, -s

[Вывод 1](https://github.com/amaliyazar/compling-01.2019/blob/master/output_mystem1.txt)
[Вывод 2](https://github.com/amaliyazar/compling-01.2019/blob/master/output_mystem.txt)

## Pymorphy

В данном случае я использовала библиотеку для Python Pymorphy2

[Файл с кодом](hhttps://github.com/amaliyazar/compling-01.2019/blob/master/pymorphy.py)

В результате исполнения кода производились:

* Нормализование слова (перевод в именительный падеж)
* Склонение в родительном
* Лексемы
* Простой Анализ

[Вывод](https://github.com/amaliyazar/compling-01.2019/blob/master/output_pymorphy.txt)

## NLTK

В этом варианте для анализа текста использовалась библиотека NLTK

[Файл с кодом](https://github.com/amaliyazar/compling-01.2019/blob/master/stopwords.py)

В результате исполнения кода производились:

* Токенизация текста
* Извлечение стоп-слов
* Подсчет количества слов в тексте
* Подсчет количества слов в тексте без стоп-слов
* Процент стоп-слов в тексте
* Разбиение текста на предложения
* Стемминг (выделение основы слова)
* POS-Tagging (определение части речи слова)

[Вывод](https://github.com/amaliyazar/compling-01.2019/blob/master/output%20nltk.txt)

