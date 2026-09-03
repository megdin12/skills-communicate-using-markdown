# Ежедневное обучение
## Утреннее планирование
[ ] - Ознакомьтесь с [блогом GitHub](https://github.blog/) для идей по темам.
- [ ] Узнайте больше о [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Превратите мой первый пост в блоге в настоящую веб-страницу.
## Обзор
Преобразуйте изображение или видео из темного режима в светлый с помощью [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hut=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
