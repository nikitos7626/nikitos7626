# Привет, я Никита! 👋

Разрабатываю масштабируемые бэкенд-сервисы на **Java 21 / Spring Boot 3** и **Python / FastAPI**, а также высокопроизводительные NLP/AI-пайплайны и сетевые приложения.

---

## ⚡ Избранные проекты (Flagship Projects)

### 1. [Модуль Контроля Качества Данных — ККД (sber-kkd-service)](https://github.com/nikitos7626/sber-kkd-service)
> **Корпоративный сервис аудита качества OKR-целей и метрик подразделений на Java 21 и Spring Boot 3**

* **Стек:** Java 21, Spring Boot 3.3.5, PostgreSQL 16, Liquibase 4.27, Docker Compose, JUnit 5, Gradle.
* **Фичи:**
  * Реализация 6 бизнес-правил аудита данных целей и ключевых результатов (OKR) с расчётом каскадированных метрик по иерархии подразделений.
  * Вычисление дельты динамики качества относительно предыдущего прогона и REST API для фронтенд-дашборда.
  * Версионирование схемы БД через Liquibase, контейнеризация в Docker Compose и **39 проходящих автотестов**.

---

### 2. [Product Attribute Extractor (product-attribute-extractor)](https://github.com/nikitos7626/product-attribute-extractor)
> **Промышленный каскадный NLP-сервис автоматического извлечения и валидации характеристик товаров каталога e-commerce**

* **Стек:** Python 3.10+, FastAPI, FlashText (Ахо-Корасик), GLiNER (Zero-Shot NER), PyTorch (CPU), Catalog KB (9 700+ моделей), Docker.
* **Фичи:**
  * Пропускная способность **> 680 карточек/сек** на одном яре CPU (задержка **< 1.5 мс** на карточку) без GPU.
  * Каскадная многоуровневая архитектура (Tier 1–4) с предохранителем \Circuit Breaker\ и проверкой заземления фактов (\GroundingVerifier\).
  * Интерактивное рабочее место контент-модератора (**Human-in-the-Loop**) со скорингом уверенности (\confidence\) и обратной связью.
  * Покрыт **208 автотестами** (100% green).

---

### 3. [Career Hub AI (career-hub-bot)](https://github.com/nikitos7626/career-hub-bot)
> **Автономная CRM-система мониторинга IT-вакансий с 9 площадок, нейросетевым скорингом и клиентом Telegram Mini App**

* **Стек:** Python 3.12+, Groq LLM API, asyncio, Telegram WebApp SDK, Tailwind CSS, Lucide Icons, Docker Compose.
* **Фичи:**
  * Мониторинг и агрегация вакансий с **HeadHunter, Хабр Карьеры, SuperJob, GetMatch, LinkedIn, СЕТИ, Работа.ру, Telegram-каналов**.
  * Интеллектуальный скоринг соответствия профилю (1–10) с генерацией персонализированных технических сопроводительных писем.
  * Два режима интерфейса: **Tinder-свайпы** жестами/клавиатурой и подробный **Канбан-дашборд** со статистикой воронки.
  * Полное покрытие интеграционными тестами (82 теста: защита от DoS, CSRF, replay attacks и XSS).

---

### 4. [VOLT (olt-voice)](https://github.com/nikitos7626/volt-voice)
> **Self-Hosted мессенджер с 2K 60fps демонстрацией экрана, студийным музыкальным плеером и нативным клиентом на Rust**

* **Стек:** Rust (\	ao\ + \wry\), LiveKit SFU, Python 3.12, FFmpeg, WebRTC, Caddy, Docker.
* **Фичи:**
  * Потоковая трансляция экрана до ®0×1440 @ 60fps\ (\VP9\,  Mbps\) без ограничений битрейта.
  * Встроенный плеер со сбалансированным звуком, эквалайзером и воспроизведением музыки из Spotify, YouTube, радио и файлов.
  * Нативный Windows-клиент размером всего **~760 КБ** с аппаратной привязкой сессии (\MachineGuid\), автообновлением по \SHA-256\ и защитой от троттлинга в играх.

---

### 5. [Tic-Tac-Toe Multiplayer Service (	ictac-multiplayer-service)](https://github.com/nikitos7626/tictac-multiplayer-service)
> **Бэкенд-сервис для многопользовательской игры в «Крестики-нолики» (PvP/PvE) на Java 21 и Spring Boot 3**

* **Стек:** Java 21, Spring Boot 3.3, Spring Security, Spring Data JPA, Hibernate, PostgreSQL, Gradle.
* **Фичи:**
  * Реализация игрового движка с поддержкой многопользовательских матчей (PvP) и игры против компьютера (PvE).
  * Система регистрации, аутентификации и разграничения прав доступа на базе Spring Security.
  * Персистентное хранение партий в PostgreSQL через Spring Data JPA и кастомный JSONB-конвертер.

---

## 🛠️ Технологический стек

| Область | Технологии |
| :--- | :--- |
| **Языки программирования** | Python 3.10+, Java 21, Rust, JavaScript / TypeScript, SQL, Bash |
| **Бэкенд и микросервисы** | FastAPI, Spring Boot 3, Spring Security, Spring Data JPA, Liquibase, asyncio, Node.js (Express), REST API |
| **Системная разработка & WebRTC** | LiveKit SFU, wry/tao, Edge WebView2, FFmpeg, WebRTC, iptables |
| **Data & AI / NLP** | LLM (Groq, OpenAI, Gemini), RAG, Function Calling, Guardrails, GLiNER, FlashText |
| **Базы данных & брокеры** | PostgreSQL, SQLite, Redis |
| **DevOps & инфраструктура** | Docker, Docker Compose, Linux VPS (Ubuntu/Debian), Nginx, Caddy, Git, Gradle |
| **Тестирование** | JUnit 5, Pytest, Unittest, Playwright |

---

## 📫 Контакты
* 🌐 Веб-резюме: https://resume.v0lt.tech/
* ✉️ Email: nikitos7626@mail.ru
* 💬 Telegram: [@nikitos7626](https://t.me/nikitos7626)
* 💻 GitHub: [@nikitos7626](https://github.com/nikitos7626)
