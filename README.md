# Check-list
**Чек лист** – это документ, который содержит **список проверок**. Он менее подробен по содержанию, в нем отсутствуют шаги, как в тест кейсе. Один пункт чек листа описывает одно направление для проверки. Чек лист содержит:   
- список проверок с требуемой степенью детализации
- статус проверок (результат)
- сборка, на которой проводилось тестирование
- тестовое окружение (если применимо)
- кто проводил тестирование   
### Пример:
Проверка диалогового окна "Масштаб" (Меню-> Вид-> Масштаб) программы   
1. Проверка открытия окна "Масштаб"  
2. Проверка масштаб 200%
3. Проверка масштаб 150%
4. Проверка масштаб 125%
5. Проверка масштаб 100%
6. Проверка масштаб 75%
7. Проверить масштаб по ширине страницы
8. Проверить масшатб Страница целиком
9. Изменить значение в поле Доля через стрелочки вверх и вниз
10. В поле Доля ввести недопустимые символы (кроме цифр), пробел
11. Проверка кнопки Ок
12. Проверка кнопки Отмена  

### Поиск - чит лист
Введение:  
1. Поиск ищет по всем полям, указанным в ТЗ  
2. Поиск НЕ ищет по тем полям, которые НЕ указаны в ТЗ  
3. Релевантность выдачи  
4. Контекст поиска  
5. Регистронезависимость поиска  
6. Ищет ли по включению или полному соответствию  
7. Два слова из одного поля  
8. Два слова из разных полей  
9. Опечатки  
10. Неправильная раскладка  
11. Другой язык  
12. Спецсимволы  
13. Эмоджи  
14. Тримаются ли открывающие и закрывающие пробелы  
15. Пустое поле  
16. Пробелы в поле  
17. Нижняя граница  
18. Верхняя произвольная граница  
19. Верхняя граница на выходе  
20. Поиск технологической границы  
### Что надо узнать  
1. По каким полям поиск должен работать / по каким нет  
2. Ищет по включению или полному соответствию?  
3. Регистрозависимый ли поиск?  
4. Какая максимальная длина поисковой строки?  
5. А если длина превышена, запрос обрезается?  
6. Как работает поиск при пустом запросе?  
### Что надо проверить  
1. Поиск ищет по всем полям, указанным в ТЗ  
2. Поиск НЕ ищет по тем полям, которые НЕ указаны в ТЗ  
3. Релевантность выдачи — то, что я ищу, в начале списка, или в конце?  
4. Учитывается ли контекст поиска — ищу я по всему сайту или только разделу игрушек  
5. Регистронезависимость поиска — найдет ли «Платье», если я ввела «платье»?  
6. Ищет ли по включению или полному соответствию — «ту» найдет мне «туфли»?  
7. Найдет ли 2 слова из одного поля? В любом порядке введенные?  
8. Найдет ли 2 слова из разных полей?  
9. Ошибка в вводе (исправляются ли опечатки, ищет ли похожее)  
10. Исправляет ли система неправильную раскладку?  
11. Ищет ли на разных языках? А если сразу на двух попробовать?  
12. Поиск со спецсимволами работает?  
13. А с эмоджи? Не упадет система при вводе какашки?  
14. Тримаются ли открывающие и закрывающие пробелы  
15. Пустое поле / только пробелы в поле  
16. Нижнюю границу (от скольких символов ищет)  
17. Верхнюю произвольную границу — указанную в ТЗ  
18. Верхнюю границу на выходе  
19. Поиск технологической границы — ввести «войну и мир», 100 млн символов  

## 1. Поиск ищет по всем полям, указанным в ТЗ
- Оставить поле пустым  
- Вбить кириллицу / латиницу  
- Большую строку  
- Всяко потыкать поиск по названию (а если часть названия указать, а если с опечаткой...)    
