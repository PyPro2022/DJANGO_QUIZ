------------------------------------------------------------------------------------------------------------------------
# DJANGO_QUIZ
Hillel python_advanced_15032022 learning project

Student: Кардашев Константин

------------------------------------------------------------------------------------------------------------------------

## Технические требования  
### Web-UI
  1. Регистрация
      - регистрация (с подтверждением по email)
      - авторизация
      - смена пароля
      - сброс пароля
    
  2. Возможности пользоваля
      - прохождение любого теста
      - последовательно проходить вопросы теста (один за другим)
      - завершение отложенного теста
      - удаление незавершенного теста 
      - просмотр результатов
    
  3. После завершения теста
      - отчет о ко-ве правильных и неправильных ответов
      - процент правильных ответов

### Admin site
  1. Управление пользователями
  2. Управление тестами
      - добавление теста
      - изменить тест
      - удаление теста
      - валидация теста
        - нельзя сохранить вопрос:
            - без указания правильного ответа
            - в которов все ответы правильные

### Дополнительные требования
1. [x] Проект должен быть на Git-е
2. [x] Наличие файла requirements.txt
3. [x] venv
4. [ ] PostgreSQL
5. [ ] Наличие дампа данных
6. [ ] bootstrap
7. [ ] API + Tests
8. [ ] Docker image
9. [ ] Кэширование 
10. [ ] Планировщик
11. [ ] Деплой на Amazon

## DB - Schema
![db](db_schema.jpg)
------------------------------------------------------------------------------------------------------------------------

Тестовые аккаунты

    user_2 ||  user_2@test.com  || testpass1234 ||

    admin ||  admin@test.com  || superpass123 || 


------------------------------------------------------------------------------------------------------------------------
ДЗ 22. Создание тестов и выгрузка их в дамп (DZ22_TestsNDump)
------------------------------------------------------------------------------------------------------------------------
###СДЕЛАНО

[x] - Добавил виджет даты в форму апдейта юзера в аккаунте

[x] - Подключил CustomUser в админку

[x] - Перекинул всё с урока в quiz

[x] - Создал валидаторы для order_num в формах. Погонял тесты.

[x] - Создал 3 теста через админку. Выгрузил данные в dump_quiz.json

[x] - Прибрал мусор. Подготовил проект к выгрузке на GH


------------------------------------------------------------------------------------------------------------------------
ДЗ 21. Сброс/Изменение пароля (DZ21_PasswordRC)
------------------------------------------------------------------------------------------------------------------------
###СДЕЛАНО

[x] - Cоздал на GH репозиторий DJANGO_QUIZ

[x] - Клонировал. Установил requirements.

[x] - Запустил джанго проект app

[x] - Создал приложения accounts и quiz

[x] - Добавил модель и форму в Accounts 

[x] - Добавил сигнал в apps

[x] - Добавил utils и send_activation_notification

[x] - Добавил настройки в settings 

[x] - Добавил вьюхи и шаблоны, прописал маршруты для изменения/сброса/восстановления пароля.

[x] - Прикрутил шаблоны изменения/сброса/восстановления пароля. Слегка отбутстрапил проект по своему стилю.

[x] - Подготовил проект к выгрузке на GH