# Test Result

## **Критерии прохождения/провала теста**

### Тест 1
#### Название теста:
Регистрация в BeeMessage.
#### Сценарий тестирования:
1. Открыть приложение; 
2. Нажать кнопку "Create account";
3. Ввести данные;
4. Проверить почту;
5. Подтвердить регистрацию;
6. Нажать кнопку "Save".
#### Ожидаемый результат:
Приложение должно зарегистрировать пользователя, отослать уведомление на почту и  показать уведомление. 
#### Фактический результат:
Приложение зарегистрировало пользователя, отослало уведомление на почту и показало уведомление. 
#### Результат: **ПРОЙДЕН** 
##

### Тест 2
#### Название теста:
Вход в BeeMessage.
#### Сценарий тестирования:
1. Открыть приложение; 
2. Нажать кнопку "Sign in";
3. Ввести данные;
5. Нажать кнопку "Enter".
#### Ожидаемый результат:
Приложение должно авторизовать пользователя в его учетной записи и показать уведомление. 
#### Фактический результат:
Приложение авторизовало пользователя и показало уведомление. 
#### Результат: **ПРОЙДЕН** 
##

### Тест 3
#### Название теста:
Отправка сообщения в чат.
#### Сценарий тестирования:
1. В Main menu нажать кнопку "Chat"; 
2. Ввести сообщение;
3. Нажать кнопку "Send";
#### Ожидаемый результат:
Приложение должно отправить сообщение, отобразить его в чате и  показать уведомление. 
#### Фактический результат:
Приложение отправило сообщение, отобразило его в чате  и показало уведомление. 
#### Результат: **ПРОЙДЕН** 
##

### Тест 4
#### Название теста:
Просмотр и запись личных задач.
#### Сценарий тестирования:
1. В Main menu нажать кнопку "My tasks"; 
2. Ввести задачу;
3. Нажать кнопку "Add";
#### Ожидаемый результат:
Приложение должно отобразить список задач с новой задачей, после добавления задачи показать уведомление. 
#### Фактический результат:
Приложение отображает список задач с новой задаче, показало уведомление о добавлении новой задачи.
#### Результат: **ПРОЙДЕН** 
##

### Тест 5
#### Название теста:
Просмотр задач пользователя.
#### Сценарий тестирования:
1. В Main menu нажать кнопку "Users"; 
2. Нажать на имя пользователя;
#### Ожидаемый результат:
Приложение должно отобразить задачи пользователя.
#### Фактический результат:
Приложение отобразило задачи пользователя
#### Результат: **ПРОЙДЕН** 
##

### Тест 6
#### Название теста:
Добавление задач пользователю.
#### Сценарий тестирования:
1. В задачах пользователя ввести задачу; 
2. Нажать кнопку "Add";
#### Ожидаемый результат:
Приложение должно отобразить список задач пользователя, отобразить новую задачу, показать уведомление. 
#### Фактический результат:
Приложение отобразило список задач пользователя, отобразило новую задачу, показало уведомление о добавлении новой задачи.
#### Результат: **ПРОЙДЕН** 
##

### Тест 7
#### Название теста:
Просмотр всех зарегистрированных пользователей.
#### Сценарий тестирования:
1. В Main menu нажать кнопку "Users"; 
#### Ожидаемый результат:
Приложение должно отобразить список всех зарегистрированных пользователей. 
#### Фактический результат:
Приложение отобразило всех зарегистрированных пользователей.
#### Результат: **ПРОЙДЕН** 
##

### Тест 8
#### Название теста:
Просмотр всех "online" пользователей.
#### Сценарий тестирования:
1. Зайти с другом в приложение.
2. Пройти авторизацию.
3. В Main menu нажать кнопку "Chat"; 
4. Нажать кнопку "Users online";
#### Ожидаемый результат:
Приложение должно отобразить имя вашего аккаунта и аккаунта друга(Возможно больше имен, если в этот момент есть еще "online" пользователи). 
#### Фактический результат:
Приложение отобразило наши имена. 
#### Результат: **ПРОЙДЕН** 
##         

### Тест 9
#### Название теста:
Удаление задач из списка.
#### Сценарий тестирования:
1. В Main menu нажать кнопку "My tasks".
2. Удержать нажатие на поле с задачей.
#### Ожидаемый результат:
Приложение должно удалить задачу из списка, отобразить новый список задач, показать уведомление. 
#### Фактический результат:
Приложение удалило задачу, отобразило новый список, показало ообщение.
#### Результат: **ПРОЙДЕН** 
##    

