# Капитан: Дело о пропавшем чемодане — Art Pack v0.2

Готовая интеграция внешних графических файлов в существующий браузерный квест.

## Содержание
- `assets/backgrounds/`: 10 сцен в SVG и оптимизированных WebP (1000×620)
- `assets/characters/`: 5 прозрачных персонажей SVG и PNG 512 px
- `assets/items/`: 11 предметов инвентаря и квеста, SVG и PNG 256 px
- `assets/ui/`: 3 UI-эффекта SVG и PNG
- `assets/references/`: исходные фотографии Капитана и Бубы для будущего арт-производства

Игра запускается через `index.html`. Существующее сохранение `captain-japan-quest-v1` не сбрасывается.

**Важно:** этот пакет — стилизованный SVG-арт и первый интегрированный графический проход; он не является полностью покадрово анимированным профессиональным арт-паком. Для финального релиза потребуется отдельная отрисовка высокодетализированных сцен, эмоций, покадровых анимаций и проверка интерфейса на разных устройствах.


## v0.3 clay integration
- Characters switched to PNG clay renders.
- Key backgrounds replaced with clay-style scenes (hotel, port/pawn, market, lighthouse/booba/ending).
- Inventory items sneakers, jelly, note, mango, suitcase re-sliced from a shared props sheet.
- Added sprite containers for NPC and Buba in `index.html`.
- Added atlases in `assets/sheets/`.
