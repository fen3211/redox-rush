# Redox Rush — игра-тренажер по ионно-электронному балансу

Мини-курс в виде игры в браузере. Учишь полуреакции на практике: степени окисления → полуреакции → среда → сборка полного уравнения.

## Запуск локально
Просто открой `index.html` двойным кликом. Ничего ставить не надо.

## Хостинг через GitHub Pages (2 минуты)

1. Создай репозиторий на github.com (например `redox-rush`), **без** README.
2. В терминале в папке игры:
```bash
git init
git add .
git commit -m "redox rush game"
git branch -M main
git remote add origin https://github.com/ТВОЙ_НИК/redox-rush.git
git push -u origin main
```
3. На GitHub: `Settings → Pages → Deploy from a branch → main / root → Save`.
4. Через минуту игра будет тут: `https://ТВОЙ_НИК.github.io/redox-rush/`

Файл один (`index.html`), поэтому Pages заведется без танцев.
