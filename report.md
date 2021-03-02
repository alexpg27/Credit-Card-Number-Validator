###  **Отчёт о тестировании валидации номеров банковских карт.**
Дата начала: 02.03.2021 - Дата окончания: 02.03.2021

Было проведено:
-  санитарное тестирование, методом белого ящика


На тестирование затрачено:  15 минут

В результате тестирования выявлены следующие дефекты:
- [Валидация банковский карты привязана к 16 знакам](https://github.com/alexpg27/Credit-Card-Number-Validator/issues/1 "Валидация банковский карты привязана к 16 знакам")

####  **Описание процесса тестирования**

В процессе тестирования использовались следующие артефакты:

- [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md "Руководство по установке IntelliJ IDEA")
- [Валидные ключи с сайта freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html "валидные ключи с сайта freeformatter.com")

В качестве тестовых данных использовались данные из [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md "Руководство по установке IntelliJ IDEA") и валидные ключи с сайта [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html "freeformatter.com")

**Ожидаемый результат:**
VISA:

4485359742684893 - Result is OK

4395957311832527 - Result is OK

4875800117259514946 - Result is OK

MasterCard:

5533805382577812 - Result is OK

5421728488060142 - Result is OK

5410329659062760 - Result is OK

Diners Club - International:

36031603879134 - Result is OK

36465896643049 - Result is OK

36929294643935 - Result is OK


Тестирование производилось в следующем окружении:

- Windows 10 (64-bit)
- Java JDK 11.0.10
