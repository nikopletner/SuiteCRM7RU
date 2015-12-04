Russian RAPIRA language pack for SuiteCRM
=========================================

+ Здесь находится самая актуальная версия языковых файлов для [SuiteCRM][suitecrm] (форка безвременно почившего [SugarCRM CE] [sugar]), с учётом последних дополнений и исправлений
+ Обновление языковых файлов проще всего сделать через установку языкового пакета ([ссылка на последний актуальный перевод для SuiteCRM 7.4][langpack]). Детально процесс установки/обновления русификации SuiteCRM описан ниже.
+ Обсуждение русификации SuiteCRM на [официальном форуме][forum]
+ Начинающие пользователи могут скачать ["Руководство пользователя и администратора"] [man], переведённое ранее для SugarCRM CE, но вполне подходящее и для знакомства с SuiteCRM.

------------------------------------------------

<b>Что нового в SuiteCRM 7.4</b>    (полная история изменений содержится в файле [HISTORY.TXT][history])

+ Добавлена возможность настройки напоминаний для запланированных мероприятий (звонков и встреч)
	- Добавление неограниченного количества напоминаний в мероприятие с индивидуальными настройками для каждого напоминания
	- Настройка списка адресатов для каждого напоминания
	- Настройка способов уведомления для каждого напоминания
+ Добавлена возможность помечать запись как Избранную
	- Быстрая навигация по избранным записям через панель последних просмотров и через меню модуля
	- Быстрая фильтрация избранных записей в Форме списка модулей
+ Добавлен функционал Базы знаний
	- Добавление статей в Базу знаний
	- Автоматическое предложение вариантов решения из Базы знаний при создании нового Обращения (если статья в Базе знаний содержит совпадения с темой или описанием Обращения)
+ Добавлено отображение оплаченных товаров и услуг
	- Просмотр детальной информации о товарах/услугах, имеющих статус ком. предложения "Принято и закрыто", через соответствующую субпанель модуля Контрагенты 
	- Просмотр клиентов, оплативших товар, через соответствующую субпанель модуля Товары
+ Обновлён мастер установки системы
	- Количество шагов установки сокращено с 8 до 2
	- Упорядочено отображение основных параметров, дополнительные параметры отображаются по необходимости, избыточные параметры удалены
+ Обновлён phpmailer до версии 5.2.13
+ Удалены выходные дни из Проектов (данный функционал не вписывается в логику работы модуля Проекты)
+ Удалён за ненадобностью модуль QuickCRM (стандартная тема SuiteR позволяет работать с SuiteCRM в том числе и на мобильных устройствах)

------------------------------------------------

<b>Установка языкового пакета</b>

Все действия по установке дополнительных пакетов (не только языковых) производятся через панель администратора.

1. Входим в систему с правами администратора.
2. В правом верхнем меню выбираем пункт <b>Администрирование</b> (Admin) для входа в раздел администратора системы.
3. В разделе администратора выбираем <b>Загрузчик модулей</b> (Module Loader).
4. Если в SuiteCRM уже был установлен пакет русификации, то его рекомендуется удалить (кнопка  <b>Деинсталлировать</b>).
5. Загружаем архив с языковым пакетом и далее следуем шагам, описанным в мастере.
6. После того как мастер сообщит об успешной установке пакета, рекомендуется выполнить быстрое восстановление (Администрирование->Восстановление->Быстрое восстановление).
7. Выходим из системы (Logout) и на странице ввода логина/пароля выбираем необходимый язык интерфейса системы.
8. Вновь входим в систему.

Если вы не выбрали русский язык в процессе установки системы, его можно указать позже в качестве языка по умолчанию. Для этого в панели администрирования в подразделе <b>Региональные настройки</b> выберите соответствующий языковой пакет (Admin->Locale Settings->Default Language).
[langpack]: https://github.com/likhobory/SuiteCRM7RU/blob/ver.7.4.0/rapira-suite_pack_russian-7.4.zip?raw=true
[suitecrm]: https://github.com/salesagility/SuiteCRM
[man]: https://github.com/likhobory/SuiteCRM7RU/blob/master/DOCS/RRAG_6.2.2.pdf?raw=true
[forum]: https://suitecrm.com/forum/international-language-support/59
[sugar]: https://ru.wikipedia.org/wiki/SugarCRM
[history]: https://github.com/likhobory/SuiteCRM7RU/blob/master/HISTORY.TXT

