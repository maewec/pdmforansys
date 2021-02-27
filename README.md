# pdnforansys

## Введение
Пакет для чтения результатов прочностного расчета Ansys (полученных в виде .rst файла) и последующей загрузкой этих результатов в python в виде словаря. 

## Описание
С помощью пакета возможно получить результаты расчета в узлах (возможно выбрать узлы по номерам узлов, элементов, названиям наборов узлов и элементов) на одном или нескольких шагах нагружения.
В python результаты представлены в виде одномерного массива данных по выбранным узлам, которые расположены в двухуровневом словаре с ключом вида результатов на первом уровне и с ключом времени нагружения на втором (res_dict[item][time])