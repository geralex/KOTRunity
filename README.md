# KOTRunity

Проект разрабатывался в первую очередь для возможности подгрузки ресурсных файлов и сцен из игры Далбнобойщики 2, была идея написать редактор сцен, но в последствии стало попросту лень всё дорабатывать.

В ассеты добавлен скрипт JCar.cs, который позволяет загрузить для управления автомобиль из переменной StartCar из скрипта GameManager.cs
Код распространяется "как есть", со всеми комментариями оставлеными во время разработки, а так же тестовыми функциями (возможно не работающими), со всеми недоработками и сопутствующими их проблемами.

Для подгрузки необходимо в корневую папку unity проекта добавить папку db2 в которой будут основные игровые файлы, либо необходимо указать пути в скриптах Load.cs и GameManager.cs

Над проектом работали: Юрий Гладышенко, aleko2144, так же были использованы алгоритмы ресурсных файлов AlexKimov с репозитория https://github.com/AlexKimov/HardTruck-RignRoll-file-formats
