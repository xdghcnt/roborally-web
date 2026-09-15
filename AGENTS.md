# RoboRally — инструкции для агента

Это игра для сайта meme-police. Она работает внутри обвязки сайта (движок
`ws-server-engine`: меню комнаты, чат, шестерёнка хоста, профиль игрока), и
большинство поломок на сайте — от нарушения контракта с этой обвязкой.

Игра проверяется в песочнице https://github.com/xdghcnt/meme-police-sandbox —
перед правками склонируй её рядом (`../meme-police-sandbox`), если её там нет,
и прочитай `../meme-police-sandbox/AGENTS.md`. Запуск:

```bash
cd ../meme-police-sandbox && npm install && node --watch server.js ../roborally-web
# http://localhost:8090/bg/roborally
```

Если папка игры называется иначе — подставь её имя.
