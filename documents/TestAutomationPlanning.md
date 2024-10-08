# План автоматизации

## 1. Перечень автоматизируемых сценариев

1. Успешная оплата тура "Путешествие дня" при валидном* заполнении полей формы "Оплата по карте" по действующей карте  
   (номер карты заполнен с пробелами после каждых 4 символов) 
   Ожидаемый результат: появление сообщения об успешной оплате тура
2. Успешная оплата в кредит тура "Путешествие дня" при валидном* заполнении полей формы "Кредит по данным карты" по
   действующей карте(номер карты заполнен с пробелами после каждых 4 символов) 
   Ожидаемый результат: появление сообщения об успешном получении кредита
3. Отказ в оплате тура "Путешествие дня" при валидном* заполнении полей формы "Оплата по карте" по declined карте(номер
   карты заполнен с пробелами после каждых 4 символов) 
   Ожидаемый результат: появление сообщения об отказе в оплате тура
4. Отказ в кредите на покупку тура "Путешествие дня" при валидном* заполнении полей формы "Кредит по данным карты" по
   declined карте (номер карты заполнен с пробелами после каждых 4 символов) 
   Ожидаемый результат: появление сообщения об отказе в получении кредита
5. Заполнение всех полей валидными* данными формы "Оплата по карте" тура "Путешествие дня" с последующим переключением
   на форму "Кредит по данным карты" 
   Ожидаемый результат: форма переключится, поля останутся заполненными теми же данными
6. Заполнение всех полей валидными* данными формы "Кредит по данным карты" тура "Путешествие дня" с последующим
   переключением на форму "Оплата по карте" 
   Ожидаемый результат: форма переключится, поля останутся заполненными теми же данными
7. Заполнение поля "Номер карты" номером действующей карты без пробелов, остальные поля заполнены валидно* в форме"
   Оплата по карте" тура "Путешествие дня" 
   Ожидаемый результат: появление сообщения об успешной оплате тура
8. Оставление поля "Номер карты" пустым, остальные поля заполнены валидно* в форме "Оплата по карте" тура "Путешествие
   дня" 
   Ожидаемый результат: под полем "Номер карты" появиться предупреждение о необходимости заполнить поле
9. Заполнение поля "Номер карты" 12 рандомными цифрами(т.е.меньше 16), остальные поля заполнены валидно* в форме "Оплата по карте"
    тура "Путешествие дня" 
    Ожидаемый результат: появление сообщения о неверном формате
10. Заполнение поля "Номер карты" 19 рандомными цифрами, остальные поля заполнены валидно* в форме "Оплата по карте"
    тура "Путешествие дня" 
    Ожидаемый результат: появление сообщения о неверном формате
11. Заполнение поля "Номер карты" 20 рандомными цифрами, остальные поля заполнены валидно* в форме "Оплата по карте"
    тура "Путешествие дня" 
    Ожидаемый результат: под полем "Номер карты" появится предупреждение о недопустимой длине поля
12. Заполнение поля "Номер карты" 16 рандомными цифрами, остальные поля заполнены валидно* в форме"
    Оплата по карте" тура "Путешествие дня" 
    Ожидаемый результат: под полем "Номер карты" появится сообщение "Ошибка! Банк отказал в проведении операции"
13. Оставление поля "Месяц" пустым, остальные поля заполнены валидно* в форме "Оплата по карте" тура "Путешествие дня"
    Ожидаемый результат: под полем "Месяц" появиться предупреждение о необходимости заполнить поле
14. Заполнение поля "Месяц" номером с 1 до 9, остальные поля заполнены валидно* в форме "Оплата по карте" тура"
    Путешествие дня" 
    Ожидаемый результат: появится предупреждение о неверном формате
15. Заполнение поля "Месяц" 3 цифрами, остальные поля заполнены валидно* в форме "Оплата по карте" тура "Путешествие
    дня" 
    Ожидаемый результат: удаление последней цифры в поле "Месяц"
16. Заполнение поля "Месяц" значением 00, остальные поля заполнены валидно* в форме "Оплата по карте" тура "Путешествие
    дня" 
    Ожидаемый результат: под полем "Месяц" появится предупреждение о неверном формате
17. Заполнение поля "Месяц" значением 01, остальные поля заполнены валидно* в форме "Оплата по карте" тура "Путешествие
    дня" 
    Ожидаемый результат: появление сообщения об успешной оплате тура
18. Заполнение поля "Месяц" значением 13, остальные поля заполнены валидно* в форме "Оплата по карте" тура "Путешествие
    дня" 
    Ожидаемый результат: под полем "Месяц" появится предупреждение "Неверно указан срок действия карты"
19. Заполнение поля "Месяц" двумя рандомными символами(не цифрами), остальные поля заполнены валидно* в форме "Оплата по
    карте" тура "Путешествие дня" 
    Ожидаемый результат: под полем "Месяц" появится предупреждение о невалидном значении
20. Оставление поля "Год" пустым, остальные поля заполнены валидно* в форме "Оплата по карте" тура "Путешествие дня" 
    Ожидаемый результат: под полем "Год" появится предупреждение о необходимости заполнить поле
