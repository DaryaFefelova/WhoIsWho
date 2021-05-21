**Название проекта**: Кто есть кто

**Команда:** Раскаты Грома АТ-01

**Формат системы:** Мобильное веб-приложение

**Цель проекта:** Создать образовательную игру по истории, которая поможет пользователям узнавать что-то новое о великих исторических личностях, лучше запоминать их имена и достижения.

**Описание:** Образовательная игра по истории представляет собой несколько режимов: Одиночный, Командный, Правда/Ложь.
В одиночном режиме перед пользователем представляется 2-3 факта и по ним пользователь должен угадать имя человека, которому принадлежит то или иное достижение, интересный факт из жизни.
В командном группа людей разбивается между собой на команды. Случайным образом выбирается кто из команд начинает первым.
Выбирается один человек, который будет своей команде, в том числе и команде противников называть ряд фактов об известной личности, не называя его имени. У каждой команды есть 30 секунд на размышление. Тому, кто быстрее угадает, начисляется балл. Угадавшей команде передается телефон со следующим раундом.
Правда или ложь представляет собой интересный интерактив. Напоминает собой игру с Алисой в Яндекс Браузере "Верю/Не верю", но с существенным отличием. Вопросы относятся только к мировым личностям. Игроку показывается факт, и он должен дать правильный ответ, то есть правда ли относится факт к данной персоне или нет.


**Целевая аудитория:** Приложение предназначено для лиц старше 14 лет

**Основное преимущество:** 1. Отсутствие прямого конкурента;
                           2. Интересные факты о деятелях истории и культуры;
                           3. Соревновательный метод обучения;
                           4. Подходит для использования группы плюдей;

**Стек технологий:** Unity, C#

**Сценарий использования:**

Пользователь заходит в игру
Выбирает один из режимов: Одиночный, командный, Правда/Ложь
*Одиночный
В течение игры дает ответы на вопросы, узнает правильные ответы, получает результаты игры(счёт)
*Командный (по желанию игроков правила могут меняться)
Происходит распределение по командам
Один из игроков называет несколько фактов об исторической личности. 
Угадавшей команде присуждается балл и передается телефон со следующим раундом.
В конце выявляется победитель.
*Правда/Ложь
Перед пользователем появляется один рандомный факт из истории.
Пользователь угадываает - правда это или ложь. 
Узнает правильный ответ. Читает узнать более подробную информацию.
Продолжает игру.

**Результат:** Мобильное приложение в плеймаркете. 

**Основные требования к ПО для пользования:** Android

**Порядок установки:** Установить приложение на смартфон

**Структура приложения:**
/index.php - основной файл, где происходит формирование страницы
/style.css - файл стилей для главной страницы
/scripts/js/consoleLog.js - скрипт, отвечающий за отправление запроса о добавлении пользователя на сервер
/scripts/php/main.php - серверный скрипт, отвечающий за подключение к БД, выборку данных из неё и формированию ответа для consoleLog.js
/assets - директория, содержащая медиа-данные (шрифты, фото и т.д.)
