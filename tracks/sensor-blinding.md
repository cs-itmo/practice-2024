# Инструмент для sensor blinding по сигнатурам IDS
**Mentor:** @yorxx

## Описание:
Когда атакующие знают, что ресурс, который они собираются проэксплуатировать, передает данные в IDS\WAF, они могут провести атаку Sensor Blinding: вызвать срабатывание большого количества сигнатур обнаружения, чтобы затруднить распознавание реальной атаки, проводимой на тот же или иной ресурс. Существующие на сегодняшний день инструменты для таких атак устарели, напишите более современное решение!

Мы предлагаем генерировать нагрузку на основании известных сигнатур средств защиты, но вы можете предложить другой подход.

**Пример существующих инструментов:**
- модуль Hail Mary в Armitage
- https://gist.github.com/r00t-3xp10it/7278942915a0514cecd73fd94a070b42

## Что мы даем:
Правила Snort: http://web.archive.org/web/20221001043403/https://www.snort.org/downloads/community/community-rules.tar.gz 

## Что мы хотим:
Скрипт, который проведет атаку на указанный хост и порт, вызвав срабатывание большого количества сигнатур 

## Критерии оценки:
- **MVP:** Скрипт на Python\Go, который принимает на вход путь к файлу с правилами Snort, транспортный протокол, хост и порт цели. Скрипт вызывает срабатывание большого количества сигнатур.
- **Критерии:** Корректность работы, легкость использования, соотношение числа запросов и срабатываний, гибкость.