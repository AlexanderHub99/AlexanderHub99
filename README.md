<h1 align="center">Привет, я Александр — Backend Developer (.NET/C#) 🚀</h1>
<p align="center">
  Строю высоконагруженные real-time сервисы на ASP.NET Core + PostgreSQL, оптимизирую GC/аллокации, люблю профилировать и добиваться аптайма 99.9%+
</p>

<p align="center">
  <a href="mailto:agames1448@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-agames1448%40gmail.com-informational?logo=gmail"></a>
  <a href="https://github.com/AlexanderHub99"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-AlexanderHub99-black?logo=github"></a>
  <img alt="Location" src="https://img.shields.io/badge/Москва-RU-blue">
  <img alt="Relocation" src="https://img.shields.io/badge/Готов%20к-релокации%20и%20командировкам-success">
</p>

---

## 🧭 Обо мне
Backend developer (C#, .NET, PostgreSQL). Проектирую и разрабатываю отказоустойчивые Web API и real-time системы (WebSocket, бинарные протоколы). Работаю с PostgreSQL (Npgsql, Dapper), закладываю оптимизацию на этапе дизайна, люблю профилировать PerfView/VS Profiler, снижать аллокации и паузы GC. Цель — предсказуемая производительность и аптайм ≥99.9%.

- 📍 Москва • Гражданство: РФ • Разрешение на работу: РФ, Беларусь, Грузия, Казахстан  
- 🧑‍💻 Опыт: 5+ лет (09.2020 → н.в.)  
- 🌐 Портфолио: этот GitHub  
- ☎️ Связь (предпочтительно): **+7 928 147-76-29** ・ **agames1448@gmail.com**

---

## 🏆 Ключевые достижения
- Реал-тайм сервер для мультиплеера (WebSocket, бинарный протокол): **~1000–1200 CCU/shard**, фан-аут 10–30k msg/мин/узел  
- Задержки: **p95 ~30–60 мс**, GC p99 **<10–15 мс** на типовой нагрузке  
- Снижение аллокаций на **50–70%**, CPU на **15–20%** (ArrayPool, фиксированные буферы, собственные пулы сообщений)  
- Надёжность: **99.9% аптайм**, авто-восстановление соединений, backpressure/rate-limit, разделение на сервисы + **RabbitMQ**  
- Бэкенд-логин с **JWT**, метрики/логи (**Prometheus/Grafana**), CI/CD (**GitHub Actions**, Docker)  
- Единый кроссплатформенный **Unity SDK** (Android/iOS/Web/Unity) — интеграции **31+ SDK**, ускорение интеграций в **5–10×**, −95% дефектов

---

## 🛠️ Технологии
**Языки/платформа:** C# 10–12, .NET 6–8, async/await, TPL  
**Web/RT:** ASP.NET Core (Kestrel), WebSocket (ws/wss), REST, JWT  
**Данные:** PostgreSQL (Npgsql), **Dapper**, индексы, миграции, профилирование запросов  
**Очереди:** RabbitMQ  
**Тесты:** NUnit, Testcontainers  
**Инфра:** Docker/Compose, Linux, GitHub Actions, Prometheus, Grafana  
**Unity:** 2019+, серверная генерация воксельных карт, синхронизация состояний, матчмейкинг, шардинг  
**Desktop:** WPF/MVVM, XAML, многопоточность (SemaphoreSlim, CTS, Concurrent\*)  
**Мобильная/интеграции:** Android (Java/JNI), iOS (Obj-C/C++ bridge), Web (JS), CDP (Chrome DevTools Protocol)

<p>
  <img alt="C#" src="https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white">
  <img alt=".NET" src="https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white">
  <img alt="Dapper" src="https://img.shields.io/badge/Dapper-0C4A6E">
  <img alt="RabbitMQ" src="https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black">
  <img alt="Unity" src="https://img.shields.io/badge/Unity-000000?logo=unity&logoColor=white">
  <img alt="WPF" src="https://img.shields.io/badge/WPF-5C2D91?logo=.net&logoColor=white">
</p>

---

## 👷‍♂️ Опыт
### Team Lead Backend (.NET, Real-time, Unity) — **Full HP (ООО «Фаренгейт Лаб»)** · 01.2024 → н.в.
Проект **Block Combat Online** (FPS, процедурная генерация), поддержка единого кроссплатформенного **Unity SDK (90/10)**.  
**Стек:** ASP.NET Core/Kestrel, WebSocket, PostgreSQL + Dapper, RabbitMQ, Docker, Linux, NUnit, Prometheus/Grafana, GitHub Actions, Unity 2019+

**Что сделал:**
- Сервер мультиплеера с бинарным протоколом, безопасная рассылка (SemaphoreSlim, CTS, Concurrent Collections), троттлинг, фан-аут
- Шардирование, комнаты/матчмейкинг, синхронизация позиций/анимаций/снарядов
- Индексы и пулы соединений, p95 горячих запросов **~8–15 мс**
- Процессы: команда 3 чел., code review, ускоренные релизы и стабильное качество

### Team Lead Backend — **Единый кроссплатформенный Unity SDK** · 01.2023 → 01.2024
Фасадный SDK под Android/iOS/Web/Unity, интеграция **31+** сторонних SDK (аналитика, реклама, платежи).  
**Результат:** 5–10× быстрее интеграции, −95% дефектов интеграций, единый API/конфиг, автотесты/песочницы.

### Middle Backend Developer (gamedev) · 01.2022 → 01.2023  
SDK/реклама/аналитика/покупки, релизы, метрики. Сборки под WebGL/Android/iOS. Оптимизация размера клиента (−10–20%).

### Middle Backend Developer · 01.2021 → 01.2022  
Переход на Dapper и REST, кэширование/индексы → −15–25% к времени ответов горячих эндпоинтов.

### Junior Backend Developer · 09.2020 → 01.2021  
Интеграция библиотек/SDK, 10+ завершённых интеграций, проектирование простых API.

---

### Middle .NET/WPF Engineer — **BettinCo** · 01.2022 → 09.2024 (part-time)
Миграция WinForms → **WPF/MVVM**, контроллер хром-ботов на **CDP**, унификация сценариев автоматизации.  
**Достижения:** 2–3× быстрее фичи, −95% ручных операций, −95% инцидентов утечки памяти, масштабирование до **20–40 параллельных ботов** на рабочую станцию.

---

## 📚 Образование и сертификаты
- **РКСИ**, Информационные системы и программирование — 2020  
- **C# Продвинутый (hh.ru, Теория)** — 2025  
- **SQL Skypro (Skypro)** — 2025  
- **ООП — Продвинутый уровень** — 2025

---

## 🔤 Языки
Русский — родной · Английский — **B1**

---

## 🤝 Рекомендации
- **Владимир Манюнин** — Team Lead отдела аналитики, ООО «Фаренгейт Лаб»: связь по запросу
- **Денис Федчинко** — Директор, ООО «Фаренгейт Лаб»: связь по запросу

---

## 📦 Проекты/темы, в которых силён
- Real-time: WebSocket, бинарные протоколы, фан-аут, backpressure/rate-limit, авто-reconnect  
- Производительность: ArrayPool\<T\>, фиксированные буферы, пулы сообщений, PerfView/VS, снижение аллокаций/GC-пауз  
- Данные: PostgreSQL + Dapper, индексы, миграции, p95 запросов 8–15 мс  
- Надёжность: 99.9% аптайм, метрики/алерты (Prometheus/Grafana), feature flags, изоляция сервисов + RabbitMQ  
- Unity-сервер: воксельные карты, синхронизации, матчмейкинг, шардинг  
- Desktop/WPF: MVVM, многопоточность, оркестрация CDP-ботов (20–40 параллельных)

---

## 📈 GitHub статистика
<p align="center">
  <a href="https://github.com/anuraghazra/github-readme-stats">
    <img height="160" src="https://github-readme-stats.vercel.app/api?username=AlexanderHub99&show_icons=true&hide_title=true&include_all_commits=true&rank_icon=github" alt="GitHub Stats">
  </a>
  <a href="https://git.io/streak-stats">
    <img height="160" src="https://streak-stats.demolab.com?user=AlexanderHub99" alt="GitHub Streak">
  </a>
</p>
