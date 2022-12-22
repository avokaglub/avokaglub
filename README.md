# Diplom_1

[Задание 1: юнит-тесты](https://github.com/avokaglub/Diplom_1/)

[Текст задания](https://github.com/avokaglub/Diplom_1/blob/main/task_1.md)

Для запуска тестов выполнить команду
```
mvn clean test
```

Для генерации отчета о покрытии кода с помощью Jacoco тестами выполнить команду
```
mvn verify
```
Отчет будет сгенерирован в папку target/site/jacoco/

Добавить папку с отчетом Jacoco к отслеживаемым файлам. Добавить ключ -f, если папка target указана в .gitignore.
```
git add -f .\target\site\jacoco\.
git commit -m "add jacoco report"
git push
```

# Diplom_2

[Задание 2: API](https://github.com/avokaglub/Diplom_2/)

[Текст задания](https://github.com/avokaglub/Diplom_2/blob/main/task_2.md)

Для запуска тестов выполнить команду
```
mvn clean test
```
Для генерации и открытия отчета Allure выполнить команды
```
allure generate --clean .\target\allure-results -o .\target\allure-reports
allure open .\target\allure-reports
```

# Diplom_3

[Задание 3: веб-приложение](https://github.com/avokaglub/Diplom_3/)

[Текст задания](https://github.com/avokaglub/Diplom_3/blob/main/task_3.md)

Для запуска тестов выполнить команду
```
mvn clean test
```
Для генерации и открытия отчета Allure выполнить команды
```
allure generate --clean .\target\allure-results -o .\target\allure-reports
allure open .\target\allure-reports
```

Для запуска тестов [chromedriver.exe](https://chromedriver.chromium.org/downloads) должен быть расположен в директории, указанной в переменной окружения PATH.
Версия драйвера должна соответствовать версии браузера Google Chrome.
