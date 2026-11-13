<p align="center">
  <img src="media/banner.webp" alt="Angel: a DPS meter and overlay for AION 2" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/nokttsu/angel-releases/releases/latest/download/Angel.exe"><img src="https://img.shields.io/github/v/release/nokttsu/angel-releases?label=Download&amp;style=for-the-badge&amp;color=8b5cf6&amp;logo=windows&amp;logoColor=white" alt="Download Angel" /></a>
  <a href="https://github.com/nokttsu/angel-releases/releases"><img src="https://img.shields.io/github/downloads/nokttsu/angel-releases/total?label=Downloads&amp;style=for-the-badge&amp;color=27272a" alt="Downloads" /></a>
  <a href="https://nokttsu.github.io/angel/"><img src="https://img.shields.io/badge/Website-nokttsu.github.io%2Fangel-27272a?style=for-the-badge" alt="Website" /></a>
</p>

<h1 align="center">Angel — AION 2 DPS meter and overlay</h1>

<p align="center"><b>English</b> · <a href="#русский">Русский</a> · <a href="#한국어">한국어</a></p>

**Angel is a free DPS meter (damage meter) and in-game overlay for AION 2.** It shows your party's damage in AION 2 as you fight: in its own window, and in a small overlay over the game that never takes its focus. One file, no installer, Windows 10 and 11.

<p align="center"><img src="media/overlay.webp" alt="The overlay over the game: a boss fight, only your row, and a PvP opponent" width="100%" /></p>

## What it does

- **Meter.** Every player's damage, DPS, healing and share, by the second and by skill. Boss fights are kept, with your best time per dungeon boss.
- **Overlay.** Over the game and out of its way: your party's bars in a fight, your pet's souls while you farm, your opponent and your chance in PvP. Lock it and clicks go through to the game.
- **PvP.** Each encounter that ends in a death is kept: how it went, exchange by exchange, and the key moments.
- **Events, pets and cubes.** Timers for the events you follow, your pet collection with where each soul drops, and a radar for hidden cubes.
- **Profiles.** A player's gear, skills and combat power from the official site, a click away.
- **15 languages.** English, Russian, German, French, Spanish, Italian, Portuguese, Polish, Dutch, Czech, Swedish, Turkish, Korean, Japanese and Chinese.

<p align="center"><img src="media/meter.webp" alt="The meter: a boss fight, every player's damage and DPS, the party's damage by the second" width="100%" /></p>

## Install

