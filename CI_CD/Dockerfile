# Dockerfile
# Используем официальный образ Python
FROM python:3.9-slim

# Устанавливаем рабочую директорию в контейнере
WORKDIR /app

# Копируем файл server.py в контейнер
COPY server.py .

# Указываем команду запуска сервера
CMD ["python", "server.py"]

# Открываем порт 8000 для доступа к серверу
EXPOSE 8000
