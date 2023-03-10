# Анализ убытков приложения ProcrastinatePRO+

[HTML](https://nbviewer.org/github/tatiana-ili/Portfolio/blob/main/marketing_analysis/marketing_analysis.ipynb) \
[ipynb](https://github.com/tatiana-ili/Portfolio/blob/main/marketing_analysis/marketing_analysis.ipynb)

*Статус:* проект завершен.

## Данные

В наличии данные о пользователях, привлечённых с 1 мая по 27 октября 2019 года.\
Файл visits_info_short.csv хранит лог сервера с информацией о посещениях сайта, orders_info_short.csv — информацию о заказах, а costs_info_short.csv — информацию о расходах на рекламу.

Структура visits_info_short.csv:
- User Id — уникальный идентификатор пользователя,
- Region — страна пользователя,
- Device — тип устройства пользователя,
- Channel — идентификатор источника перехода,
- Session Start — дата и время начала сессии,
- Session End — дата и время окончания сессии.

Структура orders_info_short.csv:
- User Id — уникальный идентификатор пользователя,
- Event Dt — дата и время покупки,
- Revenue — сумма заказа.

Структура costs_info_short.csv:
- dt — дата проведения рекламной кампании,
- Channel — идентификатор рекламного источника,
- costs — расходы на эту кампанию.

## Задача

Разобраться в причинах роста убытков компании в последние несколько месяцев и помочь компании выйти в плюс.

## Используемые библиотеки
*Pandas, Matplotlib, Seaborn, NumPy*

## Вывод

Рекомендовано пересмотреть условия либо прекратить сотрудничество с каналом TipTop, а также двумя другими явных аутсайдеров - FaceBoom и AdNonSense.\
Рекомендованы альтернативные каналы RocketSuperAds, WahooNetBanner для дальнейшего развития.
