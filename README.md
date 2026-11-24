# Umbra

**English** · [Русский](#русский)

Umbra is a simple VPN client for Windows built on [Xray-core](https://github.com/XTLS/Xray-core). It supports VLESS (including Reality), VMess, Trojan and Shadowsocks links, subscriptions and QR codes.

## Download

Get the latest archive from [Releases](../../releases/latest), unzip it anywhere and run `Umbra.exe`. No installation needed.

- Windows 10/11, 64-bit.
- On first launch Umbra opens in simple mode: one connect button and a server list. Switch to advanced mode with the button at the bottom of the window or `Ctrl+M`.
- TUN mode (all system traffic) requires running as administrator; Umbra will offer to restart with admin rights.

## Updates

Umbra checks this repository once a day and shows a link at the bottom of the window when a new version is out. To update, download the new archive and replace `Umbra.exe`. Your servers and settings live in the `data` folder next to it and are kept.

> Do not share your `data` folder: it contains your server keys.

## License

Xray-core is distributed under its own license (MPL-2.0); license files are in the `core` folder.

---

## Русский

Umbra — простой VPN-клиент для Windows на ядре [Xray-core](https://github.com/XTLS/Xray-core). Понимает ссылки VLESS (в том числе Reality), VMess, Trojan и Shadowsocks, подписки и QR-коды.

## Скачать

Скачайте архив последней версии в разделе [Releases](../../releases/latest), распакуйте в любую папку и запустите `Umbra.exe`. Установка не нужна.

- Windows 10/11, 64 бита.
- При первом запуске включён простой режим: одна кнопка подключения и список серверов. В расширенный режим можно перейти кнопкой внизу окна или сочетанием `Ctrl+M`.
- Для режима TUN (весь трафик системы) нужны права администратора — Umbra сама предложит перезапуститься с ними.

## Обновления

Раз в сутки Umbra проверяет этот репозиторий и, если вышла новая версия, показывает ссылку внизу окна. Чтобы обновиться, скачайте новый архив и замените `Umbra.exe`. Серверы и настройки лежат в папке `data` рядом с программой и сохраняются.

> Не передавайте никому папку `data`: в ней ключи ваших серверов.

## Лицензия

Xray-core распространяется по своей лицензии (MPL-2.0); файлы лицензий лежат в папке `core`.
