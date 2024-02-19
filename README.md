# Проектирование высоконагруженного сервиса для хостинга проектов и их совместной разработки GitHub

Курсовая работа в рамках 3-го семестра программы по Веб-разработке ОЦ VK x МГТУ им. Н.Э. Баумана (ex. "Технопарк") по
дисциплине "Проектирование высоконагруженных сервисов"

#### [Задание](https://github.com/init/highload/blob/main/homework_architecture.md)

#### Автор - Захаров Владимир

## Содержание

- [Проектирование высоконагруженного сервиса для хостинга проектов и их совместной разработки GitHub](#проектирование-высоконагруженного-сервиса-для-хостинга-проектов-и-их-совместной-разработки-GitHub)
    - [Содержание](#содержание)
    - [1. Тема и целевая аудитория](#1-тема-и-целевая-аудитория)
        - [1.1 Тема](#11-тема)
        - [1.2 Целевая аудитория](#12-целевая-аудитория)
        - [1.3 MVP](#13-mvp)
        - [1.4 Ключевой функционал сервиса](#14-ключевой-функционал-сервиса)
    - [Список использованной литературы](#список-использованной-литературы)

## 1. Тема и целевая аудитория

### 1.1 Тема

GitHub - веб-сервис для хостинга IT-проектов и их совместной разработки. Веб-сервис основан на системе контроля версий
Git.

Категория - Git.

### 1.2 Целевая аудитория

***MAU*** = 14+ миллионов пользователей в день; </br>
***DAU*** = 433+ миллионов посещений в месяц. [^1]

Гендерное распределение [^2]:
![image](images/audience.png)

Географическое распределение [^3]:
![image](images/geo.png)

### 1.3 MVP

1. Регистрация и авторизация;
2. Работа с репозиториями:
    1. Создание;
    2. Редактирование;
    3. Настройка;
    4. Поиск;
    5. Удаление;
3. Работа с ветками;
4. Уведомление пользователей о деятельности в репозиториях, на которые они подписаны.

### 1.4 Ключевой функционал сервиса

1. Регистрация и авторизация;
2. Работа с репозиториями:
    1. Создание;
    2. Редактирование;
    3. Поиск;
    4. Удаление;
    5. Pull Request:
        1. Создание;
        2. Редактирование;
        3. Закрытие;
        4. Комментирование;
            1. Реакции на комментарии;
    6. Issues:
        1. Создание;
        2. Редактирование;
        3. Закрытие;
        4. Комментирование;
            1. Реакции на комментарии;
    7. Fork;
    8. Просмотр статистики;
    9. Возможность добавить в избранное;
3. Работа с ветками;
4. Уведомление пользователей о деятельности в репозиториях, на которые они подписаны;
5. GitHub Actions - автоматизации рабочих процессов;
6. GitHub Pages - создание веб-страницы прямо из репозиториев.

## Список использованной литературы

[^1]: [GitHub Traffic Analysis](https://hypestat.com/info/github.com)
[^2]: [GitHub Audience Analysis](https://www.similarweb.com/website/github.com/#demographics)
[^3]: [GitHub Geography Analysis](https://www.similarweb.com/website/github.com/#geography)