21. Заполнение поля "Год" предыдущим годом, остальные поля заполнены валидно* в форме "Оплата по карте" тура"
    Путешествие дня" 
    Ожидаемый результат: под полем "Год" появится предупреждение "Истёк срок действия карты"
22. Заполнение поля "Год" текущим годом и поля "Месяц" текущим месяцем, остальные поля заполнены валидно* в форме"
    Оплата по карте" тура "Путешествие дня" 
    Ожидаемый результат: появление сообщения об успешной оплате тура
23. Оставление поля "Владелец" пустым, остальные поля заполнены валидно* в форме "Оплата по карте" тура "Путешествие
    дня" 
    Ожидаемый результат: под полем "Владелец" появится предупреждение о необходимости заполнить поле
24. Заполнение поля "Владелец" в нижнем регистре, остальные поля заполнены валидно* в форме "Оплата по карте" тура"
    Путешествие дня" 
    Ожидаемый результат: автозаполнение поля "Владелец" в верхнем регистре
25. Заполнение поля "Владелец" с дефисами в начале и в конце, остальные поля заполнены валидно* в форме "Оплата по
    карте" тура "Путешествие дня" 
    Ожидаемый результат: автоудаление лишних символов в поле "Владелец"
26. Заполнение поля "Владелец" кириллицей, остальные поля заполнены валидно* в форме "Оплата по карте" тура "Путешествие
    дня" 
    Ожидаемый результат: под полем "Владелец" появится предупреждение о невалидном значении
27. Заполнение поля "Владелец" рандомными спецсимволами, остальные поля заполнены валидно* в форме "Оплата по карте"
    тура "Путешествие дня" 
    Ожидаемый результат: под полем "Владелец" появится предупреждение о неверном формате
28. Оставление поля "CVC/CVV" пустым, остальные поля заполнены валидно* в форме "Оплата по карте" тура "Путешествие дня" 
    Ожидаемый результат: под полем "CVC/CVV" появится предупреждение о необходимости заполнить поле
29. Заполнение поля "CVC/CVV" 2 рандомными цифрами, остальные поля заполнены валидно* в форме "Оплата по карте" тура"
    Путешествие дня" 
    Ожидаемый результат: под полем "CVC/CVV" появление сообщения о неверном формате
30. Заполнение поля "CVC/CVV" 3 цифрами "0", остальные поля заполнены валидно* в форме "Оплата по карте"
    тура "Путешествие дня" 
    Ожидаемый результат: под полем "CVC/CVV" появление сообщения о неверном формате

## 2. Перечень используемых инструментов с обоснованием выбора

1. **IDE:** *IntelliJ IDEA*
2. **Язык программирования:** *Java*
3. **Система сборки:** *Gradle* 
   Легче настраивать зависимости по сравнению с Maven
4. **Тестовая среда:** *TestNG* 
   Имеет, по сравнению с JUnit, больше аннотаций для управления состоянием SUT (например @BeforeSuite, @AfterSuite), может разбивать тесты на наборы тестов (suite) и имеет больше возможностей по параметризации тестов
5. **Система репортинга:** *Allure* 
   Более сложные системы репортинга будут излишни
6. **Фреймворк для frontend тестирования:** *Selenide* 
   Популярный и простой инструмент для UI тестов
7. **Фреймворки для backend тестирования:** 
   *REST Assured* 
   Популярный инструмент для отправки REST запросов
   *Gson* 
   Фреймворк для генерации body запросов при API тестирования
   *DBUtils* 
   Простой инструмент для проверки состояния БД
8. **Дополнительные фреймворки:**
   *Java Faker* 
   Простой инструмент для генерации тестовых данных
   *Lombok* 
   Фреймворк для автогенерации кода с целью улучшить читаемость тестов

## 3. Перечень и описание возможных рисков при автоматизации

1. Так как тестируется функционал фичи "Путешествие дня", данные для тестов должны быть не "захардкоренными"
2. Заполнение полей "Месяц" и "Год" должно быть не "захардкоренными" и изменяться с течением времени
3. Из-за требования совместимости с двумя БД: MySQL, PostgreSQL, могут возникнуть проблемы с разностью диалектов SQL
4. Из-за требования совместимости с двумя БД: MySQL, PostgreSQL, создается дополнительная трудность с настройкой SUT
5. Поскольку в качестве банковского сервиса выступает заглушка, есть риск что, при подключении реальной системы появятся новые не выявленные дефекты
6. После каждого прогона тестов необходимо очистить БД от записей

## 4. Интервальная оценка с учётом рисков (в часах)

- Настройка SUT, создание дата-хелперов и page object: 16 - 20 часов
- Написание автотестов: 16 - 20 часов
- Создание баг-репортов и отчёта по результатам тестирования: 12 - 18 часов
- Отчёт по результатам автоматизации: 6 - 10 часа

Всего: 50 - 68 часов

## 5. План сдачи работ (когда будут авто-тесты, результаты их прогона и отчёт по автоматизации)

- Готовность авто-тесты - 12.09.2024
- Баг-репорты и отчёт по результатам тестов - 16.09.2024
- Отчёт по результатам тестирования - 20.09.2024
