# adv_yandex_xyin9
Карта-приключение для Counter-Strike 1.6: испытания, паркур, головоломки и секретные комнаты.
**Автор: okay_google. Соавтор: Codex (ИИ-помощник OpenAI).**

## Перед установкой
**AMX Mod X 1.9 должен быть уже скачан, установлен в вашу CS 1.6 и работать. В архив карты AMX Mod X не входит. Просто скачать его недостаточно — сначала завершите его установку.**

## Скачать и играть
[Скачать готовый ZIP последней версии](https://github.com/okaygoogle101/adv_yandex_xyin9/releases/latest/download/adv_yandex_xyin9.zip)

**Не скачивайте автоматически созданный GitHub архив Source code для установки игры.** В Assets релиза выберите `adv_yandex_xyin9.zip`.

1. [Установка для новичков](INSTALL_RU.md).
2. [Если что-то не работает](TROUBLESHOOTING_RU.md).
3. [Обновление карты](UPDATE_RU.md).
4. [Описание плагина](PLUGIN_RU.md).

Текущая версия комплекта: **v1.0.0**. Внутренняя версия плагина: **3.45.2**.
[Исходники именно v1.0.0](https://github.com/okaygoogle101/adv_yandex_xyin9-source/tree/v1.0.0) · [Релиз исходников v1.0.0](https://github.com/okaygoogle101/adv_yandex_xyin9-source/releases/tag/v1.0.0).

Готовые файлы находятся в `cstrike/`. Имена карты и ресурсов при обновлениях сохраняются.
[История изменений](CHANGELOG.md) · [Как готовятся новые версии](RELEASING.md).

## Какой файл куда копировать
Все пути справа начинаются от папки вашей игры `cstrike`.

| Из папки `cstrike` в архиве | Куда в игре |
|---|---|
| `maps/adv_yandex_xyin9.bsp` | `cstrike/maps/adv_yandex_xyin9.bsp` |
| `maps/adv_yandex_xyin9.res` | `cstrike/maps/adv_yandex_xyin9.res` |
| `yx_xyin9.wad` | `cstrike/yx_xyin9.wad` — прямо в корень cstrike |
| `addons/amxmodx/plugins/yx_xyin9.amxx` | `cstrike/addons/amxmodx/plugins/yx_xyin9.amxx` |
| Папка `models/yx_xyin9` целиком | `cstrike/models/yx_xyin9` |
| Папка `sprites/yx_xyin9` целиком | `cstrike/sprites/yx_xyin9` |
| Папка `sound/yx_xyin9` целиком, со всеми вложенными папками | `cstrike/sound/yx_xyin9` |
| Все шесть файлов `gfx/env/yx_xyin9*.tga` | `cstrike/gfx/env/` |

Проще всего скопировать **всё содержимое cstrike из архива в cstrike игры** с объединением папок. Не создавайте `cstrike/cstrike` и не переносите файлы моделей/звуков из их подпапок.

Затем в `cstrike/addons/amxmodx/configs/plugins.ini` добавьте отдельную строку `yx_xyin9.amxx` и перезапустите игру. Полные шаги — в [инструкции](INSTALL_RU.md).
