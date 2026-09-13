# Привет! Я Михаил Мамонов 👋

**Middle/Senior Backend Engineer (.NET) | 7+ лет в Enterprise-разработке**

Проектирую и разрабатываю отказоустойчивые микросервисные системы и высоконагруженные интеграционные решения на стеке **.NET**. 

Мой опыт в **Go** и **Java**, а также низкоуровневое программирование на **C**, не просто расширяют кругозор: они позволяют мне глубже понимать работу с памятью, конкурентность и издержки абстракций. Это помогает мне писать более оптимизированный, предсказуемый и эффективный код на C#, избегая типичных ловушек фреймворков.

---

### 🛠 Технологический стек

- **Языки:** C# (основной), SQL, Go, Java (для кросс-платформенных и специфичных задач).
- **Фреймворки:** .NET 8/9, ASP.NET Core (WebAPI, MVC), Entity Framework Core, gRPC.
- **Базы данных и брокеры:** PostgreSQL, MS SQL Server, MongoDB, Apache Kafka, RabbitMQ.
- **Инфраструктура и DevOps:** Docker, Kubernetes, GitLab CI, Linux, Kibana / Elasticsearch.
- **Архитектура и практики:** DDD, Clean Architecture, SOLID, Microservices, Saga, Outbox, Idempotency, TDD, оптимизация SQL-запросов.

---

### 🚀 Избранные проекты и архитектурные решения

| Проект | Описание и применимость к .NET | Стек |
| :--- | :--- | :--- |
| **[Order Management System](https://github.com/MikhailMamonov/go-order-management-system)** | Эталон микросервисной архитектуры. Реализация распределенных транзакций (Saga), асинхронной обработки событий и идемпотентности. Паттерны напрямую транслируются в .NET-микросервисы (например, с MassTransit/Kafka). | `Go`, `gRPC`, `Kafka`, `PostgreSQL`, `Docker` |
| **[Smart Subscription Registry](https://github.com/MikhailMamonov/smart-subscription-registry)** | Платформа управления подписками с фокусом на транзакционную целостность финансовых операций и строгую Clean Architecture. | `Java`, `Spring Boot`, `PostgreSQL`, `JUnit` |
| **[C5 Decimal](https://github.com/MikhailMamonov/C5_decimal)** | Низкоуровневая библиотека арифметики на C. Дает глубокое понимание аллокаций и указателей, что позволяет мне писать высокооптимизированный `zero-allocation` код на C# (используя `Span<T>`, `ArrayPool`, `ref struct`). | `C`, `CMake`, `Unit Testing` |

---

### 💡 Мой инженерный подход

1. **Надежность по умолчанию:** Проектирую системы с учетом сетевых сбоев. Асинхронная коммуникация (Kafka/RabbitMQ), паттерны Outbox, Retry-политики и идемпотентность — это стандарт, а не опция.
2. **Понимание «под капотом» (.NET CLR и не только):** Я не просто вызываю методы EF Core. Я анализирую сгенерированные SQL-запросы, понимаю работу Garbage Collector и использую инструменты профилирования для устранения узких мест в производительности.
3. **Чистота кода и тестируемость:** Строго разделяю слои (бизнес-логика вынесена из контроллеров, используются DTO), следую принципам SOLID и DDD. Unit- и интеграционные тесты (xUnit/NUnit) — обязательная часть Definition of Done.

---

### 📫 Как со мной связаться

- 📧 **Email:** [mamon201071@gmail.com](mailto:mamon201071@gmail.com)
- ✈️ **Telegram:** [@Mikhail_M20](https://t.me/Mikhail_M20)
- 💼 **Резюме:** [HH.ru](https://hh.ru/resume/7db8ff39ff10f67cc90039ed1f6754484f5051)
- 💻 **GitHub:** [github.com/MikhailMamonov](https://github.com/MikhailMamonov)
