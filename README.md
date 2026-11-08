# Аркадий Газизов

Бэкенд, информационная безопасность и распределенные системы.

Студент НИУ ВШЭ (Информационная безопасность) и совместной программы Финансового университета и МГТУ им. Баумана. Проходил стажировку в VK (инфраструктура и безопасность). Призер Всероса и НТО.

[Сайт](https://arkadiygazizov.ru) · [Telegram](https://t.me/justthebear) · [Email](mailto:arkadiygazizov@gmail.com)

---

### Основные проекты

- [**zero-trust-auth-gateway**](https://github.com/JustTheBear/zero-trust-auth-gateway) (Go) - шлюз авторизации: 2FA на TOTP (RFC 6238), ротация refresh-токенов с отслеживанием повторного использования, rate limiting на скользящем окне.
- [**tournament-bracket-engine**](https://github.com/JustTheBear/tournament-bracket-engine) (Python, FastAPI) - генератор турнирных сеток Single Elimination с посевом участников и трансляцией матчей через WebSockets.
- [**linear-kanban-board**](https://github.com/JustTheBear/linear-kanban-board) (React 19, TypeScript) - канбан-доска: drag-and-drop на `@dnd-kit`, палитра команд (Ctrl+K), переключение List/Board видов, чеклисты подзадач, дедлайны и экспорт спринта в JSON/CSV.
- [**port-scanner-recon**](https://github.com/JustTheBear/port-scanner-recon) (Python) - асинхронный сканер портов на `asyncio`: баннер-граббинг, проверка SSL-сертификатов, экспорт в JSON.
- [**fintech-terminal-ui**](https://github.com/JustTheBear/fintech-terminal-ui) (React 19, TypeScript) - торговый терминал: графики на Lightweight Charts, стакан заявок и лента сделок с генерацией тиков.
- [**async-job-queue**](https://github.com/JustTheBear/async-job-queue) (Python) - очередь фоновых задач на `asyncio.Queue` с ретраями (backoff) и DLQ.
- [**algorithms-and-ds-handbook**](https://github.com/JustTheBear/algorithms-and-ds-handbook) (Python) - реализации структур данных (Segment Tree, Fenwick, DSU, Trie) и графовых алгоритмов с замерами производительности.
- [**algo-visualizer-cli**](https://github.com/JustTheBear/algo-visualizer-cli) (Python) - терминальная визуализация сортировок на базе библиотеки `rich`.

---

### Стек

- **Языки:** Go, Python, TypeScript, C++20
- **Бэкенд:** FastAPI, Asyncio, WebSockets, PostgreSQL, Redis, Docker
- **Безопасность:** Zero-Trust, JWT, TOTP, аудит уязвимостей, Linux
- **Фронтенд:** React 19, Tailwind CSS, Zustand, @dnd-kit, Lightweight Charts
