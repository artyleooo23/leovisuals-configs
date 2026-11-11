# LeoVisuals configs

Каталог конфигов для мода LeoVisuals (вкладка CFG HUB -> Каталог).

## Как добавить конфиг
1. Положи файл конфига в папку `configs/` (например `configs/pvp-red.json`).
2. Добавь запись в `index.json`:

```json
[
  { "name": "PvP красный", "author": "ник", "file": "pvp-red.json", "desc": "Короткое описание" }
]
```

Файл конфига — это JSON, который мод сохраняет в `.minecraft/config/leovisuals-configs/`.
Заявки от игроков приходят в Issues с кодом конфига (LEO1:...).
