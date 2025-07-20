# FireFunTime - Огненный смерч для PocketMine-MP

[![PMMP Version](https://img.shields.io/badge/PocketMine-5.0.0+-blue.svg)](https://pmmp.io)
[![NG Support](https://img.shields.io/badge/NetherGamesMC-1.20--1.21.93-green.svg)](https://nethergamesmc.com)

Плагин добавляет функционал "Огненного смерча" аналогичный проекту FunTime для PocketMine-MP 5.0.0+ и совместимых форков.

## Установка
1. Скачайте `Fire.phar`
2. Поместите в папку `plugins/`
3. Перезапустите сервер

*Для DevTools:*
1. Поместите `Fire.zip` в `plugins/`
2. Разархивируйте
3. Перезагрузите сервер

## Использование
Основные команды:
/cubefire
/cfire

Настройки в `config.yml`:
```yaml
item_name: "§r§6(✦) Огненный смерч"
item_lore:
  - "§7Поджигает всех в радиусе 15 блоков"
```
Для разработчиков, чтобы добавить предмет в ваш плагин, просто проверяйте ByteTag:
```php
$item->getNamedTag()->getTag("CubeFire");
```
