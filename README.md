# Theme Switcher

Анимированный переключатель светлой и темной темы на чистом HTML/CSS/JS.

## Демо

Проект опубликован на GitHub Pages:  
`https://zaikopewpew.github.io/light-dark-switcher/`

## Что внутри

- плавная анимация переключения между светлой и темной темой;
- звуковой клик при переключении;
- управление с клавиатуры:
  - `ArrowRight` — темная тема;
  - `ArrowLeft` — светлая тема;
- виброотклик в мобильной версии (`navigator.vibrate`);
- декоративные SVG-слои (лучи, облака, звезды, солнце/луна).

## Структура проекта

- `index.html` — разметка, стили и клиентская логика;
- `beam/` — SVG лучи;
- `clouds/` — SVG облака;
- `Sun.svg`, `Moon.svg`, `Star.svg`, `star_group.svg` — графические ассеты;
- `audio.wav` — звук клика;
- `.github/workflows/pages.yml` — автодеплой на GitHub Pages.

## Локальный запуск

Открой `index.html` в браузере  
или подними локальный сервер:

```bash
python3 -m http.server 8080
```

После этого открой:

`http://localhost:8080/`

## Деплой

Деплой настроен через GitHub Actions workflow для GitHub Pages.  
При пуше в `main` сайт автоматически публикуется.
