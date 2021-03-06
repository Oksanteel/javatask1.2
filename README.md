# Отчёт о тестировании приложения IntelliJ IDEA

## Краткое описание

<05.06.2020> - <05.06.2020> было проведено: установка IntelliJ IDEA согласно Руководство по установке IntelliJ IDEA, тестирование работы программы IntelliJ IDEA согласно тестовому сценарию.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* https://github.com/Oksanteel/javatask1.2/issues/1

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Руководство по установке IntelliJ IDEA https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md
* Тест-кейс по проверке работы IntelliJ IDEA https://github.com/Oksanteel/javatask1.2/blob/master/TESTK.md


В качестве тестовых данных использовались данные из "Тест-кейса по проверке работы IntelliJ IDEA", ссылка на источник: https://github.com/Oksanteel/javatask1.2/blob/master/TESTK.md :
* Валидные номера карт, состоящие и 16 цифр - OK
* Валидные номера карт, состоящие и 13 цифр - OK
* Валидные номера карт, состоящие и 15 цифр - OK
* Валидные номера карт, состоящие и 17 цифр - OK
* Валидные номера карт, состоящие и 18 цифр - OK
* Валидные номера карт, состоящие и 19 цифр - OK

* Невалидные номера карт, состоящие и 16 цифр - FAIL
* Невалидные номера карт, состоящие и 13 цифр - FAIL
* Невалидные номера карт, состоящие и 15 цифр - FAIL
* Невалидные номера карт, состоящие и 17 цифр - FAIL
* Невалидные номера карт, состоящие и 18 цифр - FAIL
* Невалидные номера карт, состоящие и 19 цифр - FAIL


Тестирование производилось в следующем окружении:
* ОС: Windows 10 Home, 64-разрядная
* Java: 11.0.7
* IntelliJ IDEA 2020.1.2
