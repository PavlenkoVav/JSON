JSON
 4. Создать внешний репозиторий c названием JSON. 
 5. Клонировать репозиторий JSON на локальный компьютер : git clone https://github.com/PavlenkoVav/JSON.git
 6. Внутри локального JSON создать файл “new.json” :  touch new.json
 7. Добавить файл под гит : Git add  . 
 8. Закоммитить файл : git commit ( i +  commentn +esc :wq + enter ) 
 9. Отправить файл на внешний GitHub репозиторий : git push 
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON. : cat > new.json 
{
"secondname": "Pavlenko",
"firstname": "Valeriia",
"lastname": "Igorevna",
"age": 24,
"countofpets": 0,
"salary": "500$"
}
CTRL C
 11. Отправить изменения на внешний репозиторий :  git commit -a ( i +  comment +esc :wq + enter ) + git push 
 12. Создать файл preferences.json : touch preferences.json  
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON. : cat > preferences.json 
{
"film" : "Hannibal" ,
"food" : "eggs" ,
"country" : "Norway"
} 
CTRL C

 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON :   cat > skills.json
{
"first" : "TestDocumentation" , 
"second" : "SQL" ,
"third" : "MobileTesting"
}
 CTRL C


 15. Отправить сразу 2 файла на внешний репозиторий. : Git add . + git commit ( i + comment +esc :wq )  + git push
 16. На веб интерфейсе создать файл bug_report.json.  
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON. : git pull + cat > bug_report.json
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 20. Синхронизировать внешний и локальный репозиторий JSON :  git pull 
