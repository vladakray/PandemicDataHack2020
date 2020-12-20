# PandemicDataHack2020

Hello there!

В данном репозитории содержатся все файлы с кодом, которые использовались для решения задачи Хакатон, трек#3: Предскзание уровня заработной платы по данным резюме.

Что именно тут есть?
1. [General](https://github.com/vladakray/PandemicDataHack2020/blob/main/General.ipynb) - основной файл, в котором происходила первичная обработка данных и основное моделирование (в т.ч. лучшей модели). Все, что нужно знать о нашем решении, лежит именно тут.
2. [MARS_ipynb](https://github.com/vladakray/PandemicDataHack2020/blob/main/MARS_ipynb.ipynb) - дополнительный файл с отчаянной попыткой использовать силу MARS для захвата возможной нелинейности и взаимосвязи переменных. Модель не вошла в итоговый топ.
3. [Preparation_train](https://github.com/vladakray/PandemicDataHack2020/blob/main/Preparation_train.ipynb) и [Preparation_test](https://github.com/vladakray/PandemicDataHack2020/blob/main/Preparation_test.ipynb) - дополнительные файлы обработки обучающей и тестовой выборки, для их дальнейшего скармливания TabNet. В данных файлах, вы также можете найти кластеризацию городов (переменная также не вошла в итог :(, но была использована в файле General)
4. [Scrapping](https://github.com/vladakray/PandemicDataHack2020/blob/main/Scrapping.ipynb)- дополнительный файл с парсингом рейтингов университетов России (переменная снова не вошла в итог :((, но была использована в General).
5. [TabNet](https://github.com/vladakray/PandemicDataHack2020/blob/main/TabNet_model.ipynb)- дополнительный файл с попыткой предсказать з/п только по текстовым данным.
6. [Hackaton](https://github.com/vladakray/PandemicDataHack2020/blob/main/Hackaton.pdf) - презентация решения с защиты на самом PadamecDataHack2020.

Enjoy reading!

Sincerely ваш,
Лишний Носок.

![Team](https://cdn1.savepice.ru/uploads/2020/12/20/603ba4cd6ee6c88247530538ddd26923-full.jpg)
