# Tsukiko Desktop — плагины

Каталог плагинов для Tsukiko Desktop. Клиент читает `plugins.json` и показывает эти плагины в разделе «Плагины → Каталог плагинов».

## Подключить в клиенте

Плагины → Каталог плагинов → «Источник» → вставьте ссылку:

```
https://raw.githubusercontent.com/L1sovskyy/tsukikodesktop-plugins/main/plugins.json
```

## Плагины

| Плагин | Версия | Автор |
|---|---|---|
| Custom Profile Desktop | 1.0 | @tsukikogram |
| NavDrawerBackground Desktop | 1.0 | @tsukikogram, идея @ka1Plugins |
| Profile Wallpaper Desktop | 1.0.1 | @tsukikogram, идея @JIl06uTeJIb_K0TuKoB |
| Femboy Music Stats Desktop | 2.6.1-desktop | @PA3MA3AH |
| Playlist to Profile Desktop | 1.1-desktop | @rei_plugins (@optimist_opti) |
| RolePlay Commands Desktop | 1.4-desktop | @windukk and @shakyyra |
| Мут в ЛС Desktop | 1.2-desktop | @shit_plugins |
| WS-Bypass Desktop | 3.1.10-desktop | @Th3Nek1t_projects |
| Калькулятор | 1.2 | @test |
| Тихая отправка | 1.0 | @tsukikogram |
| Демо Android-API | 1.0 | @tsukikogram |

Версии с пометкой `-desktop` — переработки плагинов для Android под Tsukiko Desktop. Права на оригинальные плагины принадлежат их авторам.

## Как добавить или обновить плагин

1. Положите файл в `plugins/`.
2. Добавьте или обновите запись в `plugins.json` (`id`, `name`, `version`, `url` на raw-файл).
3. Поднимите `version`: клиенты с включённым автообновлением подтянут новую версию сами. Если новой версии нужны дополнительные разрешения, клиент попросит подтверждение.
