### Отчёт о тестировании
### Краткое описание
Создано приложение позволющее отследить пополнение банковского счет клиента крупной суммой денежных средств.
Исходя из проведенного тестирования стало ясно, что диапазона значений переменной int недостаточно для корректной
работы приложения.

### Описание тестов
Проведено функционально тестирование приложения - корректность ввода и вывода данных в приложении.
### Результаты:
1. 50% успешных тестов.
2. [Баг-репорт](https://github.com/ktonyi/moneytransfer/issues/1)

### Общие рекомендации:
Рекомендовано ипользовать тип данных long, так как значений переменной int не хватает для корректной работы
приложения.