Download: [**Angel.exe**](https://github.com/nokttsu/angel-releases/releases/latest/download/Angel.exe) · [all releases](https://github.com/nokttsu/angel-releases/releases) · [website](https://nokttsu.github.io/angel/)

1. Download [**Angel.exe**](https://github.com/nokttsu/angel-releases/releases/latest/download/Angel.exe) from the latest release.
2. Run it. Windows asks for administrator rights: Angel reads the game's network traffic.
3. If Npcap is not installed, Angel offers to install it (it is built in). Start Angel before you log in to the game.

If Windows SmartScreen stops it, choose **More info → Run anyway**: the exe is not code-signed with a certificate.

## Updates

Angel checks this page's latest release as it starts and every few hours, and installs a new version only when you say so (Settings → Updates). Every exe here is signed: before it replaces itself, Angel checks the download's SHA-256 and its Ed25519 signature against the key built into it, and refuses anything else. What changed is on the [releases page](https://github.com/nokttsu/angel-releases/releases) and in Angel after an update.

## How it works

Angel only reads the traffic the game server sends to your PC, as a packet capture does. It never reads or changes the game's memory, injects nothing and sends nothing to the game. Profiles come from the official AION 2 site; nothing about you is sent anywhere else.

## FAQ

**What is Angel?** A DPS meter for AION 2: a damage meter, a combat log of every boss fight and PvP encounter, and an overlay over the game.

**Does Angel touch the game?** No. It only reads the network traffic the game server sends to your PC. It does not read or change the game's memory, injects nothing and sends nothing to the game.

**Why does it ask for administrator rights?** To capture the game's network traffic, through Npcap or raw sockets.

**Which Windows?** Windows 10 and 11, one exe, no installer.

**Which languages?** 15, including English, Russian, Korean, Japanese and Chinese.

<p align="center"><img src="media/pvp.webp" alt="PvP: one card per opponent with your encounters, key moments and the damage both ways" width="100%" /></p>

---

## Русский

### Angel — DPS-метр и оверлей для AION 2 (Айон 2)

**Angel — бесплатный DPS-метр (счётчик урона, дамаг-метр) и оверлей для AION 2.** Он показывает урон вашей группы в AION 2 прямо во время боя: в своём окне и в маленьком оверлее поверх игры, который не забирает у неё фокус. Один файл, без установки, Windows 10 и 11.

### Что умеет

- **Метр.** Урон, DPS, лечение и доля каждого игрока, по секундам и по умениям. Бои с боссами сохраняются, с лучшим временем на каждом боссе подземелья.
- **Оверлей.** Поверх игры и не мешает: полоски группы в бою, души пета во время фарма, противник и шанс на победу в PvP. Если закрепить, клики проходят в игру.
- **PvP.** Каждый бой, который закончился смертью, сохраняется: как он шёл, размен за разменом, и ключевые моменты.
- **События, петы и кубы.** Таймеры событий, коллекция петов с местами, где падают души, и радар скрытых кубов.
- **Профили.** Снаряжение, умения и боевая сила игрока с официального сайта — в один клик.
- **15 языков**, включая русский.

### Установка

Скачать: [**Angel.exe**](https://github.com/nokttsu/angel-releases/releases/latest/download/Angel.exe) · [все релизы](https://github.com/nokttsu/angel-releases/releases) · [сайт](https://nokttsu.github.io/angel/)

1. Скачайте [**Angel.exe**](https://github.com/nokttsu/angel-releases/releases/latest/download/Angel.exe) из последнего релиза.
2. Запустите. Windows попросит права администратора: Angel читает сетевой трафик игры.
3. Если Npcap не установлен, Angel предложит его поставить (установщик встроен). Запускайте Angel до входа в игру.

Если Windows SmartScreen остановит запуск, нажмите **Подробнее → Выполнить в любом случае**: exe не подписан сертификатом.

### Обновления

Angel проверяет последний релиз на этой странице при запуске и раз в несколько часов, а новую версию ставит, только когда вы скажете (Настройки → Обновления). Каждый exe здесь подписан: перед заменой Angel сверяет SHA-256 и подпись Ed25519 со встроенным ключом и отказывается от всего остального. Что изменилось — на [странице релизов](https://github.com/nokttsu/angel-releases/releases) и в самом Angel после обновления.

### Как это работает

Angel только читает трафик, который сервер игры присылает на ваш компьютер, как это делает захват пакетов. Он не читает и не меняет память игры, ничего не внедряет и ничего не отправляет в игру. Профили берутся с официального сайта AION 2; о вас никуда ничего не отправляется.

### Частые вопросы

**Что такое Angel?** DPS-метр для AION 2: счётчик урона, журнал боёв с боссами и PvP и оверлей поверх игры.

**Трогает ли Angel игру?** Нет. Он только читает сетевой трафик, который сервер игры присылает на ваш компьютер: не читает и не меняет память игры, ничего не внедряет и ничего не отправляет в игру.

**Зачем права администратора?** Чтобы захватывать сетевой трафик игры через Npcap или raw-сокеты.

**Какая Windows нужна?** Windows 10 и 11, один exe без установки.

---

## 한국어

### Angel — 아이온2 딜미터 · 오버레이

Angel은 아이온2(AION 2)용 무료 DPS 미터(딜미터)이자 게임 위 오버레이입니다. 전투 중 파티원 모두의 피해량, DPS, 치유량과 비율을 초 단위·스킬별로 보여 주고, 보스전과 PvP 전투 기록을 남깁니다. Windows 10·11, 설치 없이 exe 하나로 실행됩니다.

- **다운로드:** [**Angel.exe**](https://github.com/nokttsu/angel-releases/releases/latest/download/Angel.exe) (최신 릴리스). 실행하면 관리자 권한을 요청합니다: 게임의 네트워크 트래픽을 읽기 위해서입니다.
- **작동 방식:** 게임 서버가 PC로 보내는 트래픽만 읽습니다. 게임 메모리를 읽거나 바꾸지 않고, 아무것도 주입하거나 게임에 보내지 않습니다.
- **언어:** 한국어를 포함한 15개 언어.
