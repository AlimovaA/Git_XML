# Git_XML
## XML
21. Создать внешний репозиторий c названием XML.
> Создаем репозиторий на GitHub - Git_XML
22. Клонировать репозиторий XML на локальный компьютер.
> git clone git@github.com:AlimovaA/Git_XML.git
23. Внутри локального XML создать файл “new.xml”.
> cd Git_XML - заходим в папку main
> touch new.xml - создаем файл
24. Добавить файл под гит.
> git add new.xml
25. Закоммитить файл.
> git commit -a -m "add first file"
26. Отправить файл на внешний GitHub репозиторий.
> git push
27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
> cat >> new.xml
> <?xml version-"1.0" encoding="UTF-8"?>
> <new>
> <ФИО>Алимова_Альбина_Руслановна</ФИО>
> <Возраст>26</Возраст>
> <Колчество_домашних_животных>1</Колчество_домашних_животных>
> <Будущая_желаемая_зарплата>150000</Будущая_желаемая_зарплата>
> </new>
> CTRL+D для выхода из режима редактирования  
28. Отправить изменения на внешний репозиторий.
> git add . ; git commit -a -m "Добавлена информация о себе" ; git push
29. Создать файл preferences.xml
> touch preferences.xml
30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
> cat >> preferences.xml
> <?xml version-"1.0" encoding="UTF-8"?>
> <preferences>
> <Любимый_фильм>Титакник</Любимый_фильм>
> <Любимый_сериал>Ведьмак</Любимый_сериал>
> <Любимая_еда>ризотто</Любимая_еда>
> <Любимое_время_года>лето</Любимое_время_года>
> <Страна_которую_хотели_бы_посетить>Португалия</Страна_которую_хотели_бы_посетить>
> </preferences>
> CTRL+D для выхода из режима редактирования  
31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
> cat >> skills.xml
> <?xml version-"1.0" encoding="UTF-8"?>
> <skills>
> <QA>Terminal_Linux, Git, GitHub, API, HTTP/HTTPS, Web testing, Mobile testing, SQL, JMeter</QA>
> </skills>
> CTRL+D для выхода из режима редактирования  
32. Сделать коммит в одну строку.
> git add . ; git commit -a -m "added preferences and skills files"
33. Отправить сразу 2 файла на внешний репозиторий.
> git push
34. На веб интерфейсе создать файл bug_report.xml.
> Создаем файл на GitHub - bug_report.xml
35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
> bug_report.xml коммитим на GitHub
36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
> Модифицируем на GitHub файл bug_report.xml
> <?xml version-"1.0" encoding="UTF-8"?>
> <bug_report>
> <ID>Т111</ID>
> <Title>Невозможность редактирования комментария по ролью Редактор</Title>
> <Module>Комментарии</Module>
> <Program_version>10</Program_version>
> <Environment>UAT</Environment>
> <Severity>Medium</Severity>
> <Priority>High</Priority>
> <Status>Open</Status>
> <Author>Tester</Author>
> <Appointed_to>Developer</Appointed_to>
> <Steps>123</Steps>
> <Actual_result>Невозможность редактирования комментария по ролью Редактор</Actual_result>
> <Expected_Result>Редактор может редактировать комментарии</Expected_Result>
> <Applications>Видео</Applications>
> </bug_report>
37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
> Сделать коммит bug_report.xml на GitHub
 38. Синхронизировать внешний и локальный репозиторий XML
> git fetch
> git pull
