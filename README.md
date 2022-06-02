# TXT
 1. Создать внешний репозиторий c названием TXT.
>**https://github.com/Tellim235/TXT.git**
 2. Клонировать репозиторий TXT на локальный компьютер.
>**git clone https://github.com/Tellim235/TXT.git**
 3. Внутри локального TXT создать файл “new.txt”.
>**cd TXT**

>**touch new.txt**
 4. Добавить файл под гит.
>**git add new.txt**
 5. Закоммитить файл.
>**git commit -m "add new.txt"**
 6. Отправить файл на внешний GitHub репозиторий.
>**git push**
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
>**vim new.txt**

>**i**
```TXT
Name: Kseniya
Age: 35
Pets: 1
Salary: 300000
```
 8. Отправить изменения на внешний репозиторий.
>**git add new.txt**

>**git commit -m "add new.txt"**

>**git push**
 9. Создать файл preferences.txt
>**touch preferences.txt**
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
>**cat >> preferences.txt**
```TXT
Film: Spider man
Series: Friends
Food: Meat
Season: Summer
Counrty: Korea
```
>**ctrl+c**
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
>**cat >> sklls.txt**
```TXT
1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.
2. Что такое клиент-серверная архитектура.  
3. HTTP Методы запросов на сервер.  
4. Коды ответов HTTP сервера.  
5. Структуры HTTP запросов и ответов.  
6. Что такое JSON, XML. Их структура. 
7. Тестирование API через Postman (JS, автотесты API).
и другие навыки
```
>**ctrl+c**
 12. Сделать коммит в одну строку.
>**git add preferences.txt sklls.txt**

>**git commit -m "add preferences.txt sklls.txt"**
 13. Отправить сразу 2 файла на внешний репозиторий.
>**git push**
 14. На веб интерфейсе создать файл bug_report.txt.
>**Нажать Add file => Create new file , указываем имя файла bug_report.txt**
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
>**В нижней части страницы нажимаем Commit new file**
 18. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
>**Выбрать файл bug_report.txt и нажать "Edit this file"**
```TXT
ID: A1
Title: Нажатие кнопки 'Поиск' на главной странице не предоставляет результат поиска
Steps:
1. Зайти на главную страницу сайта (ссылка на сайт)
2. Ввести текст поиска
3. Нажать кнопку Поиск
Enviroment:
-OS: Windows 10 x64
-Browser: Google Chrome v 100.0.4896.127
Expected result: Нажатие кнопки Поиск выдает результат поиска
Actual result: При нажатии кнопки Поиск ничего не происходит
Severity: Critical
Priority: High
Status: Open
Attachments: ссылка на картинку или видео
```
 20. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
>**В нижней части страницы нажать Commit changes**
 22. Синхронизировать внешний и локальный репозиторий TXT
>**git pull**
