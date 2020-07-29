# Задача "Внедрение автоматизации"

### Перечень автоматизируемых сценариев

1. m01.01 Меню "Вклады" доступно на странице "Карты"
2. m01.02 Меню "Вклады" доступно на странице "Кредиты"
3. m01.03 Меню "Вклады" доступно на странице "Ипотека"
4. m01.04 Меню "Вклады" доступно на странице ""Вклады"
5. m01.05 Меню "Вклады" доступно на странице "Инвестиции"
6. m01.06 Меню "Вклады" доступно на странице "Премиум"
7. m01.07 Меню "Вклады" доступно на странице "Самозанятые"
8. m01.08 Меню "Вклады" доступно на странице "Онлайн-банк"
9. m02.01 Из пункта меню "Накопилка" происходит переход на страницу "Накопительный счет «Накопилка»"
10. s01.01 Страница "Накопительный счет «Накопилка»"
11.	s01.01.01 Доступна кнопка "Заполнить заявку"
12.	s01.01.02 Клик по кнопке "Заполнить заявку" открывает страницу «Накопилка»
13.	s01.02.01 На странице «Накопилка» доступны поля "Имя", "Мобильный телефон", 
		чек-бокс "Согласие на обработку"
14.	s01.02.01 После заполнения валидными данными полей "Имя", "Мобильный телефон" 
		и установки чек-бокса "Согласие на обработку", кнопка "Мы перезвоним" - доступна.
15.	s01.02.01 После заполнения валидными данными полей "Имя", "Мобильный телефон" 
		и установки чек-бокса "Согласие на обработку", кнопка "Мы перезвоним" - доступна.
16.	s01.02.* После заполнения невалидными данными полей "Имя", "Мобильный телефон", 
		кнопка "Мы перезвоним" - недоступна.
		
### Перечень используемых инструментов с обоснованием выбора
1. JUnit5 + Selenide + Allure - сценарии достаточно простые, реализация не займет много времени. 
	Выполнение выполнение всего набора сценариев будет значительно быстрее мануального варианта.
	
### Перечень необходимых разрешений/данных/доступов от банка
1. Разрешение на доступ к сайту инструментами тестирования

### Перечень и описание возможных рисков при автоматизации
1. Недоступность сайта (технические работы)
2. Изменение дизайна сайта
3. Изменения, вязанные с самим предоставляемы продуктом (вкладом)
 
### Перечень необходимых специалистов для автоматизации
1. Инженер AQA - написание сценариев
2. Тестировщик - исполнение и анализ результатов

### Интервальная оценка с учётом рисков (в часах)
1. 4 часа разработка, 2 часа выполнение и анализ
