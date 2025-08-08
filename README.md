# SectLauncher

![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white)

Кроссплатформенный лаунчер для Minecraft с современным интерфейсом и модульной архитектурой.

## 📖 Описание

SectLauncher - это современный лаунчер для Minecraft, разработанный с использованием принципов Clean Architecture и Kotlin Multiplatform. Проект создан для обеспечения стабильной и удобной работы с различными версиями Minecraft, модами и серверами.

### ✨ Особенности

**MVP функции:**
- 🔐 Авторизация через Mojang аккаунт
- 📦 Выбор и скачивание версий Minecraft
- 🚀 Запуск игры
- 🔄 Оффлайн-режим

**Дополнительные возможности:**
- 👤 Мультипрофили
- 🔧 Управление модами и модпаками (CurseForge)
- 🔄 Автообновления лаунчера и игры
- 📰 Новости и обновления от серверов
- 🌐 Поддержка серверов (список, подключение)


---

## 🧩 Модульность
Каждый парсер источников (Mojang API, CurseForge, Modrinth) реализован как отдельный модуль для легкого расширения и поддержки.


## 🛠️ Технологии

- **Язык**: Kotlin
- **Платформа**: Kotlin Multiplatform
- **UI**: Jetpack Compose Desktop
- **Сборка**: Gradle
- **Архитектура**: Clean Architecture
- **Тестирование**: Unit-тесты для use cases

## 🚀 Установка и запуск

### Требования
- JDK 17+
- Gradle 8.0+

## 🗺️ Roadmap

### Версия 1.0 (MVP)
- [x] Базовая архитектура
- [x] Авторизация Mojang
- [x] Скачивание версий Minecraft
- [x] Запуск игры
- [x] Базовый UI

### Версия 1.1
- [x] Мультипрофили
- [ ] Управление модами
- [ ] CurseForge интеграция

### Версия 2.0
- [ ] Поддержка macOS
- [ ] Поддержка Linux
- [ ] Modrinth интеграция
- [ ] Автообновления
