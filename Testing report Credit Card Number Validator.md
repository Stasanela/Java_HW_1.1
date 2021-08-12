# Отчёт о тестировании Credit Card Number Validator

## Проверка Credit Card Number Validator

11.08.2021 - 11.08.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 0.5 часа

В результате тестирования выявлены следующие дефекты:
* При вводе карт diners club - international выдает ошибку [ссылка на issue](https://github.com/Stasanela/Java_HW_1.1/issues/1#issue-966587821)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Test case 1:

| Название                               | Описание  | Приоритет | Шаги                              | Ожидаемый результат           |
|----------------------------------------|-----------|-----------|-----------------------------------|-------------------------------|
| Ввод карты diners club - international |           | High      | Ввести номер карты 36631703182022 | Система принимает номер карты |

В качестве тестовых данных использовались данные:
* Данные брались [с этого сайта](https://www.freeformatter.com/credit-card-number-generator-validator.html)

Тестирование производилось в следующем окружении:
* IntelliJ IDEA 2021.2 (Community Edition)
Build #IC-212.4746.92, built on July 27, 2021
Runtime version: 11.0.11+9-b1504.13 aarch64
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.
macOS 11.4
GC: G1 Young Generation, G1 Old Generation
Memory: 1024M
Cores: 8

Kotlin: 212-1.5.10-release-IJ4746.92
