# 💾 Disk Part Helper v0.23 beta

[![Version](https://img.shields.io/badge/version-0.23--beta-orange)](https://github.com/MRGenius255/helper_sdd_hdd/releases)
[![Platform](https://img.shields.io/badge/platform-Windows-blue)](https://github.com/MRGenius255/helper_sdd_hdd)
[![License](https://img.shields.io/badge/license-MIT-green)](https://github.com/MRGenius255/helper_sdd_hdd/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/MRGenius255/helper_sdd_hdd)](https://github.com/MRGenius255/helper_sdd_hdd/stargazers)
[![GitHub downloads](https://img.shields.io/github/downloads/MRGenius255/helper_sdd_hdd/total)](https://github.com/MRGenius255/helper_sdd_hdd/releases)

**Disk Part Helper** — простая портативная утилита для Windows, которая помогает быстро назначить букву диску с помощью встроенной команды `diskpart`.

> 🇷🇺 Русский | 🇬🇧 English | 👨‍💻 Автор: **MRGenius255**

**Disk Part Helper** — простая портативная утилита для Windows, которая помогает быстро назначить букву диску с помощью встроенной команды `diskpart`.

> 🇷🇺 Русский | 🇬🇧 English | 👨‍💻 Автор: **MRGenius225**

---

## 📌 О программе

Бывают ситуации, когда диск подключен к компьютеру, но **не отображается в "Моём компьютере"**.  
Чаще всего проблема в том, что тому не назначена буква.

**Disk Part Helper** решает эту проблему в 4 простых шага:
1. Запускает `diskpart` от администратора
2. Показывает список томов
3. Помогает выбрать нужный том
4. Назначает букву

---

## ✨ Возможности

- ✅ **Двуязычный интерфейс** (Русский / English)
- ✅ **Автоматический запуск** `diskpart` с правами администратора
- ✅ **Пошаговые инструкции** прямо в консоли
- ✅ **Не требует установки** — скачал и запустил
- ✅ **Минималистичный дизайн** в стиле командной строки
- ✅ **Портативность** — работает с флешки
- ✅ **Открытый исходный код** от MRGenius225

---

## 🖥️ Системные требования

- ОС: **Windows 7/8/10/11**
- Права **администратора** (обязательно)
- Свободное место: **1 МБ**

---

## 📥 Установка и запуск

### Вариант 1: Скачать готовый файл
1. Перейди в раздел **[Releases](https://github.com/MRGenius225/disk-part-helper/releases)**
2. Скачай файл `disk_part_helper.bat`
3. Нажми **правой кнопкой мыши** → **Запуск от имени администратора**

### Вариант 2: Клонировать репозиторий
```bash
git clone https://github.com/MRGenius225/disk-part-helper.git
cd disk-part-helper
disk_part_helper.bat
