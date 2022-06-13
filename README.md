# json_1
JSON
 4. Создать внешний репозиторий c названием JSON.
json_1

 5. Клонировать репозиторий JSON на локальный компьютер.
git clone https://github.com/svetylka/json_1.git
 6. Внутри локального JSON создать файл “new.json”.
touch new.json
 7. Добавить файл под гит.
git add new.json
 8. Закоммитить файл.
git commit -m "add firct file"
 9. Отправить файл на внешний GitHub репозиторий.
git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
cat >> new.json
{
"Full name": " Tyrchina Svetlna",
"Age": 30,
"Number of pets" : 2
"Future desired salary": 100000
}
 11. Отправить изменения на внешний репозиторий
clear
git add . ; git commit -m "changes json file" ; git push
 12. Создать файл preferences.json
touch preferences.json
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
cat >> references.json
{
"favorite movie": "Призрак",
"favourite TV show": "Ангелы и демоны",
"favourite time of year": "Лето"
}

 14. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
cat >> skills.json
{
"Skills": "Linux, GitHab, Bash, API, HTTP/HTTPs, Mobile testing, SQL"
}

 15. Отправить сразу 2 файла на внешний репозиторий.

 git add . ; git commit -m "add two files" ; git push

 16. На веб интерфейсе создать файл bug_report.json.

Создали файл bug_report.json в gitHab в веб интерфейсе

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

сделали коммит в веб интерфейсе

 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

Сделали модификацию в веб интерфейсе

 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

Сделали  Commit changes (сохранить) изменения на веб интерфейсе под 111
 20. Синхронизировать внешний и локальный репозиторий JSON

git fetch
git pull
