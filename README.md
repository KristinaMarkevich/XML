# XML


 **21. Создать внешний репозиторий c названием XML.** 
 **22. Клонировать репозиторий XML на локальный компьютер.**
 ```
 Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github
$ git clone git@github.com:KristinaMarkevich/XML.git
```
 **23. Внутри локального XML создать файл “new.xml”.**
 ```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/XML (main)
$ touch new.xml
```
 **24. Добавить файл под гит.**
 ```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/XML (main)
$ git add new.xml
```
 **25. Закоммитить файл.**
 ```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/XML (main)
$ git commit -m "add new.xml"
```
 **26. Отправить файл на внешний GitHub репозиторий.**
 ```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/XML (main)
$ git push
```
 **27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.**
 ```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/XML (main)
$ cat > new.xml
<Info>
 <Surname>Markevich</Surname>
 <Name>Kristina</Name>
 <Age>28</Age>
 <Cat>1</Cat>
 <Future wanted salary>1000</Future wanted salary>
</Info>
```
 **28. Отправить изменения на внешний репозиторий.**
 ```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/JSON (main)
$ git add new.xml
$ git commit -m "add info"
$ git push
```
 **29. Создать файл preferences.xml**
 **30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.**
 ```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/XML (main)
$ cat > preferences.xml
<preferences>
 <movie>Titanic</movie>
 <TV-Show>Breaking bad</TV-Show>
 <food>ramen</food>
 <season>summer</season>
 <country i'd like to visit>Japan</country i'd like to visit>
</preferences>
```
 **31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML**
 ```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/XML (main)
$ cat > skills.xml
<skills>termimal, SQL, postman, creating bug reports</skills>
```
 **32. Сделать коммит в одну строку.**
 ```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/XML (main)
$ git add .
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/XML (main)
$ git commit -m "add new files"
```
 **33. Отправить сразу 2 файла на внешний репозиторий.**
```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/XML (main)
$ git push
```
 **34. На веб интерфейсе создать файл bug_report.xml.**
 **35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
 **36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.**
 **37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**

 **38. Синхронизировать внешний и локальный репозиторий XML**
 ```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/XML (main)
$ git pull
```
