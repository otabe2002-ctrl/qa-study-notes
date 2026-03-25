|Позитивный тест-кейс| | | | | | | | | | |
|---|---|---|---|---|---|---|---|---|---|---|
| | | | | | | | | | | |
|Название проекта|TC_AUTH_POS| | | | | | | | | |
|Модуль|Авторизация пользователя| | | | | | | | | |
|Автор| | | | | | | | | | |
|Дата создания|28-12-2025| | | | | | | | | |
|Ревьюер| | | | | | | | | | |
|Дата ревью| | | | | | | | | | |
| | | | | | | | | | | |
| | | | | | | | | | | |
|ID тест-кейса|Заголовок|Описание|Предусловия|Окружение|Шаги выполнения|Ожидаемый результат|Фактический результат|Статус|Исполнитель|Комментарии|
|TC_AUTH_POS-01|Успешная авторизация пользователя с валидными данными|Проверка успешной авторизации пользователя с активным аккаунтом при вводе корректного логина и пароля|#NAME?|ОС: Windows/ macOS Браузер: Chrome URL: https://www.saucedemo.com/|1. Открыть страницу https://www.saucedemo.com/ 2. Ввести валидные данные из перечисленного списка standard_user problem_user performance_glitch_user error_user visual_user 3. Ввести единый пароль  secret_sauce 4. Нажать "Login" |Пользователь попадает на вкладку каталога товаров|Пользователь попадает на  вкладку каталога товаров|Passed|QA Engineer|standard_user, problem_user, performance_glitch_user,  error_user, visual_user.|
|Негативный тест-кейс| | | | | | | | | | |
|---|---|---|---|---|---|---|---|---|---|---|
| | | | | | | | | | | |
|Название проекта|TC_AUTH_NEG| | | | | | | | | |
|Модуль|Авторизация пользователя с неккоректными данными| | | | | | | | | |
|Автор| | | | | | | | | | |
|Дата создания|28-12-2025| | | | | | | | | |
|Ревьюер| | | | | | | | | | |
|Дата ревью| | | | | | | | | | |
| | | | | | | | | | | |
| | | | | | | | | | | |
|ID тест-кейса|Заголовок|Описание|Предусловия|Окружение|Шаги выполнения|Ожидаемый результат|Фактический результат|Статус|Исполнитель|Комментарии|
|TC_AUTH_NEG-01|Авторизация заблокированного пользователя|Проверка невозможности входа в систему пользователя с заблокированным статусом|Пользователь имеет статус locked_out_user|ОС: Windows/ macOS Браузер: Chrome URL: https://www.saucedemo.com/|1. Открыть страницу https://www.saucedemo.com/ 2. Ввести логин locked_out_user 3. Ввести единый пароль  secret_sauce 4. Нажать "Login" |Выдается сообщение об ошибке: Sorry, this user has been locked out.|Выдается сообщение об ошибке: Sorry, this user has been locked out.|Passed|QA Engineer| |
|TC_AUTH_NEG-02|Авторизация с несуществующим логином| | | |1. Ввести логин asidaisd_123 2. Ввести пароль secret_sauce 3. Нажать "Login" |Выдается сообщение об ошибке: Username and password do not match any user in this service|Выдается сообщение об ошибке: Username and password do not match any user in this service|Passed|QA Engineer| |
|TC_AUTH_NEG-03|Авторизация с несуществующим паролем| | | |1. Ввести логин standard_user 2. Ввести пароль password 3. Нажать "Login" |Выдается сообщение об ошибке: Username and password do not match any user in this service|Выдается сообщение об ошибке: Username and password do not match any user in this service|Passed|QA Engineer| |
|TC_AUTH_NEG-04|Авторизация с пустыми полями| | | |1. Оставить поля пустыми 2. Нажать "Login"|Выдается сообщение об ошибке: Epic sadface: Username is required|Выдается сообщение об ошибке: Epic sadface: Username is required|Passed|QA Engineer| |
|TC_AUTH_NEG-05|Авторизация с валидным логином и паролем, но с добавлением лишнего пробела после ввода логина| | | |1. Ввести логин standard_user_ 2. Ввести пароль secret_sauce 3. Нажать "Login"|Выдается сообщение об ошибке: Username and password do not match any user in this service|Выдается сообщение об ошибке: Username and password do not match any user in this service|Passed|QA Engineer| |
|TC_AUTH_NEG-06|Авторизация с пустым логином| | | |1. Оставить пустым поле логина 2. Ввести пароль secret_sauce 3. Нажать "Login"|Выдается сообщение об ошибке: Username and password do not match any user in this service|Выдается сообщение об ошибке: Username and password do not match any user in this service|Passed|QA Engineer| |

<p align="center">
  <img src="https://i.postimg.cc/d1N5NwP6/Скриншот_1.png" alt="Скриншот">
</p>

<p align="center">
  <img src="https://i.postimg.cc/SRXDw3k7/Скриншот_2.png" alt="Скриншот">
</p>

<p align="center">
  <img src="https://i.postimg.cc/7hCmpdw2/Скриншот_3.png" alt="Скриншот">
</p>

<p align="center">
  <img src="https://i.postimg.cc/4yKBrqsc/Скриншот_4.png" alt="Скриншот">
</p>
