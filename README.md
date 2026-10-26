<p align="center">
  <img src="KiwiFarm.png" alt="KiwiFarm" width="96">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/KiwiFarm-2.18--wotlk-7fff72?style=for-the-badge&logo=appveyor">
  <img src="https://img.shields.io/badge/WotLK-3.3.5a-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/status-stable-brightgreen?style=for-the-badge">
</p>

<h1 align="center">KiwiFarm — WotLK 3.3.5a backport</h1>

<p align="center">
  <b>Instance reset and gold tracking addon for World of Warcraft 3.3.5a (WotLK).</b><br>
  <i>Backport of KiwiFarm by MiCHaeL, maintained for the 3.3.5a client.</i>
</p>

<p align="center">
  <a href="#english">English</a> ·
  <a href="#russian">Русский</a>
</p>

---

<a name="english"></a>
## English

<p align="center">
  <a href="#features">Features</a> ·
  <a href="#installation">Installation</a> ·
  <a href="#compatibility">Compatibility</a> ·
  <a href="#license">License</a> ·
  <a href="#credits">Credits</a>
</p>

### About

**KiwiFarm** keeps track of a farm: instance resets and their hourly limit, gold
from cash, items and quests, looted items, XP, and mob/item counts. It can
announce resets to your party or raid and value loot using vendor or
auction-house prices. This repository is the **WotLK 3.3.5a backport** of
KiwiFarm.

<a name="features"></a>
### Features

#### Reset tracking

Counts instance resets and shows the WotLK limit of five resets per hour,
tracked per server. Shift-click the main window to reset instances; an optional
message announces resets to your party or raid.

#### Gold and sessions

Start, pause, resume, or finish a farm session. The window shows gold per hour,
total gold, cash, item sales, quest rewards, and a breakdown by item quality.
Loot is valued with vendor prices or data from Auctionator, TSM, Aux, and
RECrystallize.

#### Loot and XP

Keeps a list of looted items with quantity and value, plus session XP per hour,
XP remaining, XP from the last pull, and level-up tracking. Mob and item
counters round out the session summary.

#### Interface

Movable main window, minimap button, DataBroker launcher, right-click config
menu, lock and reset controls, and a configurable notification output
(Blizzard floating combat text, MSBT, or Parrot2).

#### Localization

Ten client locales: deDE, enUS, esES, frFR, itIT, koKR, ptBR, ruRU, zhCN, zhTW.

<a name="installation"></a>
### Installation

1. Download the latest release (or clone this repository).
2. Extract the archive.
3. Move the **KiwiFarm** folder into:
   ```
   \Interface\AddOns\
   ```
4. Enable it on the character-select AddOns screen and launch the game.
   Type `/kfarm config` to open settings, or right-click the main window.

<a name="compatibility"></a>
### Compatibility

- Built and tested on **Warmane** (WoW 3.3.5a, Interface `30300`).
- Requires the **3.3.5a client** (build 12340); this is not a Classic or retail addon.
- Optional dependencies: `LibSharedMedia-3.0` and `LibItemUpgradeInfo-1.0`.
- Notification output can use Blizzard floating combat text, MSBT, or Parrot2.
- Other 3.3.5a servers are not tested.

<a name="license"></a>
### License

KiwiFarm is distributed under the GNU General Public License v3.0, the same
license as the original addon. See [LICENSE](LICENSE).

<a name="credits"></a>
### Credits

- Original addon: [michaelnpsp/KiwiFarm](https://github.com/michaelnpsp/KiwiFarm) by **MiCHaeL**
- WotLK 3.3.5a backport: **Keoo**
- Discord: https://discord.gg/sKpJbUrsvR

---

<a name="russian"></a>
## Русский

<p align="center">
  <a href="#возможности">Возможности</a> ·
  <a href="#установка">Установка</a> ·
  <a href="#совместимость">Совместимость</a> ·
  <a href="#лицензия">Лицензия</a> ·
  <a href="#благодарности">Благодарности</a>
</p>

### Об аддоне

**KiwiFarm** ведёт учёт фарма: сбросы подземелий и их лимит в час, золото из
наличных, предметов и квестов, собранные предметы, опыт и счётчики мобов и
предметов. Аддон может сообщать группе или рейду о сбросе подземелий и
оценивать добычу по цене вендора или аукционным данным. Это **бэкпорт
KiwiFarm под WoW 3.3.5a (WotLK)**.

<a name="возможности"></a>
### Возможности

#### Сбросы подземелий

Считает сбросы и показывает лимит WotLK — пять сбросов в час, отдельно для
каждого сервера. Shift-клик по главному окну сбрасывает подземелья; можно
включить сообщение о сбросе в группу или рейд.

#### Золото и сессии

Сессию можно начать, поставить на паузу, продолжить или завершить. Окно
показывает золото в час, всего золота, наличные, продажу предметов, награды за
задания и разбивку по качеству предметов. Добыча оценивается по цене вендора
или данным Auctionator, TSM, Aux и RECrystallize.

#### Добыча и опыт

Список собранных предметов с количеством и ценой, а также опыт в час, остаток
опыта, опыт за последний пул и повышение уровня. В сводке есть счётчики мобов и
предметов.

#### Интерфейс

Перемещаемое главное окно, кнопка на миникарте, запуск через DataBroker, меню
настроек по правому клику, блокировка и сброс, настраиваемый вывод уведомлений
(всплывающий текст Blizzard, MSBT или Parrot2).

#### Локализация

Десять локалей клиента: deDE, enUS, esES, frFR, itIT, koKR, ptBR, ruRU, zhCN,
zhTW.

<a name="установка"></a>
### Установка

1. Скачайте последний релиз (или клонируйте репозиторий).
2. Распакуйте архив.
3. Переместите папку **KiwiFarm** в:
   ```
   \Interface\AddOns\
   ```
4. Включите аддон на экране выбора персонажа и запустите игру. Введите
   `/kfarm config`, чтобы открыть настройки, или нажмите правой кнопкой по
   главному окну.

<a name="совместимость"></a>
### Совместимость

- Собрано и протестировано на **Warmane** (WoW 3.3.5a, Interface `30300`).
- Требуется клиент **3.3.5a** (build 12340); это не аддон для Classic или retail.
- Необязательные зависимости: `LibSharedMedia-3.0` и `LibItemUpgradeInfo-1.0`.
- Уведомления можно выводить через всплывающий текст Blizzard, MSBT или Parrot2.
- Другие серверы 3.3.5a не тестировались.

<a name="лицензия"></a>
### Лицензия

KiwiFarm распространяется по GNU General Public License v3.0 — той же
лицензии, что и оригинальный аддон. Подробности — в [LICENSE](LICENSE).

<a name="благодарности"></a>
### Благодарности

- Оригинальный аддон: [michaelnpsp/KiwiFarm](https://github.com/michaelnpsp/KiwiFarm) — **MiCHaeL**
- Бэкпорт под WotLK 3.3.5a: **Keoo**
- Discord: https://discord.gg/sKpJbUrsvR
