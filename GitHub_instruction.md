# Наиболее неполная инструкция по GitHub

---
Основная задача этого файла, разобрать материалы, с которые я не знаком, либо с которыми у  меня возникли сложности.

---
### Что такое origin 
Нашел [статью](https://www.atlassian.com/ru/git/tutorials/syncing#:~:text=%D0%92%20%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D0%B5%20%D0%BA%D0%BB%D0%BE%D0%BD%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20%D1%81%20%D0%BF%D0%BE%D0%BC%D0%BE%D1%89%D1%8C%D1%8E,%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B8%D0%BB%D0%B8%20%D0%BF%D1%83%D0%B1%D0%BB%D0%B8%D0%BA%D0%BE%D0%B2%D0%B0%D1%82%D1%8C%20%D0%BB%D0%BE%D0%BA%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5%20%D0%BA%D0%BE%D0%BC%D0%BC%D0%B8%D1%82%D1%8B.), в которой говорится следующее: 
> В процессе клонирования с помощью команды ```git clone``` автоматически создается удаленное подключение к исходному репозиторию (такое соединение называется origin). Это позволяет разработчикам, создающим локальную копию центрального репозитория, легко загружать вышестоящие изменения или публиковать локальные коммиты. Именно поэтому большинство проектов на основе Git называют свой центральный репозиторий origin.

Вызвав команду в терминале: ```git remove -v```, мы увидим наменование удаленного репозитория и его адрес.

---
### GitHub это еще и соцсеть!

Используя кнопку ```follow``` под фотографией пользователя, можно подписаться на пользователя на GitHub. Также будете получать уведомления о его общедоступной активности. Если тот, на кого вы подписаны, создает новый репозиторий, помечает репозиторий или подписывается на другого пользователя, это действие будет отображаться на панели мониторинга.  
Таким же способом, можно подписаться на организацию на GitHub.

Еще на GitHub Вы можете общаться с разработчиками по всему миру. 

---
### Что такое токен

Это альтернатива использованию паролей для аутентификации на GitHub. Создать его очень просто, вверху справа нажать на фото своего профиля, и зайти в меню ```settings```, далее меню ```<> Developer settings```, после заходим в меню ```Personal access tokens``` и открываем ```Tokens (classic)```. В открывшемся меню следует нажать кнопку ```Generate new token```. 

[Полная инструкция](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) по созданию токена. 

---