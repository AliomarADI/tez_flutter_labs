# TEZ Flutter Lab

**Серия технических докладов и воркшопов по Flutter.**

Разбираем то, на чём реально спотыкается продакшен: внутренности фреймворка, нативные интеграции,
архитектуру, производительность. Боевые кейсы, а не «hello world». Уровень — Middle+/Senior.

---

## Темы

**Dart Zones**
Разбор демо-проекта [`vi-k/demo_zones`](https://github.com/vi-k/demo_zones) — зоны в Dart на практике: иерархия и вложенность зон, отлов ошибок через `runZonedGuarded`, проброс контекста (`traceId`, тест-флаги) сквозь async-границы, подмена `print` и таймеров (свой мини-`fake_async`), управление зоной выполнения у Future и Stream.

Применимо: глобальный error-reporting (Crashlytics), трейсинг, фейковые таймеры в тестах.

🔗 [Репозиторий](https://github.com/vi-k/demo_zones)

- **Platform Channels** — Platform Channels, Platform Views vs Texture, Pigeon, background channels, FFI, мульти-движок.



📨 Вопросы, обсуждения и анонсы — в Telegram: **https://t.me/tez_flutter_lab**
