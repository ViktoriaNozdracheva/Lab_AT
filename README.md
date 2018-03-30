# Lab_AT
Был выбран сайт кафедры Автоматизированных систем управления Радиотехнического университета: https://rgrty.ru/
1.Необходимость внедрения автоматизации.
•	Уменьшение объема ручных, рутинных, постоянно повторяющихся операций в процессе тестирования.
•	Снижение стоимости итерации тестирования.
•	Увеличение скорости тестирования без ущерба для результата.
•	Точное выявление ошибок.
•	Автоматическое формирование отчетов о тестировании.
Автоматизацию нужно внедрять на этапе выполнения жизненного цикла.

2.Типы тестов, которые следует автоматизировать в первую очередь.
•	Функционал
•	Интерфейс
•	Манипуляции с данными
•	Сообщения об ошибках
•	Авторизация пользователей
•	Комплексная проверка всей системы

3.Предпочтительно автоматизировать.
•	Авторизация на сайте.
•	Изменение пароля учетной записи.
•	Интерфейс сайта (Слишком перегружен дополнительными сайтами, файлами и гиперссылками).
•	Работоспособность базового функционала.
•	Элементы управления.
•	Поиск данных.
Эти кейсы выбраны по причине того, что их часто используют пользователи при входе на сайт.

4.Не следует автоматизировать.
•	тесты, требующие ручного вмешательства для проверки ошибок или отклонения от ожидаемого поведения;
•	тесты, включающие в себя установку или не нуждающиеся в повторном исполнении функции;
•	новый функционал;
•	временные тесты;
•	проверка даты истечения срока действия;
•	тесты, которые включают проверку повторной калибровки объектов на разных размерах экрана. 

5.Инструменты автоматизации.
	HP QuickTest Professional
Средство автоматизации от кампании Hewlett-Packard. 
Распространяется на платной основе (460000-600000 руб.). 
Является основным инструментом автоматизации функционального тестирования от данного производителя. 
Позволяет автоматизировать функциональные и регрессионные тесты через записи действий пользователя при работе с тестируемым приложением, а потом исполнять записанные действия с целью проверки работоспособности ПО. 
Записанные действия сохраняются в виде скриптов.
Скрипты могут быть отображенные в инструменте как VBScript (expert view), или же как визуальные последовательные шаги с действиями (keyword view). 
Каждый шаг может быть отредактирован и на него можно добавить точки проверки (checkpoint), которые сравнивают ожидаемый результат с полученным.


	IBM Rational Functional Tester
Rational Functional Tester - это инструмент автоматизированного функционального и регрессивного тестирования.
Платный(30000 – 300000).
Предоставляет тестировщикам средства автоматизированного тестирования, позволяющие выполнять функциональное тестирование, регрессивное тестирование, тестирование пользовательского интерфейса и тестирование, управляемое данными.
•	Storyboard Testing упрощает визуализацию и редактирование тестов благодаря использованию естественного языка и снимков экрана.
•	Интеграция с Jazz Eclipse Client Version 2.0 - for Rational Team Concert and Rational Quality Manager Servers - предоставляет доступ к элементам потока операций, а также логическую или составную поддержку управления тестами (SCM test asset support).
•	Позволяет тестировщикам автоматизировать тестирование, устойчивое к частым изменениям пользовательского интерфейса приложений, благодаря технологии ScriptAssure™.
•	Выполняет проверку динамических данных с использованием различных мастеров, точек проверки и шаблонов регулярных выражений.
•	Автоматизированный мастер для выполнения тестирования, управляемого данными, позволяет повысить полноту тестирования за счет многократного использования отдельных тестов с различными наборами тестовых данных.
•	Допускает использование ключевых слов для частичной автоматизации ручного тестирования.
•	Позволяет тестировщикам выбрать язык сценариев для разработки и настройки тестов: Java в среде Eclipse или Microsoft Visual Basic .NET в среде Visual Studio .NET.
•	Поддерживает пользовательские элементы управления благодаря прокси-объекту SDK (Java/.Net).
•	Включает встроенную поддержку Web-, .Net-, Java-. Siebel-, SAP-приложений и приложений эмуляции терминалов, таких как приложения 3270 (zSeries™) и 5250 (iSeries™), PowerBuilder, AJAX, Adobe Flex, Dojo Toolkit и GEF. Можно также тестировать документы Adobe PDF, а также приложения zSeries, iSeries и pSeries.
•	Поддерживает функциональное тестирование сред приложений Oracle ERP посредством поставляемых расширений.
•	Поддерживаемые операционные системы: Linux, Windows.

Основные возможности:
•	тестирование приложений на Java (J2EE, J2SE, SWT, средства управления AWT/JFC);
•	тестирование Web-приложений (HTML, DHTML, XML, JavaScript, Java-аплеты);
•	написание тестовых сценариев на Java;
•	использование технологии ScriptAssure и проверка изменения прикладных данных;
•	интеграция с коллективными коммуникационными средствами Rational;
•	поддерживает тестирование приложений 3270 (zSeries) и 5250 (iSeries) с использованием расширения Functional Tester Extension для приложений на основе терминалов;
•	бесшовная интеграция в среду Eclipse, WebSphere Studio и Rational XDE Developer.


	SmartBear TestComplete
  Это инструмент для автоматизации тестирования, позволяющий создавать и выполнять тесты для любых Windows и Web приложений, как простых, так и обладающих богатой функциональностью. Используя TestComplete, можно легко создавать и автоматизировать тесты для тестируемого приложения. Автоматизированные тесты работают быстрее ручных, охватывают больше областей тестируемого приложения и снижают затраты на тестирование.
Платный (30000 – 120000 руб.)
•	Легкое в использовании keyword тестирование, не требующее создания скриптов
•	Создание мощных и гибких тестовых скриптов
•	Тестирование Windows и Web приложений
•	Поддержка .NET, ASP.NET, WPF, Silverlight и XBAP приложений
•	Поддержка Adobe AIR, Flex и Flash приложений
•	Поддержка Java и JavaFX приложений
•	Поддержка Ajax, ASP, PHP и других типов Web приложений
•	Поддержка различных Интернет браузеров, включая последние версии Internet Explorer 8 и Firefox 3.6
•	Поддержка операционных систем Windows 7, Vista, XP, 2000, Windows Server 2003 и 2008
•	Поддержка телефонов и эмуляторов на базе Windows Mobile
•	Поддержка как 32-битных, так и 64-битных приложений
•	Поддержка популярных систем отслеживания ошибок (bug tracking system): Software Planner, Axosoft OnTime, Atlassian JIRA и других.
•	Открытый API
•	Легкая расширяемость
•	Подробная документация и примеры

Вывод: для автоматизированного тестирования данного сайта, лучше воспользоваться SmartBear TestComplete. Так как он подходит по всем требованиям, которые нам нужны: поддержка всех ОС, создание мощных и гибких тестовых скриптов, дешевле из всех рассмотренных, подходит для тестирования функционала и интерфейса.
