## Описание игры
«Операция Багратион» - онлайн стратегия в реальном времени. Игра эмулирует действия Советского союза и Рейха на территории Беларуси в 1944 году. Названия армий и фронтов не вымышлены, в игре использован исторический контент.  

## Разработка проекта
Проект начал разрабатываться с 11 октября, и на данный момент находится в процессе разработки. Каждый день, по мере возможности, реализуется всё больше и больше идей для данного проекта. Игра находится в бета версии.

С выходами обновлений в игре, данный репозиторий будет обновляться. Весь исходный код разрешается смотреть и использовать в своих проектах.

> На момент бета версии игры в репозитории находится только клиент игры. Полный исходный код игры(сервер и клиент) будет доступен по окончанию разработки, выходу версии 1.0.

## Структура проекта
- Сервер
  - [Node.js](https://nodejs.org/en/);
- Клиент
  - Внешний вид: HTML - разметка страницы;
  - Внешний вид: CSS - стилизация страницы;
  - Javascript - язык программирования игры;
  
## Структура клиента:
- index.html - html страница игры(всей);
- assets
  - img - папка с изображениями;
  - music - папка с аудио файлами;
  - game.js - вся игровая логика игры, главный файл;
  - map.json - база всех территорий на карте;
  - socket.io.js - серверный скрипт;
  - style.css - стилизация игры;
  
## Структура сервера:
- node_modules - папка с модулями сервера;
- package.json - настройки [nodejs](https://nodejs.org/en/) сервера;
- server.js - код [nodejs](https://nodejs.org/en/) сервера;
- start-server.bat - запуск сервера с компьютера под локальный хостинг;
  
## Планы
- [ ] Создание режима "Наблюдение" для серверов;
- [ ] Изменение дизайна:
  - [x] Изменение дизайна меню "Список серверов";                 ***(обновление за 07.11.2018)***
  - [ ] Изменение дизайна главного меню;
  - [x] Изменение дизайна меню "Создание сервера";                ***(обновление за 08.11.2018)***
  - [ ] Изменение дизайна меню "Подключение к серверу";
- [ ] Детализация игровой карты;
- [x] Создание системы призыва армии;                             ***(обновление за 07.11.2018)***
- [ ] Улучшение игрового чата;
- [ ] Реализация игровых меню:
  - [ ] Поддержка;
  - [ ] Фабрики;
  - [ ] Экономика;
  - [ ] Технологии;
- [ ] Система профилей:
  - [ ] Достижения;
  - [ ] История профиля;
  - [ ] Игровая валюта;
  - [ ] Внутриигровые покупки;

## Разработчик
Проект разработан в одиночку [Дмитрием Вансовичем](https://vk.com/dimonka282). Отдельная благодарность людям, которые поддерживали меня на протяжении реализации проекта.
- Gmail почта: <dmitryvansovich94@gmail.com>
- Вконтакте: [Дмитрий Вансович](https://vk.com/dimonka282)
