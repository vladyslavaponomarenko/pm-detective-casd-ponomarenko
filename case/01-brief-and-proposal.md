# Запит клієнта, наша пропозиція, рішення клієнта

## 1. Запит клієнта (30.08.2021, email від Jina Park, art producer, CookApps)

> Hi RSG team,
>
> We'd like to prepare a Halloween event version of our existing **Mansion Garden** location. The idea is a festive but not childish look: pumpkins, spider webs, lanterns, a slightly spooky mood. Our reference is the Halloween decoration in Lily's Garden.
>
> What we need: **a reskin of the location you see in the attached screenshot**, same camera and canvas (**2720 × 3700 px**, plus a 1360 × 1850 version), decorated for Halloween. The existing objects must stay in their positions because the gameplay grid is already set up; decorations can be added on top and some objects can be restyled.
>
> The screenshot is attached; the scene files are too heavy for email, I'll share them separately via Drive.
>
> Timeline: we'd love to have it by **end of September** so we can ship the event mid-October.
>
> Could you send an estimate and a proposed approach?
>
> Thanks, Jina

**Вкладення:** `MansionGarden_ingame_screenshot.png` (скріншот локації з ігрового білду; прев'ю «Основа»: 00_base_client-screenshot_2021-08-30.webp), посилання на референс Lily's Garden ([artstation.com/artwork/v21PEO](https://www.artstation.com/artwork/v21PEO)). Lily's Garden — референс стилю; переходити за посиланням необов'язково.

## 2. Технічні вимоги (з брифу)
- Полотно **2720 × 3700 px** (і даунскейл 1360 × 1850).
- Об'єкти на тих самих позиціях, що в поточній локації.
- Шари: фон окремо, кожен декорований об'єкт окремо, під ігрову логіку «до/після».
- Шрифти і текст не потрібні.
- Клієнт просив «hand-painted look».

## 3. Наша пропозиція (02.09.2021, PM Артем)

Два варіанти на вибір, обидва як **рескін наявної локації**.

Клієнт обрав V2; V1 для контексту.

### V1. Декор поверх
Об'єкти локації не змінюємо, додаємо хелловінський декор (гарбузи, павутиння, ліхтарі, свічки) і перефарбовуємо освітлення.

| Стадія | Людино-дні | Бюджет ($300/день) |
|---|---|---|
| Concept 2D | 2–3 | $600–900 |
| Modeling + Texturing 3D (декор) | 9–10 | $2,700–3,000 |
| Render | 2–3 | $600–900 |
| Overpaint 2D | 6–8 | $1,800–2,400 |
| **Разом** | **19–24** | **$5,700–7,200** |

### V2. Повний редизайн
Нова альтанка, нова статуя, перестилізовані дерева і кущі, новий декор. Об'єкти залишаються на своїх місцях (під ігрову сітку), але форма і матеріали змінюються.

| Стадія | Людино-дні | Бюджет ($300/день) |
|---|---|---|
| Concept 2D | 4–6 | $1,200–1,800 |
| Modeling + Texturing 3D | 17–18 | $5,100–5,400 |
| Render | 4–5 | $1,200–1,500 |
| Overpaint 2D | 7–10 | $2,100–3,000 |
| **Разом** | **32–39** | **$9,600–11,700** |

Пайплайн обох версій: концепт у кольорі → 3D-моделінг і текстури нових та змінених об'єктів → рендер у розмірі полотна → оверпейнт по рендеру → порізка і PSD.

Умови: 2 раунди правок на весь скоуп у ціні (див. rate card). Термін при V2: 4 тижні від затвердження концепту; при старті 6 вересня орієнтир здачі **1 жовтня**.

## 4. Рішення клієнта (03.09.2021)

> Let's go with **V2**, the full redesign. Budget $9,600–11,700 (32–39 man-days, 256–312 h) is approved on our side. Please start as soon as you can, end of September is important for us.
>
> One more thing: please keep the object positions, our grid team already mapped the current layout.
