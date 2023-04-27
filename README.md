# XML
Learning how to use GitHub
<hr>


**1. Создать внешний репозиторий с названием XML**

**2.Клонировать репозиторий XML на локальный компьютер**
```
$ git clone git@github.com:KristinaMarkevich/XML.git
```
**3.Внутри локального XML создать файл “new.xml”**
```
$ touch new.xml
```
**4.Добавить файл под гит**
```
$ git add new.xml
```
**5. Закоммитить файл**
```
$ git commit -m "new.xml"
```
**6. Отправить файл на внешний GitHub репозиторий**
```
$ git push
```
**7. Отредактировать содержание файла “new.xml” - написать информацию о себе**
```
$ cat > new.xml
<info_about_me>
<name>Kristina Markevich </name>
<age>25</age>
<pets><cat>Kuzya</cat></pets>
<future_wanted_salary>400 USD</future_wanted_salary>
</info_about_me>
```
**8. Отправить изменения на внешний репозиторий**
```
$ git add new.xml
$ git commit -m new.xml
$ git push
```
**9. Создать файл preferences.xml**
```
$ touch preferences.xml
```
**10.  В файл preferences.xml” добавить информацию о своих предпочтениях**
```
$ cat > preferences.xml
<prefereces>
<movie>Titanic</movie>
<TV_Show>Breaking bad</TV_Show>
<food>ramen</food>
<season>summer</season>
<country_i'd_like_to_visit> Japan </country i'd like to visit>
</prefereces> 
```
**11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML**
```
$ cat > skills.xml
<list_of_skills>
<skill_1> termimal </skill_1>
<skill_2> SQL</skill_2>
<skill_3> postman</skill_3>
<skill_4> creating bug reports</skill_4>
</list_of_skills>
```
**12. Сделать коммит в одну строку**
```
$ git add . 
$ git commit -m "comment"
```
**13. Отправить сразу 2 файла на внешний репозиторий**
```
$ git push
```
 **14. На веб интерфейсе создать файл [bug_report.txt](https://github.com/KristinaMarkevich/XML/blob/main/bug_report.xml)**
 
 **15. Сделать Commit changes (сохранить) изменения на веб интерфейсе**
 
 **16. На веб интерфейсе модифицировать файл [bug_report.txt](https://github.com/KristinaMarkevich/XML/blob/main/bug_report.xml), добавить баг репорт в формате TXT**
 
 **17. Сделать Commit changes (сохранить) изменения на веб интерфейсе**
 
 **18. Синхронизировать внешний и локальный репозиторий TXT**
 ```
$ git pull
```
