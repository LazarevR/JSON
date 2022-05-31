# JSON
Group_30 Homework

1. Создать внешний репозиторий c названием JSON.

	`Repositories -> New -> "Repository name": Json -> Create repository`

2. Клонировать репозиторий JSON на локальный компьютер.

	`git clone git@github.com:LazarevR/JSON.git`

3. Внутри локального JSON создать файл “new.json”.
	```
	cd json
	touch new.json
	```
4. Добавить файл под гит.
	```
	git add new.json
	git status
	```
5. Закоммитить файл.

	`git commit -m "add first new.json file"`

6. Отправить файл на внешний GitHub репозиторий.

	`git push`

7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
	```
	  {
	    "data" : {
	      "Name" : "Ruslan",
	      "Surname" : "Lazarev",
	      "Patronymic" : null,
	      "Age" : "31"
	    },
	    "addition" : {
	    "Pets" : "0",
	    "Salary" : "$3000"
	    }
	  }
	```
8. Отправить изменения на внешний репозиторий.
	```
	git status
	git add new.json
	git commit -m "edit the new.json file"
	git push
	```
	Или
	```
	git checkout main
	git add new.json
	git commit -m "edit the new.json file"
	git push
	```
9. Создать файл preferences.json

	`touch preferences.json`

10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
	```
	{
	   "favorites": {
	      "Movie": "Вечное сияние чистого разума",
	      "TvSeries": ["Californication", "Friends"],
	      "Food": "Солянка",
	      "Season": "Весна"
	   },
	   "countriesToVisit": ["Норвегия", "Финляндия"]
	}
	```
11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.

	`touch sklls.json`

	Файл редактировал в Sublime Text:
	```
	{ 
	  "Skills":
	  [ 
	    "Базовая теория SDLC, STLC",
	    "Клиент-серверная архитектура",
	    "HTTP методы запросов на сервер",
	    "Коды ответов HTTP сервера",
	    "Структуры HTTP запросов и ответов",
	    "JSON",
	    "XML",
	    "Postman: тестирование API",
	    "Снятие и чтение логов c внешнего сервера",
	    "Charles и Fidler: сниффинг http web трафика, перехват мобильного трафика",
	    "Dev Tools веб браузеров",
	    "VPN",
	    "Мобильное тестирование",
	    "Особенность iOS, Android, гайдлайны",
	    "Android Studio: сборка android приложений",
	    "ADB (управление андройд девайсами)",
	    "Настройка прокси и vpn на iOS и Android",
	    "Linux Terminal",
	    "Основы bash скриптинг",
	    "Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)",
	    "База данных Postgres",
	    "Нереляционная база данных Redis",
	    "Нагрузочное тестирование в Jmeter"
	  ] 
	}
	```
12. Отправить сразу 2 файла на внешний репозиторий.
	```
	git add preferences.json sklls.json
	git commit -m "add preferences.json , sklls.json"
	git push
	```
13. На веб интерфейсе создать файл bug_report.json.

	`Repositories -> JSON -> Add file -> Create new file -> "Name your file": bug_report.json`

14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	```
	Блок "Commit new file"
	В поле заголовка: create bug_report.json
	В поле описания: create my first bug_report.json
	Нажать на кнопку "Commit changes"
	```
15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
	```
	Repositories -> JSON -> bug_report.json -> Edit this file (*иконка карандаша*)
	Приступить к редактированию файла в поле "Edit file"
	```
16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	```
	Блок "Commit changes"
	В поле заголовка: можно оставить пустым, а можно указать Update bug_report.json
	В поле описания: "added first bug report"
	Нажать на кнопку "Commit changes"
	```
17. Синхронизировать внешний и локальный репозиторий JSON.

	`git pull`
