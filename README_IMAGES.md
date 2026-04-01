# 📁 Инструкция по файлам изображений — Skills4Cause Landing

## ✅ Файлы, которые у тебя уже ЕСТЬ (не переименовывать):

| Файл в папке | Используется как |
|---|---|
| `logo.png` | Логотип в хедере |
| `logo-2.png` | Логотип в футере |
| `Group 14.png` | Иллюстрация "Fundraising" в hero |
| `Icon1.png` | Иконка "Donor Fatigue" |
| `Icon2.png` | Иконка "Fundraiser Burnout" |
| `Icon3.png` | Иконка "Loss of Momentum" |
| `Vector 11.png` | Стрелка в "How It Works" шаг 1 |
| `Vector 12.png` | Стрелка в "How It Works" шаг 2 |
| `Gemini_Generated_Image_5g3x85g3x85g3x85 1 [Vectorized].png` | Пазл-иллюстрация в секции "Any Cause. Any Skill." |

> ⚠️ GitHub Pages чувствителен к регистру. Имена — точно как выше.

---

## ⚠️ Файлы, которые НУЖНО добавить из Figma-экспорта:

| Нужное имя | Что это |
|---|---|
| `5.png` | Декоративный элемент hero (внизу справа) |
| `6.png` | Декоративный элемент hero (внизу слева) |
| `1.svg` — `10.svg` | SVG-части иллюстрации hero (персонажи) |

> 💡 Эти файлы — части сборной hero-иллюстрации из Figma.
> Без них десктоп всё равно откроется, просто без декоративных деталей вокруг "Fundraising"-таблички.

---

## 📂 Итоговая структура на GitHub:

```
📁 репозиторий/
├── index.html
└── img/
    ├── logo.png
    ├── logo-2.png
    ├── Group 14.png
    ├── Icon1.png
    ├── Icon2.png
    ├── Icon3.png
    ├── Vector 11.png
    ├── Vector 12.png
    ├── Gemini_Generated_Image_5g3x85g3x85g3x85 1 [Vectorized].png
    ├── 5.png
    ├── 6.png
    ├── 1.svg, 3.svg, 4.svg, 5.svg, 6.svg, 7.svg, 8.svg, 9.svg, 10.svg
```

## 🔧 Что сделано в index.html:
1. ✅ Десктоп (1920px) масштабируется под любой экран
2. ✅ Мобильная версия при ширине ≤ 900px
3. ✅ Пробелы и скобки в именах файлов URL-закодированы
4. ✅ Все секции: Hero, Problem, How It Works, Brand, Statement, CTA, Footer
