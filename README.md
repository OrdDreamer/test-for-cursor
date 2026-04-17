# Neon Self-Presentation Landing

Невеликий статичний лендінг для самопрезентації у неоновому стилі.

## Що всередині

- `index.html` — структура сторінки (hero, про мене, навички, проєкти, контакти)
- `styles.css` — неоновий стиль та адаптивність
- `.github/workflows/deploy-pages.yml` — автодеплой у GitHub Pages

## Як кастомізувати

Відкрий `index.html` і онови за потреби:

- контактні посилання/номер
- тексти в секціях проєктів
- позиціонування під конкретну роль

## Деплой через GitHub Pages

1. Запуш зміни у `main`.
2. У репозиторії GitHub відкрий **Settings → Pages**.
3. У полі **Source** обери **GitHub Actions** (якщо ще не обрано).
4. Після виконання workflow `Deploy static site to Pages` сайт буде доступний за:

`https://<your-username>.github.io/<repo-name>/`
