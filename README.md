# Документация по созданию полного стека на открытом ПО для использования 1С

Основная цель - предоставить простые и исчерпывающие инструкции для "плавного", постепенного перевода инфраструктуры организации, использующей 1С, на открытое ПО там, где это возможно. Проще говоря - разобраться, как перейти на linux и postgres всей конторой и не умереть. И заодно скиллы прокачать.

Можно выделить несколько "типовых" целей перехода на открытое ПО:
- Соблюдение лицензионной чистоты при разумном бюджете
- Незапланированный существенный рост потребности в лицензиях
- Снижение зависимости от вендоров там, где это возможно
- Обеспечение масштабируемости и отказоустойчивости за счет тиражирования/кластеризации сервисов

## Последовательно заменяем сервисы и ПО  

**То, что незаметно для пользователей, достаточно беспроблемно:**
- [IIS -> Apache httpd](apache.md)
- [MSSQL -> postgresql]()
- [Сервер 1С: переводим на linux]()
- [Контроллер домена: переводим на samba|freeipa]
- [Файловое хранилище: переводим на samba]  
- [Организация мониторинга]  
- [Организация резервного копирования]  


**Самое опасное - касается UX, требуется тщательная подготовка:**
- [Сервер терминалов](rdp-server.md)
- [Офисный пакет: переходим на libreoffice&msoffice online](office.md)
- [Рабочие места пользователей: переходим на linux mint или debian](workstations.md)

Если есть ссылки на статьи и другие ресурсы, которые кажутся полезным в рамках данной темы, буду очень признателен за пополнение [bibliography.md](bibliography.md). Ну или можно просто написать в вопросы (issues).  
Дополнения, исправления и вопросы, возникшие при чтении/применении, а также любая другая помощь приветствуется!
