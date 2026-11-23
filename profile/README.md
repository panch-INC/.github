<div align="center">

# ⚡ panch INC.

**Высокопроизводительная коммуникационная экосистема нового поколения: мгновенный мессенджер, голосовые и видеокомнаты, стриминг и платформа приложений.**

[![Платформа](https://img.shields.io/badge/Платформа-PanchLine-blueviolet.svg)](https://panchline.ru)
[![Статус](https://img.shields.io/badge/Статус-Production-brightgreen.svg)](https://panchline.ru/healthz)
[![Организация](https://img.shields.io/badge/GitHub-panch--INC-black.svg?logo=github)](https://github.com/panch-INC)

[🌐 Веб-версия](https://panchline.ru/messenger) •
[🖥️ Десктоп-приложение](https://panchline.ru/download) •
[📱 Скачать Android APK](https://panchline.ru/download/android) •
[⚙️ Серверное ядро](https://github.com/panch-INC/panchline-core)

</div>

---

### 🧩 Репозитории экосистемы PanchLine

Все компоненты платформы разделены по специализированным репозиториям по образцу передовых открытых экосистем:

| Компонент | Репозиторий | Стек технологий | Описание |
| :--- | :--- | :--- | :--- |
| ⚙️ **Серверное ядро** | [**`panchline-core`**](https://github.com/panch-INC/panchline-core) | Go 1.24, Postgres 18, Redis 8, LiveKit SFU | Единый демон платформы (`panchlined`), WebSocket/SSE шлюз, LiveKit SFU, версионированные миграции БД, Outbox воркер, Bot API и обратный прокси Caddy |
| 🌐 **Веб-клиент** | [**`panchline-web`**](https://github.com/panch-INC/panchline-web) | React 19, TypeScript, Vite, WebRTC | Полнофункциональный адаптивный веб-клиент и устанавливаемый Progressive Web App (PWA) |
| 🖥️ **Десктоп-клиент** | [**`panchline-desktop`**](https://github.com/panch-INC/panchline-desktop) | Electron, Vite, TypeScript | Нативное приложение для Windows, macOS и Linux с системным треем, захватом системного звука при демонстрации экрана и автообновлениями |
| 📱 **Android-клиент** | [**`panchline-android`**](https://github.com/panch-INC/panchline-android) | Kotlin, Jetpack Compose, Media3 | Нативное мобильное приложение с аппаратным WebRTC, push-уведомлениями FCM, голосовыми сообщениями и видеокружочками |

---

### 🚀 Ключевые возможности платформы

* **Мгновенный обмен сообщениями**: Сверхбыстрая доставка без задержек по WebSocket, поддержка Markdown, моментальный полнотекстовый поиск, редактирование, треды, реакции, стикеры, голосовые сообщения и видеокружочки.
* **Голосовые и видеоканалы (Discord/Stoat-уровень)**: Голосовые пространства серверов, приватные звонки тет-а-тет и групповые конференции на базе масштабируемого LiveKit SFU с чистым звуком и аппаратным эхоподавлением.
* **Трансляции и медиа**: Видеостриминг с ультранизкой задержкой (MediaMTX WebRTC/HLS/RTMPS), демонстрация экрана со звуком, лента коротких видеороликов (Shorts) и стена профиля.
* **Открытая платформа ботов и Mini Apps**: Интерактивные мини-приложения в чатах (HTML5/Canvas), богатый Bot API (совместимый по логике с Telegram), кастомные клавиатуры и JavaScript SDK.
* **Self-Hosted & Zero Downtime**: Удобный запуск полного серверного стека через Docker Compose с готовыми сертификатами Caddy, мониторингом и бесшовным обновлением.

---

### 🛠️ Быстрый старт серверной части (Self-Hosted)

```bash
# Клонирование репозитория серверного ядра
git clone https://github.com/panch-INC/panchline-core.git
cd panchline-core

# Настройка переменных окружения
cp .env.example .env

# Запуск всех сервисов платформы
bash start.sh
```

---

### 👥 Команда и доступ

В организации **panch INC.** настроен автоматический доступ с правами записи для всех участников команды ко всем приватным и публичным репозиториям проекта.

<div align="center">
  <sub>Создано с ❤️ командой panch INC. · <a href="https://panchline.ru">panchline.ru</a></sub>
</div>
