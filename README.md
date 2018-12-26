# ФОРМАТОРИ
<p align="justify">Цей документ містить шаблони таблиць (так звані форматори), котрі полегшують роботу розпорядників інформації щодо формування та подальшого оприлюднення їх даних, як на Єдиному державному порталі (https://data.gov.ua), так і інших централізованих та регіональних порталах відкритих даних. Форматори розроблені в загальнодоступних електронних Google таблицях, котрі при наявності облікового запису, здатен зберегти у себе на особистому Google диску кожен розпорядник інформації.</p>
<p align="justify">Форматори розроблені під конкретні таблиці, що входять до складу того чи іншого набору даних. Таких таблиць в наборі зазвичай налічується від однієї до декількох десятків (у випадку з регламентованими звітами). Зокрема, на кінець 2018 року вже було розроблено 34-ре форматора для 10 наборів даних і, цей список форматорів постійно поповнюється. Таким чином, з часом число форматорів для таблиць в наборах даних може скласти кілька сотень і, для того, щоб розібратися та знайти потрібний форматор, всі вони оформлені у вигляді наведених нижче таблиць, які відповідають тому чи іншому набору даних. У цих же таблицях також наведені CSV файли зі структурою всіх ресурсів (таблиць), що належать відповідному набору даних. Разом з тим, всі форматори містять докладний опис того, як ними користуватися.</p>
<p align="justify">Слід зазначити, що присутні в назвах вищезгаданих таблиць позначення наборів даних формуються у вигляді сукупності, як скорочених найменувань груп (розпорядників) наборів даних, задекларованих у Постанові КМУ № 835, так і порядкових номерів цих наборів даних у відповідних групах. Наприклад, набору даних <i>«Інформація про організаційну структуру розпорядника інформації»</i> буде відповідати підпапка <i><b>«all-002»</b></i>, так як цей набір даних належить до групи <i>«Всі розпорядники інформації»</i>, і знаходиться в ній під <i>2-м</i> порядковим номером. Далі наводяться розшифровки до позначень для тих груп (розпорядників), по наборах даних яких на сьогоднішній момент вже розроблені форматори:</p>

- <b>all</b> - Все розпорядники інформації
-	<b>mun</b> - Органи місцевого самоврядування

    dir /fonts
    dir /images
    dir /js

<p align="center"><b>ЗМІСТ</b></p>

[<b>all-001</b> - Набір данних: «Довідник підприємств, установ (закладів) та організацій розпорядника інформації та підпорядкованих йому організацій»](#Набір-данних-all-001)<br>
[<b>all-002</b> - Набір данних: «Інформація про організаційну структуру розпорядника інформації»](#Набір-данних-all-002)<br>
[<b>all-010</b> - Набір данних: «Фінансова звітність суб’єктів господарювання державного сектору економіки»](#Набір-данних-all-010)<br>
[<b>all-011</b> - Набір данних: «Переліки регуляторних актів із зазначенням дати набрання чинності, строку проведення базового, повторного та періодичного їх відстеження»](#Набір-данних-all-011)<br>
[<b>mun-002</b> - Набір данних: «Перелік об’єктів комуна-льної власності»](#Набір-данних-mun-002)

## Набір данних: all-001

<p align="center"><i>Довідник підприємств, установ (закладів) та організацій розпорядника інформації та підпорядкованих йому організацій</i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [referenceBookFormatter.xls](https://docs.google.com/spreadsheets/d/1eAh-_koPnNYcVyWxoHeREJ2RriofUHrei-H5EnkQ82Q/edit?usp=sharing) | Відомості про підприємства, установи (заклади), організації або структурні підрозділи розпорядника інформації |
| [allStructure-001.csv](https://drive.google.com/file/d/1Ed_nrsFjcmQ8Lx2Epkm9WKpQ9Su4yKbP/view?usp=sharing) | Описання структури для таблиці referenceBook |

## Набір данних: all-002

<p align="center"><i>Інформація про організаційну структуру розпорядника інформації</i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [organizationsFormatter.xls](https://docs.google.com/spreadsheets/d/1gMwDp1IuBFrxizrxYSfxI8q9lEhO8HudPm4PkWBr76M/edit?usp=sharing) | Перелік юридичних осіб, що підпорядковані розпоряднику та/або входять в його структуру |
| [organizationalUnitsFormatter.xls](https://docs.google.com/spreadsheets/d/1B4OT9PL7tQm4TWHleg6Mfvf5ITcKL_eOE4IES9VvF88/edit?usp=sharing) | Перелік структурних підрозділів усіх рівнів, що входять до юридичної особи, якою є розпорядник |
| [postsFormatter.xls](https://docs.google.com/spreadsheets/d/1H1NpucGuMyPPtgZhZndWtwug0kCENeY4P_j1pNCTs48/edit?usp=sharing) | Перелік посад та працівників юридичної особи, якою є розпорядник |
| [allStructure-002.csv](https://drive.google.com/file/d/111HFYLXHRNdUDnJ0ho_2SWHVsCXC-IfW/view?usp=sharing) | Описання структур для таблиць organizations, organizationalUnits та posts |

## Набір данних: all-010

<p align="center"><i> Фінансова звітність суб’єктів господарювання державного сектору економіки </i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [Form-2-StateBudgetFormatter.xls](https://docs.google.com/spreadsheets/d/1vcN7F6VqipykL1Cp4KeILJ-HZqUr10QbLfK4WpnsegA/edit?usp=sharing) | Форма № 2д - Звіт про надходження та використання коштів загального фонду (державний бюджет) |
| [Form-2-LocalBudgetFormatter.xls](https://docs.google.com/spreadsheets/d/1HQxY67qZDSfrEIGBwBDdZeNHW1v9cRXpRGsbBHGCxO8/edit?usp=sharing) | Форма № 2м - Звіт про надходження та використання коштів загального фонду (місцевий бюджет) |
| [Form-4-1-StateBudgetFormatter.xls](https://docs.google.com/spreadsheets/d/1x2BuOGFRWpB6qZohMCu5UZqrYPyyYM_xcA-C37xI8c4/edit?usp=sharing) | Форма № 4-1д - Звіт про надходження і використання коштів, отриманих як плата за послуги  (державний бюджет) |
| [Form-4-1-LocalBudgetFormatter.xls](https://docs.google.com/spreadsheets/d/1oIKRRP56X65C2XzXg6KbdOA6AiivcNCgd1Q9-7HqJys/edit?usp=sharing) | Форма № 4-1м - Звіт про надходження і використання коштів, отриманих як плата за послуги  (місцевий бюджет) |
| Form-4-2-StateBudgetFormatter.xls | Форма № 4-2д - Звіт про надходження і використання коштів, отриманих за іншими джерелами власних надходжень (державний бюджет) |
| Form-4-2-LocalBudgetFormatter.xls | Форма № 4-2м - Звіт про надходження і використання коштів, отриманих за іншими джерелами власних надходжень (місцевий бюджет) |
| Form-4-3-StateBudgetFormatter.xls | Форма № 4-3д - Звіт про надходження і використання інших надходжень спеціального фонду (державний бюджет) |
| Form-4-3-LocalBudgetFormatter.xls | Форма № 4-3м - Звіт про надходження і використання інших надходжень спеціального фонду (місцевий бюджет) |
| Form-4-3-1-StateBudgetFormatter.xls | Форма № 4-3.1д - Звіт про надходження і використання інших надходжень спеціального фонду (позики міжнародних фінансових організацій) (державний бюджет) |
| Form-4-3-1-LocalBudgetFormatter.xls | Форма № 4-3.1м - Звіт про надходження і використання інших надходжень спеціального фонду (позики міжнародних фінансових організацій) (місцевий бюджет) |
| Form-4-4-StateBudgetFormatter.xls | Форма № 4-4д - Звіт про надходження і використання коштів, отриманих на виконання програм соціально-економічного та культурного розвитку регіонів (державний бюджет) |
| Form-4-7-StateBudgetFormatter.xls | Форма № 7д - Звіт про заборгованість за бюджетними коштами (державний бюджет) |
| Form-4-7-LocalBudgetFormatter.xls | Форма № 7м - Звіт про заборгованість за бюджетними коштами (місцевий бюджет) |
| Form-4-7-1-StateBudgetFormatter.xls | Форма № 7.1д - Звіт про заборгованість за окремими програмами (державний бюджет) |
| Form-4-7-1-LocalBudgetFormatter.xls | Форма № 7.1м - Звіт про заборгованість за окремими програмами (державний бюджет) |
| allStructureStateBudget-002.csv | <b>Описання структур для таблиць: </b> Form-2-StateBudgetFormatter.xls, Form-4-1-StateBudgetFormatter.xls, Form-4-2-StateBudgetFormatter.xls, Form-4-3-StateBudgetFormatter.xls, Form-4-3-1-StateBudgetFormatter.xls, Form-4-4-StateBudgetFormatter.xls, Form-7-StateBudgetFormatter.xls, Form-7-1-StateBudgetFormatter.xls |
| allStructureLocalBudget-002.csv | <b>Описання структур для таблиць: </b> Form-2-LocalBudgetFormatter.xls, Form-4-1-LocalBudgetFormatter.xls, Form-4-2-LocalBudgetFormatter.xls, Form-4-3-LocalBudgetFormatter.xls, Form-4-3-1-LocalBudgetFormatter.xls, Form-7-LocalBudgetFormatter.xls, Form-7-1-LocalBudgetFormatter.xls |

## Набір данних: all-011

<p align="center"><i> Переліки регуляторних актів із зазначенням дати набрання чинності, строку проведення базового, повторного та періодичного їх відстеження </i></p>

| Посилання на файли<br>форматорів та структур | Короткий опис таблиць форматорів або файлів структур |
| ------ | ------ |
| [listOfRegulatoryActsFormatter.xls]( https://docs.google.com/spreadsheets/d/1yGniQiJhagiOCI2WfspLF_rPW_Zys2hZSq6PaYnNl-Q/edit?usp=sharing) | Таблиця, що містить перелік діючих регуляторних актів розпорядника із зазначенням інформації про нормативно-правові акти, якими вони були введені в дію, а також інформації про базові, повторні та періодичні відстеження |
| [allStructure-011.csv]( https://drive.google.com/file/d/1GbxCsfr95WymJeEByhbtKo3PXIRY59Xx/view?usp=sharing) | Описання структури для таблиці listOfRegulatoryActs |


