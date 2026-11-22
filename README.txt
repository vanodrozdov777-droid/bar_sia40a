BAR DESK — чистая установка

1. На github.com создайте НОВЫЙ репозиторий (New repository), любое имя, Public, без галочек про README.
2. Нажмите "uploading an existing file".
3. Распакуйте ZIP. Выделите ВСЕ файлы внутри папки (Ctrl+A) и перетащите в окно GitHub.
   Папка .github тоже должна быть среди перетаскиваемых. Папка app НЕ нужна — её создаст сборка.
4. Commit changes.
5. Вкладка Actions -> Build BAR DESK APK -> дождитесь зелёной галочки (5-10 минут).
6. Откройте запуск, внизу в Artifacts скачайте BAR-DESK-APK. Внутри ZIP — app-debug.apk.
7. Перенесите APK на телефон и установите (разрешите установку из неизвестных источников).

Без APK: Settings -> Pages -> Source: Deploy from a branch -> main / root. Приложение откроется по ссылке сайта.
