# Minecraft Server Project

Совместный проект сервера Minecraft для публичного запуска.

## Стек и архитектура
- **Ядро:** Paper / Purpur
- **Java:** OpenJDK 21
- **Совместная разработка:** Antigravity 2.0 + Git / GitHub

## Структура репозитория
- `plugins/` — конфигурации (`config.yml`, сообщения, права) и jar-плагины.
- `server.properties` — основные сетевые и игровые параметры.
- `.agents/rules/` — база знаний и инструкции для ИИ-ассистентов Antigravity.
- `SERVER_ROADMAP.md` — текущий статус разработки, задачи и план запуска.

## Инструкция для синхронизации
1. Перед началом работы в Antigravity:
   ```bash
   git pull
   ```
2. После внесения изменений или правок от агента:
   ```bash
   git add .
   git commit -m "Описание изменений (например: настроен LuckPerms)"
   git push
   ```
