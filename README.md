# DeliveryForm

### Описание проекта smoke test нового функционала услуг банка
В данном проекте проверялась функция доставки карты в разные города.

Была предоставлена SUT (черный ящик) в виде jar файла, который был запусщен на нашем окружени.

Данные созадвалась случайный образом при помощи библиотеке Faker, хард-кодились в самом коде.

Был проведен позитивный сценарий успешного заказа данной услуги. 

Никаких багов выявлено не было.

### Запуск приложение и allure report
```
java -jar ./artifacts/app-card-delivery.jar

gradlew clean test allureReport

gradlew allureServe
```

### Окружение 

java 11, gradle, selenide, faker, junit5, allure
