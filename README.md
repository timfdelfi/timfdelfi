<h1 align="left">Привет, я Тимофей 👋</h1>

<p align="left">
  Разрабатываю системный софт и сетевые инструменты под <b>Linux</b> и роутеры (<b>OpenWrt</b>).<br/>
  Люблю, когда всё работает быстро, без лишних зависимостей и стабильно на слабом железе.
</p>

<p align="left">
  <a href="https://t.me/timfiiiii"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"/></a>
  <a href="mailto:timfiiiii7535@gmail.com"><img src="https://img.shields.io/badge/Email-timfiiiii7535%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Шерегеш%2C%20Россия-6c5ce7?style=flat-square" alt="Location"/>
</p>

---

### 🛠 Чем занимаюсь

- **Сетевой стек Linux:** Policy Routing (`ip rule`, маршрутизация по таблицам), `nftables`, TUN-интерфейсы, селективный роутинг и обход DPI/блокировок.
- **OpenWrt & Embedded:** разработка LuCI JS-интерфейсов, системные демоны (`procd`, `ubus`), скрипты на POSIX `sh` / BusyBox `ash`, обработка данных на чистом `jq` без внешних рантаймов.
- **Надёжность и CI/CD:** автоматическое тестирование (`shellcheck`, `sh -n`, валидация конфигов) и e2e UI-тестирование на Playwright.

---

### 🚀 Проект: [luci-vless-selective](https://github.com/timfdelfi/luci-vless-selective)

VPN-клиент для OpenWrt (LuCI + sing-box + zapret) по принципу **«вставил ссылку → нажал кнопку → работает»**.

- **Zero-dependency бэкенд:** модульный код на чистом `sh` и `jq` без внешних библиотек и регулярок (заводится на любом роутере с урезанным BusyBox).
- **Умная маршрутизация:** выборочный обход по доменам через `dnsmasq-full` + `nftset`, автовыбор быстрого сервера и изоляция собственных сетевых правил.
- **Discord через zapret:** обход блокировок через `nfqws` с автоподбором рабочих стратегий и бесшовным переключением на VPN при сбое.
- **Интерфейс:** современный LuCI JS View с живым спидометром скорости, сессионным счётчиком трафика и тёмной темой.
- **Инженерия:** чистый shellcheck, синтаксические тесты и UI-тесты на Playwright в headless Chromium.

---

### 💻 Стек

<p align="left">
  <img src="https://skillicons.dev/icons?i=linux,bash,js,git,githubactions&theme=dark" alt="Стек" />
</p>