### Тест 11
#### Название теста:
Проверка установки приложения.
#### Сценарий тестирования:
1. Скачать APK файл;
2. Открыть его;
3. Запустить установку;
4. Открыть приложение.
#### Ожидаемый результат:
Приложение должно установится на устройство и запуститься.
#### Фактический результат:
Приложение установилось на устройство и запустилось.
#### Результат: **ПРОЙДЕН** 
##

### Тест 12
#### Название теста:
Удаление приложения.
#### Сценарий тестирования:
1. Найти приложение в меню устройства;
2. Удержать нажатие на иконке приложения;
3. Переместить приложение в корзину;
4. Подтвердить удаление.
#### Ожидаемый результат:
Приложение должно удалится с устройства.
#### Фактический результат:
Приложение удалилось с устройства.
#### Результат: **ПРОЙДЕН** 
##

### Тест 13
#### Название теста:
Отключение сети Интернет во время работы приложения и отправить сообщение в чате.
#### Сценарий тестирования:
1. Открыть приложение;
2. В Main Menu выбрать "Chat";
3. Отключить мобильные данные;
4. Отправить сообщение;
5. Включить мобильные данные.
#### Ожидаемый результат:
Приложение должно отправить сообщение в чат после включения мобильных данных.
#### Фактический результат:
Приложение отправило сообщение в чат после включения мобильных данных.
#### Результат: **ПРОЙДЕН** 
##

### Тест 14
#### Название теста:
Корректность отображения уведомлений после выключения мобильных данных.
#### Сценарий тестирования:
1. Открыть приложение;
2. В Main Menu выбрать "Chat";
3. Отключить мобильные данные;
4. Отправить сообщение;
#### Ожидаемый результат:
Приложение должно отправить уведомление "ожидайте подключения".
#### Фактический результат:
Приложение показало уведомление "отправлено".
#### Результат: **НЕ ПРОЙДЕН** 
##

### Тест 15
#### Название теста:
Удобство удаления задач.
#### Сценарий тестирования:
1. В Main menu выбрать "My tasks";
2. Удалить задачу.
#### Ожидаемый результат:
Функция удаления должна быть интуитивно понятна пользователем.
#### Фактический результат:
Возникли трудности с удалением.
#### Результат: **НЕ ПРОЙДЕН** 
##

### Тест 16
#### Название теста:
Вход в систему после активации аккаунта через почту.
#### Сценарий тестирования:
1. Пройти регистрацию аккаунта (Create account);
2. Перейти к авторизации (Sign in);
3. Ввести данные; 
4. Нажать кнопку "Enter".
#### Ожидаемый результат:
Приложение не должно войти в систему и показать уведомление.
#### Фактический результат:
Приложение не вошло в систему и показало уведомление.
#### Результат: **ПРОЙДЕН** 
##

### Тест 17
#### Название теста:
Попытка войти в систему под старым паролем (после смены).
#### Сценарий тестирования:
1. Перейти к авторизации(Sign in);
2. Ввести почту(Mail);
3. Нажать кнопку "Forgot password";
4. Проверить почту;
5. Перейти по ссылке в сообщении;
6. Ввести новый пароль;
7. Ввести старые данные в окне "Sign in";
8. Нажать кнопку "Enter".
#### Ожидаемый результат:
Приложение не должно войти в систему и показать уведомление.
#### Фактический результат:
Приложение не вошло в систему и показало уведомление.
#### Результат: **ПРОЙДЕН** 
##

### Тест 18
#### Название теста:
Установка на версии ОС Android 4.4+.
#### Сценарий тестирования:
1. Скачать APK;
2. Установить приложение;
3. Запустить приложение;
4. Проверить основные функции приложения.
#### Ожидаемый результат:
Приложение должно работать без ошибок.
#### Фактический результат:
Приложение работает без ошибок. Тестирование было проведено на устройствах с ОС Android 4.4 , Android 5.0, Android 6.0
#### Результат: **ПРОЙДЕН** 
##

### Тест 19
#### Название теста:
Проверка утечки памяти приложения
#### Сценарий тестирования:
1. Запускаем приложение;
2. Открываем Android monitor;
3. Ждем 15 минут
#### Ожидаемый результат:
За 15 минут теста потребление памяти не должно расти (после достижения среднего значения).
#### Фактический результат:
![](https://github.com/PcheLL/BeeMessage/blob/master/Document/Test%20Plan/TestMemory.png)
Из теста видно, что утечки памяти за 15 минут нет. Из доступных 48мб было занято в среднем 34мб.
#### Результат: **ПРОЙДЕН** 
##