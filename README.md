# JSON 
4. Создать внешний репозиторий c названием JSON.  
 `Github - Repositories - New - Repository name: JSON - поставить галочку у Add Readme file - Cteate repository`  
5. Клонировать репозиторий JSON на локальный компьютер.  
`git clone https://github.com/irinalwnk/JSON.git`  
6. Внутри локального JSON создать файл “new.json”.  
`touch new.json`
7. Добавить файл под гит.  
`git add new.json`
8. Закоммитить файл.  
`git commit -m 'create new.json'`
9. Отправить файл на внешний GitHub репозиторий.  
`git push`
10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.  
`vim new.json`  
Нажать "i" для ввода данных.  
```json  
{"name":"Leshenko Irina",
"age":31,
"cats":1,
"expected salaty":"800$"
}
```
Нажать "Esc" и ввести для выхода из редактора  
	`:wq`  
11. Отправить изменения на внешний репозиторий.  
`git commit -am 'add information in to new.json' ; git pish`  
12. Создать файл preferences.json  
`touch preferences.json `  
13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.  
`vim preferences.json`  
Нажать "i" для ввода данных.   
```json
{
"film": "Lord of the rings",
"series":"Friends",
"food": "Orange",
"season": "Spring",
"country to visit": "Ireland"
}
``` 
Нажать "Esc" и ввести для выхода из редактора   
	`:wq`  
14.  Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON  
`vim skills.json`  
Нажать "i" для ввода данных.   
```json  
{
"Skills":
["QA Testing",
"Terminal",
"Postman",
"Jmeter",
"SQL",
"Android Studio"]
}
```
Нажать "Esc" и ввести для выхода из редактора  
	`:wq`  
15.  Отправить сразу 2 файла на внешний репозиторий.  
`git add . ; git commit -m 'add information in to the files' ; git push`  
16. На веб интерфейсе создать файл bug_report.json.  
`File - Cteate New File - bug_report.json`  
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
`В строку "Commit new file" добавить "Cteate New File - bug_report.json" - Нажать "Commit new file"`  
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.  
`Edit this file - внести информацию в файл  в формате JSON:`
```json
{
  "Description": "Не работает кнопка отправки заказа.",
  
  "steps_to_reproduce":  
  {
  "1.":"Открыть сайт *.",
  
  "2." :"Нажать по ссылке *.",
  
  "3." :"Пролистать до поля *",
  
  "4." :"Ввести значение в поле *.",
  
  "5.":" Попытаться нажать кнопку отправки заказа."},
  
  "ar": "кнопка неактивна.",
  
  "er": "кнопка нажимается, можно сделать заказ."
  } 

```
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
`В строку "Commit new file" добавить "add information" - Нажать "Commit new file"`  
20. Синхронизировать внешний и локальный репозиторий JSON  
`git pull`  

