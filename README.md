# ТЕХНИЧЕСКОЕ ЗАДАНИЕ НА РАЗРАБОТКУ ИНТЕРНЕТ-САЙТА «Global Engineering Baltia LTD»

Структура документа:

1. Глоссарий
2. Общие положения
	* Предмет разработки
	* Назначение документа
3. Требования к графическому дизайну сайта
	- Требования к дизайну сайта
	- Порядок утверждения дизайн-концепции
4. Функциональные требования
	- Классы пользователей
	- Требования к представлению сайта
	- Требования к системе управления сайтом
	- Требования к разделению доступа
5. Требования к видам обеспечения
	- Требования к информационному обеспечению
	- Требования к программному обеспечению
	- Требования к техническому обеспечению
	- Требования к лингвистическому обеспечению
	- Требования к эргономике и технической эстетике
6. Требования к приемке-сдаче проекта
	- Требования к наполнению информацией
	- Требования к персоналу
	- Порядок предоставления дистрибутива
	- Порядок переноса сайта на технические средства заказчика


# 1. Глоссарий 
Термин  | Описание
------------ | -------------
Сайт | Информационная система, предоставляющая пользователям сети Интернет доступ к своему содержимому и функционалу в виде упорядоченного набора взаимосвязанных HTML-страниц 
World wide web (WWW, web, веб)  | Единое информационное пространство на базе сети Internet, состоящее из совокупности сайтов. Приставка "веб-" может использоваться для обозначения объектов, ориентированных на использование в WWW или использующих типичные для WWW технологии (например, веб- интерфейс - интерфейс на базе веб-страниц)
HTML-страница (веб- страница, страница) | Основной носитель информации в World ide Web. Особым образом сформатированный файл (набор файлов), просматриваемый с помощью www-браузера как единое целое (без перехода по гиперссылкам) 
HTML-теги (теги) | Управляющие коды, посредством которых осуществляется форматирование HTML-страницы 
Гиперссылка (ссылка, линк) | Активный элемент HTML-страницы, задаваемый специальным тегом. Выделенный фрагмент текста или изображения, позволяющий загрузить другую страницу или выполнить определенное действие 
WWW-браузер (браузер) | Клиентская программа, поставляемая третьими сторонами и позволяющая просматривать содержимое HTML-страниц 
HTML-форма (форма) | Часть HTML-страницы, предназначенная для взаимодействия с посетителем сайта. Представляет собой набор элементов (текстовых полей, селекторов, выпадающих списков), посредством которых пользователь может ввести какую-либо информацию и отправить ее для обработки на сервере 
Поле (поле БД, поле формы) | Структурный элемент, содержащий однотипную информацию, например, текст, дату, числовые значения и т.п. 
Флаг | Особое поле данных, могущее содержать только одно из двух допустимых значений. Позволяет указать на наличие или отсутствие какого-либо события или свойства объекта 
Справочник | Вспомогательная структура данных, содержащая список допустимых значений для какого-либо поля основных форм или БД. Справочники подразделяются на фиксированные (неизменяемые и поставляемые Исполнителем вместе с готовым сайтом) и редактируемые (состав которых может изменяться администратором) 
Администратор (менеджер, редактор) сайта | Лицо, осуществляющее от имени Заказчика информационную поддержку сайта
Дизайн-шаблон страниц | Файл, содержащий элементы внешнего оформления HTML страниц сайта, а также набор специальных тегов, используемых системой публикации сайта для вывода информации при создании окончательных HTML страниц 
Дизайн веб-сайта | Уникальные для конкретного веб-сайта структура, графическое оформление и способы представления информации 
Информационные материалы | Информация о деятельности Заказчика. Может включать графические, текстовые, аудио или видео материалы. Предоставляется Заказчиком 
Наполнение (контент) | Совокупность информационного наполнения веб-сайта. Включает тексты, изображения, файлы и т.п. предназначенные для пользователей системы 
Элемент наполнения (контента) | Отдельная запись в базе данных, внешнее представление которой зависит от управляющего ей программного модуля (например, в модуле «новостная лента» элементом наполнения является отдельная новость) 
Система динамического управления наполнением (контентом) сайта | Информационная система, позволяющая авторизованным пользователям производить изменения иерархической структуры и информационного наполнения веб-сайта без использования каких либо дополнительных специальных программных средств 
Дамп | Совокупность объектов базы данных, представленная в виде файлов, позволяющая восстановить точную копию структуры исходной базы данных в аналогичной системе управления базами данных
Веб-интерфейс | Совокупность экранов и элементов управления системы, позволяющих пользователю, осуществляющему доступ к системе через веб-браузер, осуществлять поддержку и управление системой. 
Шаблона раздела | Особым образом размеченный ASCII-файл, определяющий как графическое оформление страниц раздела, так и их макет (раскладку) – взаимное расположение блоков с наполнением раздела 
WYSIWYG редактор | Редактор языка HTML, имеющий возможности по работе в текстовом режиме и в режиме WYSIWYG (What You See Is What You Get). В режиме WYSIWYG элементы HTML страницы при редактировании представляются в том же виде, что и при просмотре 
Роль | Класс пользователей системы, обладающих определенным набором прав доступа 

