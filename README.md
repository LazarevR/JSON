# JSON
Group_30 Homework

**JSON**

1. Создать внешний репозиторий c названием JSON.

	`Repositories -> New -> "Repository name": Json -> Create perository`

2. Клонировать репозиторий JSON на локальный компьютер.

	`git clone git@github.com:LazarevR/JSON.git`

3. Внутри локального JSON создать файл “new.json”.

	`touch new.json`

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

	`[{ "ФИО":"Ruslan Lazarev", "Возраст":"31", "Количество домашних животных":"0", "Будущая желаемая зарплата":"$4000" }]`

8. Отправить изменения на внешний репозиторий.
	```
	git status
	git add new.json
	git commit -m "edit the new.json file"
	git push
	```	
9. Создать файл preferences.json

	`touch preferences.json`

10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

	`[{ "Любимый фильм":"Вечное сияние чистого разума", "Любимый сериал":"Californication", "Любимая еда":"Солянка", "Любимое время года":"Весна", "Страна, которую хотели бы посетить":"Норвегия" }]`

11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.

	`touch sklls.json`

	Файл редактировал в Sublime Text:
	```
	[{ "Skills":["Git bash/Terminal", "Git", "Postman", "Charles Proxy", "JavaScript", "SQL", "Selenium+Python"] }]
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
	В поле описания: create my first but_repots.json
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
	В поле заголовка: можно оставить пустым, а можно указать Update but_report.json
	В поле описания: "added first bug report"
	Нажать на кнопку "Commit changes"
	```
17. Синхронизировать внешний и локальный репозиторий JSON.

	`git pull`
