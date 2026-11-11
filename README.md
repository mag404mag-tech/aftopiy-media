# aftopiy-media

Публичные страницы превью для постов Telegram-канала «Афтопий» (GitHub Pages).

- `posts/<хеш текста>-<хеш картинки>/index.html` — страница с og:image для превью ссылки в Telegram;
- `media/reviewed-<хеш>.png` — иллюстрация с логотипом.

Файлы генерируются из репозитория `medbot` (`content/editorial-batch-*/export_previews.py`). Бот перед отправкой сверяет страницу и SHA-256 картинки с реестром `deploy/nas/assets/post-preview-registry.json`, поэтому файлы нельзя менять вручную.
