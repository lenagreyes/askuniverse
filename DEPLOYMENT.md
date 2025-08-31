# 🚀 Развертывание на GitHub Pages

## Быстрый старт

1. **Создайте новый репозиторий на GitHub**
   - Назовите его, например, `mystery-app`

2. **Загрузите файлы в репозиторий**
   ```bash
   git init
   git add index.html static/ README.md .gitignore
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/ваше-имя-пользователя/mystery-app.git
   git push -u origin main
   ```

3. **Настройте GitHub Pages**
   - Перейдите в Settings → Pages
   - Source: Deploy from a branch
   - Branch: main, Folder: / (root)
   - Save

4. **Ваш сайт будет доступен по адресу:**
   `https://ваше-имя-пользователя.github.io/mystery-app`

## Структура файлов для GitHub Pages

```
mystery-app/
├── index.html          # Главная страница
├── static/
│   └── Letmeshowyou_font.otf  # Шрифт
├── README.md           # Описание проекта
├── DEPLOYMENT.md       # Эта инструкция
└── .gitignore          # Исключения для Git
```

## Проверка

После развертывания:
1. Откройте ваш сайт в браузере
2. Нажмите кнопку "Нашаманить"
3. Убедитесь, что ответы загружаются корректно

## Устранение неполадок

- **Шрифт не загружается**: Проверьте, что файл `static/Letmeshowyou_font.otf` загружен в репозиторий
- **API не работает**: Убедитесь, что сайт открывается по HTTPS (GitHub Pages автоматически использует HTTPS)
- **Страница не отображается**: Проверьте, что `index.html` находится в корне репозитория
