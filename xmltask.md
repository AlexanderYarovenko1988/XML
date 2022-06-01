# XML
 1. Создать внешний репозиторий c названием XML.
>GitHub -> Create New Repository XML
 2. Клонировать репозиторий XML на локальный компьютер.
>git clone git@github.com:AlexanderYarovenko1988/XML.git
 3. Внутри локального XML создать файл “new.xml”.
>cd XML && touch new.xml
 4. Добавить файл под гит.
>git add new.xml
 5. Закоммитить файл.
>git commit -m "newfile"
 6. Отправить файл на внешний GitHub репозиторий.
>git push
 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
>vim new.xml
>><?xml version="1.0"?>
>>     <INFO>
>>        <NAME>Alexander Yrovenko</NAME>
>>        <AGE>34</AGE>
>>        <PETS>0</PETS>
>>        <SALARY>1000</SALARY>
>>    </INFO>
 8. Отправить изменения на внешний репозиторий.
>git commit -am "change xml" && git push
 9. Создать файл preferences.xml
>touch preferences.xml
 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
>vim preferences.xml
>>    <?xml version="1.0"?>
>>    <INFO>
>>        <FILM>Patriot</FILM>
>>        <SERIES>University<</SERIES>
>>        <FOOD>Cheeseburger</FOOD>
>>        <SEASON>Autumn</SEASON>
>>        <COUNTRY>Canada</COUNTRY>
>>    </INFO
 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
>vim skills.txt
>>    <?xml version="1.0"?>
>>    <INFO>
>>        <SKILLS>The best skills</SKILLS>
>>    </INFO>
 12. Сделать коммит в одну строку.
>git add . && git commit -m "preferences and skill"
 13. Отправить сразу 2 файла на внешний репозиторий.
>git push
 14. На веб интерфейсе создать файл bug_report.xml.
>GitHub -> add file -> create new file -> bug_report.xml
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. Синхронизировать внешний и локальный репозиторий XML
