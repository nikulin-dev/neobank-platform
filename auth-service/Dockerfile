# Берем легкий образ питона
FROM python:3.9-slim

# Создаем папку /app внутри контейнера
WORKDIR /app

# Копируем наш скрипт внутрь
COPY app.py .

# Запускаем скрипт
CMD ["python", "app.py"]