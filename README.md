# RankApart-3days

Скан позиций объектов на Booking.com на 3 ночи. Результаты пишутся в лист "Rank AP3d".

## Запуск

```
pip install -r requirements.txt
python -m playwright install chromium
python RankAp3d_3nights.py
```

- `GOOGLE_CREDS` — JSON сервисного аккаунта в переменной окружения (или файл `silken-glyph-443313-i4-cdf14b36288a.json` рядом со скриптом, на уровень выше).
- `HEADLESS=1` — запуск без окна браузера.
