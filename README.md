# :scroll: Roadmap Java developer [СНГ]

Структурированный список ресурсов для изучения Java, который поможет систематизировать занятия. Основан на личном опыте и самостоятельном изучении данной области.








## Содержание
* [JAVA CORE](#java-core)
* [ALGORYTHMS & DATA STRUCTURES](#algorythms--data-structures)
* [SQL & JDBC](#sql--jdbc)
* [HTTP & SERVLETS](#http--servlets)
* [MAVEN & GRADLE](#maven--gradle)
* [SPRING](#spring)
* [JPA & HIBERNATE](#jpa--hibernate)
* [TESTING](#testing)








## JAVA CORE
Это целый ряд тем. Оновные: **ООП в Java**, **Ветвление, Циклы**, **Массивы**, **Исключения**, **Коллекции**, **Внутренние классы**, **Ввод-вывод**, **Многопоточность**, **Stream API**, и еще разный ряд базовых принципов для использование всего, например основные классы Java (Object) и тд.

:large_orange_diamond: **[Java Core с нуля №1](https://coursehunter.net/course/java-dzhava-dlya-nachinayushchih-s-nulya-do-sertifikata-oracle)**

:large_orange_diamond: **[Java Core продвинутый №2](https://coursehunter.net/course/java-poluchi-chernyy-poyas)**

:large_orange_diamond: **[Java Core детали от Головача](https://www.youtube.com/playlist?list=PLoij6udfBnciBZf7aLRmayAzcisWfAwOY)**

:small_orange_diamond: Книги. Покрывают все особенности языка: **[Философия Java Брюс.Экк](https://t.me/dmytrii_bookshelf)**, **[Java Полное руководство Г.Шилдт](https://t.me/dmytrii_bookshelf)**.

:small_orange_diamond: Книги. Для укрепления знаний и как их использовать должным образом: **[Java Эффективное программирование Д.Блох](https://t.me/dmytrii_bookshelf)**, **[Чистый код Р.Мартин](https://t.me/dmytrii_bookshelf)**.

:small_red_triangle: Для закрепления темы можно потренироваться решая задачи: **[CodingBat](https://codingbat.com/java)**, **[Практические задачи по Java](https://habr.com/ru/post/440436/)**, **[1000 задач на Java](https://github.com/allicen/Java-1000)**, **[Codewars](https://www.codewars.com/kata/search/java?beta=false&order_by=popularity+desc&q=&r%5B%5D=-8&tags=)**.

:large_blue_diamond: Можно еще покрыть пробелы в знаниях через конкретные [лекции Головача](https://youtube.com/playlist?list=PLoij6udfBnciBZf7aLRmayAzcisWfAwOY):

Java Core Процедурное программирование(детали основ), итерация, рекурсия, динамические структуры данных, память в Java:
> *[Additional#1.Dec2013(Сети база) №1](https://youtube.com/playlist?list=PLoij6udfBncjdjKiKlnqikkIjrPLFeivp)*

> *[Additional#2.SQL.Dec2013 №2](https://youtube.com/playlist?list=PLoij6udfBnchYCncZyAzZyFjTGkXIKc7B)*

> *[(Итерация) Java Core December: Procedural Java. Лекция #1 №3](https://youtube.com/playlist?list=PLoij6udfBncigG7gvCLBMd3y0mR_ekCv8)*

> *[(Итерация) Java Core December: Procedural Java. Лекция #2 №4](https://youtube.com/playlist?list=PLoij6udfBncjzPJ4yyysa4Fqz1BrZH3g9)*

> *[(Рекурсия) Java Core December: Procedural Java. Лекция #3 №5](https://youtube.com/playlist?list=PLoij6udfBncifDy8AjaU5wcG_UDPjDSSb)*

> *[(Динамические структуры данных) Java Core December: Procedural Java. Лекция #4 №6](https://youtube.com/playlist?list=PLoij6udfBncijqEUPXhY-NS0ZKWALlN0B)*

> *[(Память в Java) Java Core December: Procedural Java. Лекция #5 №7](https://youtube.com/playlist?list=PLoij6udfBncilPJMzXtsOyUutDDULrtEm)*

Исключения в Java, механика работы исключений, throws + checked/unchecked, иерархия исключений, классификация исключений, "устройство": message, cause, custom fields, сцепленные исключения, стратегии обработки ошибок, try-with-resources (+ suppressed exceptions), multi-catch (+ more precise rethrow):
> *[(Основы иключения) Java Core December: Exceptions. Лекция #6 №1](https://youtube.com/playlist?list=PLoij6udfBncilVuX_R0sBrESIlyfQWVjm)*

> *[(try-with-resources, иерархия) Java Core December: Exceptions. Лекция #7 №2](https://youtube.com/playlist?list=PLoij6udfBnchbxh8ZAY-FPlmj97aCILTY)*

> *[(checked/unchecked, иерархия) Java Core December: Exceptions. Лекция #8 №3](https://youtube.com/playlist?list=PLoij6udfBncjLoxagaF5tGsDp-0XKMyhc)*

> *[() Java Core December: Exceptions. Лекция #9 №4](https://youtube.com/playlist?list=PLoij6udfBnchR-Cc-RB4EUZokLrLlIuWQ)*

Java I/O, byte-ориентированные потоки, char-ориентированные потоки, java-type-ориентированные потоки(классы-адаптеры, классы-декораторы, работа с файловой системой, сериализация и клонирование)
> *[(кодировка) Java Core December: IO. Лекция #10 №1](https://youtube.com/playlist?list=PLoij6udfBncidoWbNwteMhqkE_uxcnWP1)*

> *[(адаптеры/декораторы) Java Core December: IO. Лекция #11 №2](https://youtube.com/playlist?list=PLoij6udfBnchhzsjZkAbhW-V1K5dM-_Xf)*

> *[(адаптеры/декораторы) Java Core December: IO. Лекция #12 №3](https://youtube.com/playlist?list=PLoij6udfBncgBHx7HxK8gAxV-oqT_pOob)*

Java Collection API (big-O notation, Java generics, Iterable / Iterator, Collection API (general), List/ArrayList/LinkedList, Set/List/Map/SortedSet/SortedMap, HashSet/HashMap/hashCode()/equals(), TreeSet/TreeMap/Comparable/Comparator, Collection API (detailed)):
> *[Java Core December:Collections API. Лекция #13 №1](https://youtube.com/playlist?list=PLoij6udfBncjiXKA5ce0hi4b4DIvGymeo)*

> *[(дженерикс) Java Core December:Collections API. Лекция #14 №2](https://youtube.com/playlist?list=PLoij6udfBnciAPeXh5oOGBsQ2c8GlEFu0)*

Продолжение Java IO, Стримы, адаптер/декоратор, клонирование, файловая система:
> *[Java Core December: IO. Лекция #15 №4](https://youtube.com/playlist?list=PLoij6udfBnci29otnZedLq6x-EPlx3I4f)*

Продолжение Java Collection:
> *[(нотации О, equals list, сд хеш сет, мап и тд.) Java Core December: Collections. Лекция #16 №3](https://youtube.com/playlist?list=PLoij6udfBncgIlUdvGNtG2Jp7gXbDMx15)*

> *[(хеш сет и хеш мап, структуры данных) Java Core December: Collections. Лекция #17 №4](https://youtube.com/playlist?list=PLoij6udfBncjAZTDf6Vx281R5Y9mnm93q)*

Многопоточность(введение, Thread/Runnable run(), start(), join(), currentThread(), Модель памяти джавы, монитор, synchronized и многое другое, прерывание потока):
> *[Java Core December: Multithreading. Лекция#18 №1](https://youtube.com/playlist?list=PLoij6udfBncgjoaFqWZSh3L-THigDum7g)*

> *[Java Core December: Multithreading. Лекция#19 №2](https://youtu.be/Y0OaihQCFpg)*

> *[(монитор) Java Core December: Multithreading. Лекция#20 №3](https://youtu.be/8rdrpSSV-wg)*

Объектно-ориентированная Java(конструирование объекта, методы класса Object, перегрузка метода (overload), переопределение метода (overriding), и тд):
> *[(конструирование объекта) Java Core December: OOP. Лекция#21 №1](https://youtu.be/150u5ofBzhc)*

> *[Java Core December: OOP. Лекция#22 №2](https://youtube.com/playlist?list=PLoij6udfBncgtdSaq4nqVNtTqPeyh7rnV)*

> *[(nested/inner) Java Core December: OOP. Лекция#23 №3](https://youtube.com/playlist?list=PLoij6udfBnciXh1_Itg-Hiw9EdGGzwYPE)*

> *[(singleton,enom,multiton) Java Core December: OOP. Лекция#24 №4](https://youtube.com/playlist?list=PLoij6udfBncjjuiZQNFx_b4A5Ygdn1YbS)*

> *[(gof, uml и тд)Java Core December: OOP. Лекция#25 №5](https://youtube.com/playlist?list=PLoij6udfBnch50JMDvipTQmAp-q4Pw6jG)*

:small_blue_diamond: Ролики на Youtube которые могут помочь:
> *[Основы работы со Stream API в Java](https://youtu.be/aC0-KsuPG0I)*









## ALGORYTHMS & DATA STRUCTURES
Нужно уметь применять наиболее эффективные способы решения некоторых задач, а для этого стоит быть в курсе базовых алгоритмов и структур данных: **Algorythms**(Различные сортировки, поиск значений, поиск кратчайшего пути и тд.), **Data Structures**(Списки, Очереди, Мапы, Деревья, Графы и прочее).

:large_orange_diamond: **Книги**: *[Грокаем алгоритмы Б.Адитья](https://t.me/dmytrii_bookshelf)*, *[Алгоритмы. Руководство по разработке. 2-е издание С.Скиена](https://t.me/dmytrii_bookshelf)*, *[Структуры данных и алгоритмы Java Р.Лафоре](https://t.me/dmytrii_bookshelf)*, *[Алгоритмы. Построение и анализ](https://t.me/dmytrii_bookshelf)*.

:large_orange_diamond: **Практика**: 
- вариант 1: заходим на сайт **[LeetCode](https://leetcode.com/)** -> в разделе Explore заходим в лист *[Top Interview Questions](https://leetcode.com/explore/interview/card/top-interview-questions-easy/)* (Easy / Medium / Hard) -> берем задание -> смотрим теги задачи(Related Topics) -> берем книгу и читаем нужную тему.
- вариант 2: читаем книгу -> узнаем новый алгоритм или структуру данных -> пытаемся написать код который делает тоже самое(сортировки, списки, очереди, поиск в ширину).
- вариант 3: решаем задачки по теме на *[Codewars](https://www.codewars.com/kata/search/java?beta=false&order_by=popularity+desc&q=&r%5B%5D=-8&tags=)* или *[HackerRank](https://www.hackerrank.com/domains/java?filters%5Bdifficulty%5D%5B%5D=easy&filters%5Bskills%5D%5B%5D=Java%20%28Basic%29)*.

:small_blue_diamond: Ролики на Youtube которые могут помочь: 
> *[Советы от Ксении по алгоритмам](https://www.youtube.com/watch?v=_NhmGvYs8_g&t=686s)*

> *[Гайды от Жени по структурам данных](https://youtube.com/playlist?list=PLlsMRoVt5sTOKU87z9NhHHRH9nvE5chfH)*

> *[LeetCode гайды от Жени](https://youtube.com/playlist?list=PLlsMRoVt5sTPCbbIW2QZ-hRMW80lymEYR)*








## SQL & JDBC
:large_orange_diamond: **[Базы данных SQL | Основы SQL](https://youtu.be/uGKIXTUjZbc)**

:large_orange_diamond: **[JDBC: Введение в JDBC](https://youtu.be/7LwOvVPavWA)**

:large_orange_diamond: **Практика**:
Чтобы потренироватся, нужно взять пару задач на sql и написать прогу на джава которая будет входить в вашу собственную бд и выполнять там нужные запросы.
- **[SQL-EX.ru](https://www.sql-ex.ru/index.php?Lang=1)**
- **[SQL Academy.org](https://sql-academy.org/ru)**








## HTTP & SERVLETS
:large_orange_diamond: **[Java EE для начинающих](https://youtube.com/playlist?list=PLAma_mKffTOTTFqIkLXgHqVuL6xJhb0mr)**

:large_orange_diamond: **Практика**:
По прохождению курса что выше мы напишем простой сайт, просто стоит повторить написанное за автором. Затем можно добавить свои собственные сервлеты с дополнительной логикой. Также можно добавить свою базу данных, чтобы потренироваться в SQL & JDBC.

:small_blue_diamond: Ролики на Youtube которые могут помочь:
> *[Как работает HTTPS](https://youtu.be/B3j4SS5P8tM)*








## MAVEN & GRADLE
:large_orange_diamond: **[Лекция от Немчинского](https://youtu.be/IAbZVA4tK6M)**

:large_orange_diamond: **[Мавен основы на хабре](https://habr.com/ru/post/77382/)**

:large_orange_diamond: **[Гайд от принга по мавен и градл](http://spring-projects.ru/guides/gradle/)**

:large_orange_diamond: **[Гайд по Градл](https://javarush.ru/groups/posts/2126-kratkoe-znakomstvo-s-gradle)**








## SPRING
Содержит множество компонентов для работы с разнообразными задачами. **Spring MVC**(для разработки веб-приложений), **Spring Data**(для работы с бд), **Spring Security**(для обеспечения безопасности приложений) и тд. Нужно разобраться с базовыми принципами работы с спринг, на чем все строится. Spring Basics(IoC Container, Spring Beans, Bean Configuration, Bean Wiring и тд).

:large_orange_diamond: **[Гайд от алишева Spring Core, MVC](https://youtube.com/playlist?list=PLAma_mKffTOR5o0WNHnY0mTjKxnCgSXrZ)**

:large_orange_diamond: **[Гайд на канале letsCode Spring Boot MVC](https://youtube.com/playlist?list=PLU2ftbIeotGoGSEUf54LQH-DgiQPF2XRO)**

:large_orange_diamond: **[Гайд на канале letsCode Spring Boot Rest](https://youtube.com/playlist?list=PLU2ftbIeotGqSTOVNjT4L3Yfy8jatCdhm)**

:large_orange_diamond: **[Гайд на канале letsCode Spring Boot + Webix](https://www.youtube.com/playlist?list=PLU2ftbIeotGqnwHMFZQz-FrI9w_KGZlw9)** 

:large_orange_diamond: **[Гайд от самого спринга](http://spring-projects.ru/projects/spring-framework/)**

:large_orange_diamond: **[Статья на хабре о Спринге](https://habr.com/ru/post/490586/)**

:large_orange_diamond: **[Статья от Жени](https://proselyte.net/tutorials/spring-tutorial-full-version/)**

:large_orange_diamond: **Практика**:
Написать веб приложение вместе с **[letsCode](https://youtube.com/playlist?list=PLU2ftbIeotGoGSEUf54LQH-DgiQPF2XRO)** / **[alishev](https://www.youtube.com/watch?v=5ePo08sqcpk&list=PLAma_mKffTOR5o0WNHnY0mTjKxnCgSXrZ)** и добавить туда свою логику.








## JPA & HIBERNATE
Спецификация, описывающая, как удобно представлять данные из бд в виде Java объектов. Спецификация не является фреймворком. Она только показывает, что должен уметь реальный фреймворк. А вот фреймворк уже реализует спецификацию. т.е. реальная работа происходит как раз в нем. **Hibernate**(фреймворк, реализующий спецификацию jpf), **ORM**(общее понятие для представления данных из бд в виде java объектов, тогда каждая строка таблицы становится java объектом).
* поискать курсы на эту тему

:large_orange_diamond: **[Статьи Java Persistence API](https://easyjava.ru/data/jpa/)**

:large_orange_diamond: **[Learn JPA & Hibernate](https://www.baeldung.com/learn-jpa-hibernate)**

:large_orange_diamond: **[Статья от Жени](https://proselyte.net/tutorials/hibernate-tutorial/)**






## TESTING
Позволяет убедиться, что вы не допустили ошибку при написании программы. Это как бы набор маленьких программ на Java, которые проверяют правильность вашей основной программы. Также гарантируют, что будущие изменения кода программы не затронут старую логику. Таким образом вы всегда будете уверены, что ничего не сломали. Это серьезно ускоряет разработку, т.к. вам не приходится каждый раз проверять потенциальные баги. **Junit**(Java фреймворк для написания тестов самых разных видов), **Integration**(прекрасно работает в паре с другими фреймворками, например Spring).
* Стоит просто разобратся какие бывают виды тестов на джава, как их писать на Junit, что такое моки и тд.

:large_orange_diamond: **[Статьи на javarash](https://javarush.ru/groups/posts/605-junit)**

:large_orange_diamond: **[Habr Инструменты тестирования Java](https://habr.com/ru/company/otus/blog/596033/)**

:large_orange_diamond: **[Habr Тестирование в Java. JUnit](https://habr.com/ru/post/120101/)**

:large_orange_diamond: **[Гайд от Жени](https://proselyte.net/tutorials/junit/)**






##
:large_blue_diamond: Пробелы в знаниях **SQL & JDBC | HTTP & SERVLETS | MAVEN & GRADLE | SPRING | JPA & HIBERNATE | TESTING** можно покрыть через следующие [лекции от Головача](https://youtube.com/playlist?list=PLoij6udfBncioun9-sBwpkpTit1SIhWko):

Обзор Java EE / Обзор Java 8:
> *[Jun#1.Feb 2014.Additional №1](https://youtube.com/playlist?list=PLoij6udfBnchI9V8WL1wbK67hfuJM9efz)*

> *[Jun#2.Feb 2014.Additional java 8 №2](https://youtube.com/playlist?list=PLoij6udfBnchzRV3L10ECE0tTasKC7GdV)*

**Протокол TCP/IP, протокол HTTP (детально) / многопоточная архитектура HTTP-сервера:**
> *[Junior.February2014.HTTP#1 №1](https://youtube.com/playlist?list=PLoij6udfBnchmBR9V7tdSCsOdtcpPkoxo)*

> *[Junior.February2014.HTTP#2 №2](https://youtube.com/playlist?list=PLoij6udfBncgYO5FS9U-DcBQlix8FF2Q8)*

> *[Junior.February2014.HTTP#3 №3](https://youtube.com/playlist?list=PLoij6udfBncgYO5FS9U-DcBQlix8FF2Q8)*

Servlet API (детально) / Spring MVC:
> *[Junior.February2014.Servlets#3 №1](https://youtube.com/playlist?list=PLoij6udfBncjHaO5s7Ln4w4BLj5FVc49P)*

> *[Junior.February2014.Servlets#4 №2](https://youtube.com/playlist?list=PLoij6udfBncgN40Iu3mSn0SK8T-Ug0ByH)*

> *[Junior.February2014.Servlets#5 №3](https://youtu.be/FCKYkh74BVY)*

> *[Junior.February2014.Servlets#6 №4](https://youtu.be/xHKT8BUZt54)*

**Spring / Maven (детально) / Log4j (детально):**
> *[Junior.February2014.Spring#7 №1](https://youtu.be/7Je56cl0DPE)*

> *[Junior.February2014.Spring#8 №2](https://youtu.be/fcd6ftSLy6s)*

Test Driven Development: JUnit, Mockito (детально):
> *[Junior.February2014 #9_1](https://youtu.be/Khy4TJ1WsWc)*

> *[Junior.February2014 #9_2](https://www.youtube.com/watch?v=H88JLkYrbYE&list=PLoij6udfBncioun9-sBwpkpTit1SIhWko&index=44)*

**SQL / JDBC, connection pool (детально) / JPA 2/Hibernate:**
> *[Junior.February2014.JDBC#9 №1](https://youtube.com/playlist?list=PLoij6udfBncijyqGvf-YLN7hAL0S6nIrG)*

> *[Junior.February2014.JDBC#10 №2](https://youtube.com/playlist?list=PLoij6udfBncgGpXnVrDElGWoIhZMJTzr6)*

> *[Junior.February2014.JDBC#11 №3](https://youtube.com/playlist?list=PLoij6udfBncjQ6nd4jZvelDojOLkdITDq)*

> *[Junior.February2014.JDBC#12 №4](https://youtube.com/playlist?list=PLoij6udfBncgy-PDoYGvxyZ5L5GnqV_2R)*

> *[Junior.February2014.JDBC#13 №5](https://youtube.com/playlist?list=PLoij6udfBncjY0jx7t8Sc-V_qoNZM5gAu)*

> *[Junior.February2014.JDBC#14 №6](https://youtube.com/playlist?list=PLoij6udfBncigW-7YJku0LlQTDlMwmL33)*

> *[Junior.February2014.JDBC#15 №7](https://youtube.com/playlist?list=PLoij6udfBncj5beNvOYxtPhOkAPKVYnFz)*

OOD(SOLID)
> *[Junior.February2014.OOD#16](https://youtube.com/playlist?list=PLoij6udfBncgRuXhcs1gsWhUlS_8ZOLbg)*

GOF(Шаблоны ООП):
> *[Junior.February2014.GOF#17 №1_1](https://youtu.be/3sOIVgubyeQ)*

> *[Junior.February2014.GOF#17 №1_2](https://youtu.be/Cp6mv2F4zPo)*

> *[Junior.February2014.GOF#17 №1_3](https://youtu.be/BCfKV4FFMhQ)*

> *[Junior.February2014.GOF#17 №1_4](https://youtu.be/v7FfJDYvDjQ)*

> *[Junior.February2014.GOF#17 №1_5](https://youtu.be/BCfKV4FFMhQ)*

> *[Junior.February2014.GOF#17 №1_6](https://youtu.be/v7FfJDYvDjQ)*

> *[Junior.February2014.GOF#17 №1_7](https://youtu.be/mfaXG9eVIEA)*

> *[Junior.February2014.GOF#17 №1_8](https://youtu.be/V5a0JC6DVgQ)*

JSF(JavaServer Faces):
> *[Junior.February2014.JSF#18 №1](https://youtube.com/playlist?list=PLoij6udfBncilwh6M-OUWSxef4ZP0PjdY)*

> *[Junior.February2014.JSF#19 №2](https://youtube.com/playlist?list=PLoij6udfBnciRUejKExnW78IDLBt7ntwv)*

> *[Junior.February2014.JSF#20 №3](https://youtube.com/playlist?list=PLoij6udfBncgtTP0V1Z5V6zJeoYmcTpG4)*

WebSockets:
> *[Junior.February2014.WebSockets #21 №1](https://youtube.com/playlist?list=PLoij6udfBncjXbiZ6pmX-chxQNjANR2Gh)*

Apache Maven:
> *[Junior.February2014.Maven#22 №1](https://youtube.com/playlist?list=PLoij6udfBnchZ36TWDdiQsPArx-ON-1GM)*

Log4J:
> *[Junior.February2014.Log4J#23 №1](https://youtube.com/playlist?list=PLoij6udfBncj2KugaIbiLz9ggQzeAtA33)*

JPA 2/Hibernate:
> *[Junior.February2014.JPA2&Hibernate#24](https://youtube.com/playlist?list=PLoij6udfBnci05Oh7IRN-KU3PCjLeYtez)*
##






### Или карта по пунктам
* **ООП**
* **Object** *(знать методы этого класса)*
* **Exception** *(**логирование**, ловля их, обработка в логи)*
* **Collections** **_(больше всего спрашивают, надо очень подробно знать)_**
  - *[ссылка на плейлист Головача по коллекциям](https://youtube.com/playlist?list=PLoij6udfBncgj3VbXvJxUIZOnFFHMv7os)*
  - *[ссылка на плейлист с теорией по коллекциям](https://youtube.com/playlist?list=PLrCZzMib1e9pDxHYzmEzMmnMMUK-dz0_7)*
* **Generics** *(как применять, как он работает).*
* **Concurrency** **_(базовые знания)_** *(монитор, лог, светофор, как работает многопоточность, как создавать тред)*
* **[GC](https://java-online.ru/garbage-collection.xhtml)** *(как он чистит мусор, как он работает, можно ли его заставить или нет)* [(9Урок49:20)](https://coursehunter.net/course/java-dzhava-dlya-nachinayushchih-s-nulya-do-sertifikata-oracle)
* **JDBC** **_(mybatis / hibernate)_** *(как создавать коннект, как создавать пул, работать с бд)*
* **Maven** *(меньше всего спрашивают) (как он устроен и как им пользоватся)*
  - *[годный гайд от Немчинского](https://www.youtube.com/watch?v=IAbZVA4tK6M)*
* **Lamda** *(как она работает, как оно устроено, черный ящик)*
* **Stream** *(как работает)*
* **String** **_(и память) (Часто спрашивают!)_** *(работа с памятю, как он копирует, и многое другое)*
* **SQL** *(лучше postgre) Надо знать основы, не более! (главное понять как с ним работать)*
  - *[ссылка на плейлист с гайдом по SQL](https://youtube.com/playlist?list=PL07gy0X0ydd0_SrqguK2zVIQg07sbTEDK)*
* **SOLID** *(как правильно программировать, понятия ООП, интерфейсы и тд.)*
* **Уровни изоляции транзакций sql** **_(isolation levels)_** *(грязно чтение, понимание что будет происходить на уровне бд если человек читает эту запись, а другой изменяет  какие то данные, какие данные будут у них видны)*
* **Тестирование** *(хотя бы понимание как это делать и зачем). (создать мини метод, сделать на него тест, на истину/ложь и на ошибку)*
* **Паттерны** *(хватит поверхностных знаний) (минимальные знания, рассказать что они из себя представляют, знать самые базовые и популярные, сингл тон, прокси)*
* **Spring** *(базовые знания)*
  - *[ссылка на плейлист по спрингу](https://youtube.com/playlist?list=PLAma_mKffTOR5o0WNHnY0mTjKxnCgSXrZ)*
* **Git** *(хватит базы, уметь использовать на практике)*
  - *[основы за час по ролику](https://youtu.be/dHlhCO56Pv0)* | *[GIT Полный курс](https://youtube.com/playlist?list=PLAma_mKffTOTIomJBmL9J42PP0l7riFUO)* | *[документация от Жени](https://proselyte.net/tutorials/git/introduction/)*


### После подготовка к работе
* **Подготовка к собеседоваию:** *[частые вопросы](https://jsehelper.blogspot.com/2016/01/blog-post_59.html)*
* **Как найти первую работу в it:** *[Немчинский, что делать после завершения обучения](https://youtu.be/oLZuCGuAnsM)*
* **Резюме на английском:** *[Немчинский, как писать резюме](https://www.youtube.com/watch?v=UV3YSVBJxX0)* | *[GitHub как резюме программиста](https://youtu.be/nEnuP2NmMA4)*
* **Тестовые собеседования:** *[плейлист Жени](https://youtube.com/playlist?list=PLlsMRoVt5sTMMCwd_gLaaZMkQhzVh9hLA)*


## Дополнительный материал
- Разное:
  - *[Е.Книга "Архитектура Современных Веб-Приложений"](https://workshop.zhashkevych.com/courses-info/60a6692126276a15b8dcfa39)*
  - *[Краткие гайды от Жени](https://proselyte.net/tutorials/)*
  - *[Телеграм канал с книгами](https://t.me/dmytrii_bookshelf)* , здесь можно по тегу it найти следующие книги:
    - Java. Полное руководство 10-е изданание. Г.Шилдт
    - Java. Эффективное программирование
    - Алгоритмы на Java
    - Грокаем алгоритмы
  - *[Если у тебя все совсем плохо - лекции CS50](https://youtube.com/playlist?list=PLawfWYMUziZqyUL5QDLVbe3j5BKWj42E5)*
  - *[Годный плагин для Идеи, он заставляет тебя придерживаться чистому стилю письма](https://youtu.be/yrldX6dIS_4)*
- Интересные yt каналы:
  - *[letstCode](https://www.youtube.com/c/letsCodeDru)*
  - *[Sergey Nemchinskiy](https://www.youtube.com/c/SergeyNemchinskiy)*
  - *[Eugene Suleimanov](https://www.youtube.com/c/EugeneSuleimanov)*
  - *[Golovach Courses](https://www.youtube.com/user/KharkovITCourses)*
  - *[Петр](https://youtube.com/channel/UCLUYG3J5lYXs9gwz98aXIsQ)*
  - *[S0ER TALKS](https://www.youtube.com/channel/UCcNotjFXtUZ6bTAWk1KpOWg)*
  - *[Senior Software Vlogger](https://www.youtube.com/c/SeniorSoftwareVlogger)*
  - *[S0ER](https://www.youtube.com/c/S0ERDEVS)*
  - *[Ulbi TV](https://www.youtube.com/c/UlbiTV)*
  - *[ExtremeCode](https://www.youtube.com/c/ExtremeCode)*
- Интересные статьи:
  - *[Зачем мне Java: неудобные вопросы о популярном языке и ответы на них](https://tproger.ru/articles/zachem-mne-java-voprosy-i-otvety/)*
- Интересные ролики:
  - *[Отличный ролик где сказано все необходимое о алгоритмах](https://youtu.be/_NhmGvYs8_g)*
  - *[Какие проекты делать начинающему программисту?](https://youtu.be/lNWp3_CVEO0)*
