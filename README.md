# Привет, я Никита! 👋


Разрабатываю масштабируемые сетевые сервисы, высокопроизводительные NLP/AI-пайплайны и легковесные нативные приложения.

---

## ⚡ Избранные  проекты (Flagship Projects)

### 1. [VOLT (`volt-voice`)](https://github.com/nikitos7626/volt-voice)
> **Self-Hosted мессенджер с 2K 60fps демонстрацией экрана, студийным Hi-Fi плеером и нативным клиентом на Rust**

* **Стек:** Rust (`tao` + `wry`), LiveKit SFU, Python 3.12, FFmpeg (`libsoxr 28-bit`), WebRTC, Caddy, Docker.
* **Фичи:**
  * Потоковая трансляция экрана до `2560×1440 @ 60fps` (`VP9`, `25 Mbps`) без ограничений битрейта.
  * Студийный аудиотракт `48 kHz Stereo Opus 260+ kbps` с калибровкой кадра 20.0 мс, EQ и защитой от обрезки низких частот.
  * Нативный Windows-клиент размером всего **~760 КБ** с аппаратной привязкой сессии (`MachineGuid`), автообновлением по `SHA-256` и защитой от троттлинга в играх.
  * Серверная защита ядра от фейковых DPI-пакетов (`iptables raw PREROUTING`) для 100% стабильности сокета.

---

### 2. [Product Attribute Extractor (`product-attribute-extractor`)](https://github.com/nikitos7626/product-attribute-extractor)
> **Промышленный каскадный NLP-сервис автоматического извлечения и валидации характеристик товаров каталога e-commerce**

* **Стек:** Python 3.10+, FastAPI, FlashText (Ахо-Корасик), GLiNER (Zero-Shot NER), PyTorch (CPU), Catalog KB (9 700+ моделей), Docker.
* **Фичи:**
  * Пропускная способность **> 680 карточек/сек** на одном ядре CPU (задержка **< 1.5 мс** на карточку) без GPU.
  * Каскадная многоуровневая архитектура (Tier 1–4) с предохранителем `Circuit Breaker` и проверкой заземления фактов (`GroundingVerifier`).
  * Интерактивное рабочее место контент-модератора (**Human-in-the-Loop**) со скорингом уверенности (`confidence`) и обратной связью.
  * Покрыт **208 автотестами** (100% green).

---

### 3. [Career Hub AI (`career-hub-bot`)](https://github.com/nikitos7626/career-hub-bot)
> **Автономный агрегатор IT-вакансий с 9 площадок, нейросетевым скорингом и клиентом Telegram Mini App со свайпами**

* **Стек:** Python 3.12+, Groq LLM API, asyncio, Telegram WebApp SDK, Tailwind CSS, Lucide Icons, Docker Compose.
* **Фичи:**
  * Мониторинг и парсинг вакансий с **HeadHunter, Хабр Карьеры, SuperJob, GetMatch, LinkedIn, СЕТИ, Работа.ру, Telegram-каналов**.
  * Интеллектуальный скоринг соответствия профилю (1–10) с генерацией персонализированных технических сопроводительных писем.
  * Два режима интерфейса: **Tinder-свайпы** жестами/клавиатурой и подробный **Канбан-дашборд** со статистикой воронки.
  * Мультиплатформенный авто-отклик в 1 клик через веб-сессии HH, Хабр Карьеры, SuperJob, GetMatch и email.
  * Полное покрытие интеграционными тестами (82 теста: защита от DoS, CSRF, replay attacks и XSS).

---

---

### 4. [Tic-Tac-Toe Multiplayer Service (`tictac-multiplayer-service`)](https://github.com/nikitos7626/tictac-multiplayer-service)
> **Бэкенд-сервис для многопользовательской игры в «Крестики-нолики» (PvP/PvE) на Java 21 и Spring Boot 3**

* **Стек:** Java 21, Spring Boot 3.3, Spring Security, Spring Data JPA, Hibernate, PostgreSQL, Docker, Maven.
* **Фичи:**
  * Реализация игрового движка с поддержкой многопользовательских матчей между игроками (PvP) и одиночного режима против компьютера.
  * Система регистрации, аутентификации и разграничения прав доступа на базе Spring Security.
  * Персистентное хранение истории матчей, игровых полей и статистики игроков в PostgreSQL через Spring Data JPA.
  * Модульная слоистая архитектура (Controller ➔ Service ➔ Repository ➔ Entity) с валидацией ходов и обработкой состояния игровых сессий.

---

## 🛠️ Технологический стек

| Область | Технологии |
| :--- | :--- |
| **Языки программирования** | Python 3.10+, Java 21, Rust, JavaScript / TypeScript, SQL, Bash |
| **Бэкенд и микросервисы** | FastAPI, Spring Boot 3, aiohttp, Node.js (Express), REST API, WebSockets |
| **Системная разработка & WebRTC** | LiveKit SFU, wry/tao, Edge WebView2, FFmpeg (libsoxr), PCM аудио, iptables |
| **Data & AI / NLP** | LLM (Groq, OpenAI, Gemini), RAG, Prompt Engineering, Guardrails, GLiNER, FlashText |
| **Базы данных & брокеры** | PostgreSQL, SQLite, Redis |
| **DevOps & инфраструктура** | Docker, Docker Compose, Linux VPS (Ubuntu/Debian), Nginx, Caddy, Git |
| **Тестирование** | Pytest, Unittest, Playwright, TDD |

---

## 📫 Контакты
* GitHub: [@nikitos7626](https://github.com/nikitos7626)
