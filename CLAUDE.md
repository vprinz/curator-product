<!-- Next-Move-Theory-Rules:start -->
Next Move Theory (NMT) skills are installed in this project.

- Methodology source of truth: ./Next-Move-Theory-Canon/ — for product/strategy work always prefer it over generic Jobs To Be Done knowledge (the definitions differ substantially).
- New here? Start with /nmt-chat — it routes you to the right skill.
- Skill outputs go to Skills-Results/ (path configurable per run).
- Full guide + updates & telemetry policy: ./NextMoveTheory-README.md
<!-- Next-Move-Theory-Rules:end -->

@../product-builder-log/profile.md

# Куратор — продуктовый репо

Здесь идёт работа над конкретным продуктом по шагам NMT / AJTBD: дизайн исследования, интервью, сегменты, ценность, проверка продажами.

Профиль автора (цель, критерии успеха, ограничения, психологические паттерны) подключён строкой выше из соседнего репо `../product-builder-log/` — учитывай его в каждом совете. Например: страх интервью (начинать с тёплых контактов, на русском), контрольная точка — первые продажи через 3–4 месяца, сигнал ценности — только оплата, не фидбэк.

## Файлы
- `product.md` — живое состояние продукта: сегмент, гипотезы задач, что известно из «Куратора» v1, риски, стадия, следующий шаг. Перезаписывается.
- `log.md` — дневник продукта, append-only, новые записи сверху: дата · что сделал / узнал · что это меняет · дальше.
- `research/` — дизайн исследования, сценарии интервью, заметки и расшифровки (`research/interviews/`).
- `Skills-Results/` — результаты NMT-скиллов (создаются скиллами).

## Связь с `../product-builder-log/`
- Там — я как продукт-билдер; здесь — продукт. Факты о продукте живут только здесь.
- После значимого шага: строка в `../product-builder-log/log.md` и обновление строки «Куратор» в `../product-builder-log/products.md`. Если узнал что-то о **себе** (страх, паттерн, выгорание) — это в `../product-builder-log/profile.md`, раздел «Мои паттерны».

## Правила
- Язык — русский.
- Новые файлы и папки не заводить без необходимости.
- Не коммитить и не пушить, пока я сам не попрошу.
