# GIT 

Task 1: JSON
-

1. Создать внешний репозиторий c названием JSON:
```bash
[Repositories] > [New] > [Create repository]
```
2. Клонировать репозиторий JSON на локальный компьютер:
```bash
git clone "link"
```
3. Внутри локального JSON создать файл “new.json”:
```bash
cd json
touch new.json
```
4. Добавить файл под гит:
```bash
git add new.json
```
5. Закоммитить файл:
```bash
git commit -m "new.json"
```
6. Отправить файл на внешний GitHub репозиторий:
```bash
git push
```
7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON:
```bash
cat > new.json
[Enter]
{
    "Name": "Vladimir Semenovich",
    "Age": 39,
    "Number of pets": 1,
    "Future desired salary": 150000
}
[Enter]
[Ctrl + C]
```
8. Отправить изменения на внешний репозиторий:
```bash
git commit -am "edit new.json"
git push
```
9. Создать файл preferences.json:
```bash
touch preferences.json
```
10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON:
```bash
cat > preferences.json
[Enter]
{
"Favorite movie": "As Good as It Gets",
"Favorite TV series": "Friends",
"Favorite food": "Barbecue",
"Favorite season": "Spring",
"The country you would like to visit": "Argentina"
}
[Enter]
[Ctrl + C]
```
11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON:
```bash
cat > sklls.json
[Enter]
{
"Hard skills by Vadim Ksendzov's course":
[
"Postman",
"Charles",
"Fiddler",
"DevTools",
"Android studio",
"ADB",
"Terminal Linux",
"SQL",
"Postgres",
"Redis",
"Jmeter",
"Python"
]
}
[Enter]
[Ctrl + C]
```
12. Отправить сразу 2 файла на внешний репозиторий:
```bash
git add .
git commit -m "preferences.json, sklls.json"
git push
```
13. На веб интерфейсе создать файл bug_report.json:
```bash
[Add file] > [Create new file]
```
14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash
[Commit changes] > [Commit changes]
```
15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON:
```bash
[Edit this file]
```
16. Сделать Commit changes (сохранить) изменения на веб интерфейсе:
```bash
[Commit changes] > [Commit changes]
```
17. Синхронизировать внешний и локальный репозиторий JSON:
```bash
git fetch
git merge
```
```bash
git pull
```
---