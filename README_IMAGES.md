# 📁 Инструкция по файлам изображений — Skills4Cause Landing

## ✅ Файлы, которые у тебя уже ЕСТЬ (не переименовывать):

| Файл в папке | Используется как |
|---|---|
| `logo-2.png` | Логотип в хедере (тёмный, на белом фоне) |
| `logo.png` | Логотип в футере (белый/светлый, на тёмном фоне) |
| `Group 14.png` | Иллюстрация "Fundraising" в hero |
| `Icon1.png` | Иконка "Donor Fatigue" |
| `Icon2.png` | Иконка "Fundraiser Burnout" |
| `Icon3.png` | Иконка "Loss of Momentum" |
| `Vector 11.png` | Стрелка в "How It Works" шаг 1 |
| `Vector 12.png` | Стрелка в "How It Works" шаг 2 |
| `Gemini_Generated_Image_5g3x85g3x85g3x85 1 [Vectorized].png` | Пазл-иллюстрация в секции "Any Cause. Any Skill." |

> ⚠️ GitHub Pages чувствителен к регистру. Имена — точно как выше.

---

## ℹ️ SVG и декоративные файлы больше не нужны:

> ~~`5.png`, `6.png`, `1.svg`–`10.svg`~~ — hero-секция теперь использует только `Group 14.png`.

---

## 📂 Итоговая структура на GitHub:

```
📁 репозиторий/
├── index.html
└── img/
    ├── logo-2.png          ← хедер (тёмный логотип)
    ├── logo.png            ← футер (белый логотип)
    ├── Group 14.png
    ├── Icon1.png
    ├── Icon2.png
    ├── Icon3.png
    ├── Vector 11.png
    ├── Vector 12.png
    └── Gemini_Generated_Image_5g3x85g3x85g3x85 1 [Vectorized].png
```

## 🔧 Что сделано в index.html:
1. ✅ Десктоп (1920px) масштабируется под любой экран
2. ✅ Мобильная версия при ширине ≤ 900px
3. ✅ Пробелы и скобки в именах файлов URL-закодированы
4. ✅ Все секции: Hero, Problem, How It Works, Brand, Statement, CTA, Footer
5. ✅ **Логотипы исправлены:** `logo-2.png` — хедер, `logo.png` — футер (десктоп + мобайл)
6. ✅ **Hero:** одно изображение `Group 14.png`, увеличено и поднято выше
7. ✅ **Иконки в карточках:** круглый полупрозрачный фон, иконка уменьшена до нужного размера
