# Аркадий Газизов (JustTheBear)

**Software Engineer & Tech Lead** · Бэкенд, Информационная безопасность, Распределенные системы & WebGL.  
Студент НИУ ВШЭ (*Компьютерная безопасность*) и программы двух дипломов Финансового университета & МГТУ им. Н.Э. Баумана (*Цифровизация финансовых продуктов*). Экс-стажер VK по безопасности и middleware, основатель B2B-продуктов, призер ВсОШ и НТО.

[Личный сайт](https://arkadiygazizov.ru) · [Telegram](https://t.me/justthebear) · [Email](mailto:arkadiygazizov@gmail.com)

---

### Специализация и стек

- **Backend & Systems**: Go, Python (FastAPI, Asyncio), C++20, PostgreSQL, Redis, Docker, WebSockets.
- **Security & Infrastructure**: Zero-Trust архитектура, 2FA (RFC 6238 TOTP), ротация JWT-токенов, аудит уязвимостей, Linux, CI/CD.
- **Frontend & Interfaces**: TypeScript, React 19, Tailwind CSS, Zustand, Lightweight Charts, дизайн-системы (Linear, Coinbase, Vercel).
- **Core & Algorithms**: Олимпиадная база (ВсОШ, ЦПМ), структуры данных (Segment Tree, Fenwick, DSU, Trie), теория графов.

---

### Выбранные репозитории (Pinned Projects)

| Проект | Стек | Описание |
| :--- | :--- | :--- |
| [**tournament-bracket-engine**](https://github.com/JustTheBear/tournament-bracket-engine) | `Python`, `FastAPI`, `WebSockets`, `Docker` | Флагман из резюме: движок генерации турнирных сеток с распределением слотов по силе посева и живой трансляцией матчей по WS. |
| [**zero-trust-auth-gateway**](https://github.com/JustTheBear/zero-trust-auth-gateway) | `Go`, `JWT`, `TOTP`, `RBAC`, `Crypto` | Шлюз аутентификации (опыт VK & ВШЭ КБ): 2FA TOTP RFC 6238, ротация токенов с детекцией replay-атак и sliding-window rate limiting. |
| [**fintech-terminal-ui**](https://github.com/JustTheBear/fintech-terminal-ui) | `React 19`, `TypeScript`, `Tailwind`, `Charts` | Торговый терминал в стиле Coinbase/Stripe: свечные графики TradingView, живой биржевой стакан (order book) и лента сделок. |
| [**algorithms-and-ds-handbook**](https://github.com/JustTheBear/algorithms-and-ds-handbook) | `Python`, `Algorithms`, `Pytest`, `Rich` | Фундаментальная библиотека структур данных и алгоритмов: Lazy Segment Tree, Fenwick, DSU, Tarjan SCC, KMP с бенчмарками. |

---

### Инженерное портфолио по категориям

#### 🛡️ Безопасность и Сетевые инструменты
- [**zero-trust-auth-gateway**](https://github.com/JustTheBear/zero-trust-auth-gateway) — Production-grade сервис аутентификации на Go: защита от брутфорса, ротация refresh-токенов, RBAC-контроль доступа.
- [**port-scanner-recon**](https://github.com/JustTheBear/port-scanner-recon) — Асинхронный сетевой сканер на `asyncio`: неблокирующий опрос сокетов (150+ воркеров), баннер-греббинг и валидация SSL/TLS x509 сертификатов.

#### ⚙️ Бэкенд и Распределенные системы
- [**tournament-bracket-engine**](https://github.com/JustTheBear/tournament-bracket-engine) — REST API + WebSockets платформа проведения чемпионатов с математическим посевом участников и графом продвижения победителей.
- [**async-job-queue**](https://github.com/JustTheBear/async-job-queue) — Легковесная асинхронная очередь задач: пулы воркеров, экспоненциальные ретраи (exponential backoff) и Dead Letter Queue (DLQ).

#### 🎨 Дизайн-системы и Frontend
- [**fintech-terminal-ui**](https://github.com/JustTheBear/fintech-terminal-ui) — Высокоплотный финансовый интерфейс спотовой торговли с графиками Lightweight Charts и симулятором тиков.
- [**linear-kanban-board**](https://github.com/JustTheBear/linear-kanban-board) — Инженерный таск-трекер в эстетике Linear.app: доступный Drag-and-Drop на `@dnd-kit`, локальный стор на Zustand и мгновенная фильтрация.

#### ⚡ Алгоритмы и Системная база
- [**algorithms-and-ds-handbook**](https://github.com/JustTheBear/algorithms-and-ds-handbook) — Полный справочник алгоритмов: 3-way QuickSort, MergeSort, Radix, Dijkstra, A*, Floyd-Warshall, Segment Tree с Lazy Propagation, Fenwick, DSU, Trie, KMP, Z-алгоритм.
- [**algo-visualizer-cli**](https://github.com/JustTheBear/algo-visualizer-cli) — Терминальный ASCII-визуализатор сортировок в реальном времени на базе `rich.live`.

---

```
           +-------------------------------------------------------+
           |                    АРКАДИЙ ГАЗИЗОВ                    |
           |             Backend & Security Engineer               |
           +---------------------------+---------------------------+
                                       |
        +------------------+-----------+-----------+------------------+
        |                  |                       |                  |
        v                  v                       v                  v
  [ Безопасность ]    [ Бэкенд ]              [ Frontend ]       [ Алгоритмы ]
  - Zero-Trust Go     - Tournament Engine     - Coinbase UI      - Handbook & Bench
  - Async Recon       - Distributed Queue     - Linear Kanban    - CLI Visualizer
```
