# 👋 Vladislav (`@BeerLover47`)

Инженер, увлечённый системным администрированием Linux, устройством реляционных баз данных (PostgreSQL) и автоматизацией инфраструктуры.

---

## 🛠️ Стек технологий

### Системы и автоматизация
<p align="left">
  <a href="#"><img src="https://img.shields.io/badge/Linux-Ubuntu_24.04_LTS-1E232A?style=for-the-badge&logo=ubuntu&logoColor=E95420&labelColor=161B22" alt="Ubuntu"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Bash-5.2%2B-1E232A?style=for-the-badge&logo=gnu-bash&logoColor=4EAA25&labelColor=161B22" alt="Bash"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Git-VCS-1E232A?style=for-the-badge&logo=git&logoColor=F05032&labelColor=161B22" alt="Git"/></a>
  <a href="#"><img src="https://img.shields.io/badge/WSL2-Ubuntu-1E232A?style=for-the-badge&logo=linux&logoColor=FCC624&labelColor=161B22" alt="WSL2"/></a>
</p>

### Базы данных и хранение
<p align="left">
  <a href="#"><img src="https://img.shields.io/badge/PostgreSQL-16-1E232A?style=for-the-badge&logo=postgresql&logoColor=4169E1&labelColor=161B22" alt="PostgreSQL"/></a>
  <a href="#"><img src="https://img.shields.io/badge/SQL-ANSI_Standard-1E232A?style=for-the-badge&logo=sqlite&logoColor=00599C&labelColor=161B22" alt="SQL"/></a>
</p>

### Мониторинг, телеметрия и веб
<p align="left">
  <a href="#"><img src="https://img.shields.io/badge/Prometheus-v2.54%2B-1E232A?style=for-the-badge&logo=prometheus&logoColor=E6522C&labelColor=161B22" alt="Prometheus"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Grafana-v11%2B-1E232A?style=for-the-badge&logo=grafana&logoColor=F46800&labelColor=161B22" alt="Grafana"/></a>
  <a href="#"><img src="https://img.shields.io/badge/GoAccess-TUI_%26_Web-1E232A?style=for-the-badge&logo=nginx&logoColor=009639&labelColor=161B22" alt="GoAccess"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Nginx-1.24%2B-1E232A?style=for-the-badge&logo=nginx&logoColor=009639&labelColor=161B22" alt="Nginx"/></a>
</p>

---

## 📌 Избранные проекты

### 🛠️ [Bash DevOps Toolkit](https://github.com/BeerLover47/linux-system-monitor)
Модульный набор из 9 автономных инструментов системного администрирования на чистом Bash:
* **Storage Operations:** параметрический генератор файлов и каталогов по алфавитной маске (`fallocate`), стресс-тест дисковой подсистемы с контролем порога в 1 Гб и 3 режима безопасной очистки файловой системы.
* **Log Pipeline:** эмулятор веб-трафика Nginx в Combined Log Format, потоковый фильтр логов на AWK с дедупликацией в памяти ($O(N)$) и генерация интерактивных отчётов в GoAccess.
* **Telemetry & Observability:** оркестрация Prometheus + Node Exporter + Grafana, сценарии нагрузочного тестирования (`stress`, `iperf3`) и нативный Bash-экспортер метрик операционной системы под Nginx.

### 🐘 [PostgreSQL Intensive & Architecture Notes](https://github.com/BeerLover47/postgresql-bootcamp)
Практический интенсив и инженерные конспекты по реляционной модели данных и PostgreSQL:
* Физический порядок выполнения запросов движком (`FROM` $\rightarrow$ `WHERE` $\rightarrow$ `GROUP BY` $\rightarrow$ `SELECT` $\rightarrow$ `ORDER BY`).
* Трёхзначная предикатная логика SQL и особенности работы с `NULL`.
* Реляционная алгебра: теория множеств (`UNION`, `INTERSECT`, `EXCEPT`), соединения (INNER, OUTER, CROSS JOIN) и устранение декартовых произведений.
* Индексирование (B-Tree, GiST), чтение планов выполнения (`EXPLAIN ANALYZE`) и аналитические оконные функции.

---

## 🔭 Текущий фокус

* Углубляюсь во внутреннее устройство движка PostgreSQL: Query Planner, Cost-based оптимизатор, транзакционные блокировки и MVCC.
* Автоматизация инфраструктурных задач и системное программирование в среде Linux.
