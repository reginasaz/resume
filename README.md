# Веб-резюме (DWH / Analytics Engineer)

Статическая версия интерактивного резюме. Развернуто на платформе GitHub Pages.

🔗 **Ссылка на сайт:** https://reginasaz.github.io/resume/

---

## ⚙️ Спецификации реализации

| Компонент | Технологический стек | Реализованная логика |
| :--- | :--- | :--- |
| **Печать и экспорт** | CSS `@media print` (формат А4) | Настроены поля `15mm` и запрет разрыва карточек опыта на стыке страниц. Принудительно отключаются темные фоны для экономии тонера принтера при печати. |
| **Смена темы** | JavaScript + `localStorage` | Переключение между темной и светлой темами. Выбранное состояние сохраняется в памяти браузера клиента и не сбрасывается при обновлении страницы. |
| **Оптимизация** | Локальные файлы (`.woff2`) | Все шрифты загружаются из локальной папки `/fonts`. Внешние сетевые запросы к Google CDN исключены. Добавлен скрипт скрытия битых иконок при ошибке загрузки. |
| **Адаптивность** | CSS Grid & Flexbox | Двухколоночная структура на десктопах (`max-width: 1200px`) автоматически перестраивается в одну колонку на мобильных устройствах (`max-width: 768px`). |

---

## 🔤 Карта шрифтов

* **Заголовки и имя:** `Plus Jakarta Sans` — используется в интерфейсе **Google Looker Studio**.
* **Основной текст:** `Inter` — используется в интерфейсе **Yandex DataLens**.
* **Бейджи навыков:** `JetBrains Mono` — моноширинный код-шрифт для быстрого считывания стека.

---

## 🛠️ Основной стек технологий

* **DWH & Engineering:** ClickHouse, SQL (DML/DDL), Apache Airflow, Python, BigQuery, ETL / ELT, Data Modeling
* **BI & Cloud Infrastructure:** Yandex Cloud, Yandex DataLens, Looker Studio, Analytics Engineering, Data Quality
* **MarTech & Web Analytics:** Сквозная аналитика, GTM, Яндекс Метрика, Google Analytics

---

## 📬 Контакты

* **Telegram:** [@geginja](https://t.me/geginja)
* **Email:** [rsazgutdinova@bk.ru](mailto:rsazgutdinova@bk.ru)
* **hh.ru Profile:** [Прямая ссылка](https://hh.ru/resume/d6dd3ff3ff11461daa0039ed1f34556570306d)