Прочая техническая терминология понимается в соответствии с действующими стандартами и рекомендациями международных органов, ответственных за вопросы стандартизации в сети Интернет. 

# 2. Общие положения
# 2.1 Предмет разработки
Предметом разработки является Интернет-сайт компании «Global Engineering Baltia», с системой динамического управления наполнением на базе веб-интерфейса. Назначение сайта:
- предоставление информации о компании «Global Engineering Baltia»;
- предоставление площадки для инвестирования в альтернативную энергетику;
- анонсирование статей и новых продуктов компании; - осуществление обратной связи с клиентами;

Цель создания сайта: ознакомление с деятельностью компании «Global Engineering Baltia», расширение ареала инвестиций.


# 2.2 Назначение документа
В настоящем документе приводится полный набор требований к реализации сайта компании "Global Engineering Baltia". Подпись Заказчика и Исполнителя на настоящем документе подтверждает их согласие с нижеследующими фактами и условиями:

1. Исполнитель подготовил и разработал настоящий документ, именуемый Техническое Задание, который содержит перечень требований к выполняемым работам.
2. Заказчик согласен со всеми положениями настоящего Технического Задания.
3. Заказчик не вправе требовать от Исполнителя в рамках текущего Договора выполнения работ либо оказания услуг, прямо не описанных в настоящем Техническом Задании.
4. Исполнитель обязуется выполнить работы в объёме, указанном в настоящем Техническом Задании.
5. Заказчик не вправе требовать от Исполнителя соблюдения каких-либо форматов и стандартов, если это не указано в настоящем Техническом Задании.
6. Все неоднозначности, выявленные в настоящем Техническом задании после его подписания, подлежат двухстороннему согласованию между Сторонами. В процессе согласования могут быть разработаны дополнительные требования, которые оформляются дополнительным соглашением к Договору и соответствующим образом оцениваются.


# 3. Требования к графическому дизайну сайта
# 3.1 Требования к дизайну сайта
При разработке сайта должны быть использованы преимущественно светлые цветовые решения(пример дизайнерского решения сайта: http://prostor-capital.ru/). Оформление должно быть разработано в достаточно консервативном ключе. Основные разделы сайта должны быть доступны с первой страницы. На первой странице не должно быть большого объема текстовой информации.

В дизайне сайта не должны присутствовать:

- мелькающие баннеры;
- много сливающегося текста;
- тёмные и агрессивные цветовые сочетания и графические решения.

# 3.2 Порядок утверждения дизайн-концепции
Под дизайн-концепцией понимается вариант оформления главной страницы и графическая оболочка внутренних страниц, демонстрирующие общее визуальное (композиционное, цветовое, шрифтовое, навигационное) решение основных страниц сайта. Дизайн-концепция представляется в виде файла (нескольких файлов) в растровом формате или в распечатке по согласованию сторон.

Если представленная Исполнителем дизайн-концепция удовлетворяет Заказчика, он должен утвердить ее в течение пяти рабочих дней с момента представления. При этом он может направить Исполнителю список частных доработок, не затрагивающих общую структуру страниц и их стилевое решение. Указанные доработки производятся параллельно с разработкой программных модулей сайта. Внесение изменений в дизайн-концепцию после ее приемки допускается только по дополнительному соглашению сторон.
Если представленная концепция не удовлетворяет требованиям Заказчика, последний предоставляет мотивированный отказ от принятия концепции с указанием деталей, которые послужили препятствием для принятия концепции и более четкой формулировкой требований.
В этом случае Исполнитель разрабатывает второй вариант дизайн-концепции (дорабатывает, вносит изменения). Обязательства по разработке второго варианта дизайн-концепции Исполнитель принимает только после согласования и подписания дополнительного соглашения о продлении этапа разработки дизайн-концепции на срок не менее пяти рабочих дней. Дополнительные (третий и последующие) варианты разрабатываются Исполнителем за отдельную плату на основании дополнительных соглашений.

# 4. Функциональные требования
# 4.1 Классы пользователей
1. Гость – неавторизованный пользователь
2. Авторизованный пользователь
3. Менеджер
4. Администратор – пользователь, авторизованный в интерфейсе администрирования портала. Полный доступ ко всем функциональным возможностям администрирования системы

# 4.2 Требования к представлению сайта
1. Архитектура системы
	* Изобретение
	* Компания
		* О компании
		* Наша команда
		* Документы
	* Инвестору
	* Новости
	* Видео
	* Контакты
	* Личный кабинет
2. Шаблоны интерфейсов системы
	* [Главная страница](/01-templates/home)
	* [Изобретение](/01-templates/tech)
	* Компания
		* [О компания](/01-templates/company/about_company)
		* [Наша команда](/01-templates/company/our_team)
		* [Документы](/01-templates/company/documents)
	* [Инвестору](/01-templates/invest)
	* Новости
		* [Список новостей](/01-templates/news/news_list)
		* [Новость](/01-templates/news/news_single)
	* [Видео](/01-templates/video)
	* [Контакты](/01-templates/contacts)


