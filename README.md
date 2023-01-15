## HW_2 : XML

1. Создать внешний репозиторий c названием XML;

2. Клонировать репозиторий XML на локальный компьютер - `git clone`;

3. Внутри локального XML создать файл “new.xml” - `git touch new.xml`;

4. Добавить файл под гит - `git add .`;

5. Закоммитить файл - `git commit -m "create new file"`;

6. Отправить файл на внешний GitHub репозиторий - `git push`;

7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML:

```
<info>
	<about_me>
		<personal>
<name>ALONA</name>
<age>32</age>
<pets>1</pets>
<salary>1000</salary>
<position>QA Engineer</position>
		<currency>USD</currency>
</personal>
	</about_me>
</info>
```

8. Отправить изменения на внешний репозиторий - `git commit -am "updated file" / git push`;

9. Создать файл preferences.xml - `touch preferences.xml`;

10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML:

```
<preferences>
	<favorite_movie> Split </favorite_movie>
	<favorite_series> Friends </favorite_series>
	<favorite_food> Meet </favorite_food>
	<favorite_season>Summer</favorite_season> 
	<favorite_countries>
		<1>Spain<1/>
		<2>Portugal</2>
	<favorite_countries>
</preferences>
```

11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML - `touch skills.xml`:

```
<skills>
<1> Basic theory </1>
<2> What is client-server architecture </2>
<3> HTTP Server Request Methods </3>
<4> HTTP server response codes </4>
<5> HTTP request and response structures </5>
<6> What is JSON, XML. Their structure </6>
<7> API testing via Postman (JS, API autotests) </7>
<8> Removing and reading logs from an external server </8>
<9> Sniffing http web traffic with Charles and Fiddler </9>
  <10> Web Browser Dev Tools (Google Chrome, FireFox)</10>
<11> VPN. (How it works, why you need it, how to use it, tool options) </11>
<12> Mobile Testing</12>
<13> Feature iOS, Android, guidelines</13>
<14> Building iOS apps with XCode </14>
<15> Building Android apps with Android Studio </15>
<16> ADB (android device management) </16>
<17> Proxy and vpn setup on iOS and Android </17>
<18> Sniffing mobile traffic via Charles and Fiddler on iOS and Android</18>
<19> Linux command line (terminal) (copy, create, view, move files on non-GUI servers)</19>
<20> Basic bash scripting, automation of routine tasks on the server </20>
<21> Accessing remote servers </21>
<22> SQL Basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join)</22>
<23> Postgres database (installation, configuration and use) </23>
<24> Non-relational Redis database (installation, configuration and use) </24>
<25> Load testing in Jmeter </25>
<26> Scrum Development Methodology</26>
</skills>
```

12. Сделать коммит в одну строку - `git add . && git commit -m "2 new files"`;

13. Отправить сразу 2 файла на внешний репозиторий - `git push`;

14. На веб интерфейсе создать файл bug_report.xml;

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе:

```
<bug_report>
   <project>Govar</project>
   <version>1.1</version>
   <id> №1 </id>
   <summary> When you click on the 'A to Z' filtering button on the main page of the application, chaotic filtering of lists occurs </summary>
   <step_to_reproduce>
     <1> Open Govar application </1>
     <2> Create 15 lists that will start respectively (A, a, D, 3, :, U, u, SH, SH, 5, @, Ї, ї, -, d) </2>
     <3> Click on the 'A to Z' filter button on the main page of the application </3>
   </step_to_reproduce>
   <actual_result> Lists sorted randomly </actual_result>
   <expected_result>
     <1> Lists are sorted in order: symbols, numbers, Latin letters (upper case first), Cyrillic letters (upper case first)</1>
     <2> Correct order : (-, :, @, 3, 5, A, a, D, d, U, u, Ї, ї, W, w) </2>
   </expected_result>
   <severity>Minor</severity>
   <priority>Low</priority>
   <status>New</status>
   <environment> Samsung A72, Android 12 </environment>
   <author> Alona Bohdanets </author>
</bug_report>
```

16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML;

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе;

18. Синхронизировать внешний и локальный репозиторий XML - `git pull`.
