# mediametrics

Консольный клиент для **http://mediametrics.ru**

Прежде всего предлагаю писать на node.js или на golang. ( я больше склоняюсь к golang )
Основная идея клиента в возможности просмотра ленты новостей из консоли для технарей.
+ возможность детализации по конкретной новости
+ список последних новостей
+ список последних статей
+ также изучать содержимое рубрик
+ возможность внесения новости в закладки
+ публикация в сервисах (ФБ, VK, TW)

Через него можно просматривать список последних новостей и статей, а также изучать содержимое рубрик (в том числе английской версии издания).

Наброски:
- архиважно запилить отслеживание  нотификацию по тегам
- параметры ограничивающие кол-во вывода
- blacklist для определенных новостей
- возможность самостоятельной смены цветовой схемы
- транспорт в slack и hipchat
- админский ssh сhat c транспортом в общий чат
- транспорт в IRC ( мегафункция )
- пушить отслеживаемые новости в github
- интеграция с  Homebrew, apt-get, yum, и прочими пакетами
- сортировка новостей по источникам (например по habrhabr)
- встроить возможность откладывания статьи для прочтения на потом с НАПОМИНАНИЕМ

Радио:
- возможность просмотра прошедших и будующих передач
- возможность поставить себе напоминание о передачи
- запись передачи на диск
- оценка передачи

Новости по SSH для TRUE админов

Несколько типов интерфейсов:
1) Простой консольный ( запускается один раз, выдает новости и другую информацию )
2) Интерактивный новостной интерфейс
3) Интерфейс радио, сразу с чатом и другими плюшками

- Возможность авторизации для комментирования.
- Возможность генерирования SSH ключа и привязка его к аккаунту в интернете

SUPER функции:
1) Нотификация с напоминанием работает на нашей стороне ( на стороне сервера )
2) 

