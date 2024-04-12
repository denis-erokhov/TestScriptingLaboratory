# TestScriptingLaboratory

# Тестовое задание 1: Автоматизация работы с постами

## Задача 1: Создание нового поста

**Описание:**
Создайте новый пост и запишите его ID в переменную окружения.

**Шаги:**
1. Отправьте запрос для создания нового поста.
2. Извлеките ID созданного поста из тела ответа.
3. Запишите ID поста в переменную окружения.

**Подсказка:**
Воспользуйтесь скриптом во вкладке "Tests". Для записи переменной в окружение используйте `pm.environment`.

## Задача 2: Изменение параметра "likes" поста

**Описание:**
Измените параметр "likes" у существующего поста на значение 10 и отправьте запрос на его обновление.

**Шаги:**
1. Отправьте запрос для получения поста по его ID, используя переменную окружения с ID поста.
2. Измените параметр "likes" в теле ответа на значение 10.
3. Отправьте запрос на обновление поста с обновленным телом.

**Подсказка:**
Используйте скрипт во вкладке "Tests". Для перенаправления запроса используйте `pm.sendRequest`.


