# Big Data Analysis Course

Lab 1
1.	Сколько всего административных округов в Сан-Франциско? - 10
2.	В каких административных округах наибольшая преступность? - SOUTHERN, MISSION, CENTRAL
3.	Какие виды преступлений совершаются чаще всего? - LARCENY/THEFT, OTHER OFFENSES, NON-CRIMINAL
4.	Каково назначение функции Лямбда в Python? - Лямбда позволяет указывать функцию в одной строке кода, без использования def и без определения конкретного имени для нее.
5.	Какие виды преступлений регистрируются в Сан-Франциско? - LARCENY/THEFT, OTHER OFFENSES, NON-CRIMINAL, ASSAULT, VEHICLE THEFT, SEX OFFENSES, NON FORCIBLE, BAD CHECKS etc.


Lab 2
1.	Что такое анонимная функция Python, как она работает - функции, которые не привязаны к имени. Лямбда-функцию удобно использовать в выражениях, где требуется написать небольшую функцию для обработки данных.
2.	Что возвращает функция speedtest ()? - строку со скоростями загрузки и выгрузки.
3.	Какой код используется для просмотра результатов функции speedtest ()? - 
    speedtest_cmd = "speedtest-cli --simple"
    process = subprocess.Popen(speedtest_cmd.split(), stdout=subprocess.PIPE)
    process_output = process.communicate()[0]
    print(process_output, type(process_output))
5.	Каким образом выполняется переименование столбцов датафрейма? - метод rename(). df_compact.rename(columns={'Measure A':'Ping (ms), ...'}, inplace=True)
6.	Для чего в лабораторной работе импортируется библиотека NumPy? - базовый пакет для математических вычислений на Python. Он содержит среди прочего средства работы с массивами объектов и сложные математические функции. Во второй работе имеется импорт, но ни одного явного вызова функций данной библиотеки.
7.	Как выглядит код удаления столбца Datetime? - df_compact.drop('Datetime', axis=1, inplace=True)
