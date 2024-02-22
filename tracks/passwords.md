# Оценка сложности паролей для ру-пользователей

**Mentor:** @shagrath

## Описание:
Оценить сложность пароля пользователя - непростая задача. С одной стороны, нельзя дать поставить 12346, с другой - перегибать тоже нельзя. У русских пользователей есть привычка использовать русские слова в английской раскладке в качестве паролей (Ghbdtn \ Ltrf,hm) и анализаторы сложности, рассчитанные на англоговорящих пользователей, посчитают такие пароли безопасными. Напишите программу или обучите модель, которая решит эту и другие проблемы с безопасностью паролей. Обоснуйте свой подход.

## Что мы даем:
- https://github.com/sharsi1/russkiwlst - утечки паролей русскоговорящих пользователей

## Что мы хотим:
1) Проанализируйте и выявите шаблоны и зависимости в паролях характерные для русского языка.
2) Разработайте скрипт, оценивающий, безопасен ли введенный пароль.
3) Интеграция с https://github.com/jephthai/OpenPasswordFilter как задача со звездочкой.

## Критерии оценки:
- **Критерии:** Корректность работы, адекватность и обоснованность методологии.