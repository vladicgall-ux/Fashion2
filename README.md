# Fashion Стилист — сайт курса STYLE ON

## Структура
- `index.html` — вся страница (текст + вёрстка)
- `images/` — 12 фотографий, оптимизированы под веб
- `robots.txt`, `sitemap.xml` — для поисковиков

## Деплой на GitHub Pages

1. Создать репозиторий на github.com → New repository → имя `fashion` → Create repository
2. В терминале, в папке с этими файлами:

```bash
git init
git add .
git commit -m "Fashion Стилист — сайт курса"
git branch -M main
git remote add origin https://github.com/ВАШ_ЛОГИН/fashion.git
git push -u origin main
```

3. На GitHub: репозиторий → Settings → Pages → Source → выбрать ветку `main`, папку `/ (root)` → Save
4. Через 1–2 минуты сайт будет доступен по адресу:
   `https://ВАШ_ЛОГИН.github.io/fashion/`

## Свой домен вместо github.io (опционально)
Если захотите подключить `включистиль.рф` или другой домен к этому репозиторию:
1. Settings → Pages → Custom domain → ввести домен
2. У регистратора домена добавить CNAME-запись на `ВАШ_ЛОГИН.github.io`
