# Отчёт о тестировании приложения "Precision"

## Бонусная система.

При сложении регулярного бонуса (`regularBonus = 0.3`) и специального (`specialBonus = 0.6`) сумма тотал бонуса не корректна (`0.8999999999999999`)

## Описание тестов:
* Unit test "Запуск кода"

## В результате тестирования выявлены следующие дефекты:
[Ссылка на Issues](https://github.com/BulygaDenis/javaHW1_4/issues/1)


## Результаты

1. 0/1
2. [Ссылка на баг-репорт](https://github.com/BulygaDenis/javaHW1_4/issues/1)


**Ожидаемый результат:**
0.9
**Фактический результат:**
0.8999999999999999
## Общие рекомендации:
Возможно, стоит использовать другой тип переменной.

## Окружение:

Win 10 x 64
openjdk version "11.0.8" 2020-07-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)



