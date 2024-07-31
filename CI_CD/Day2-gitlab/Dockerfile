# Используйте базовый образ
FROM python:3.9

# Установите зависимости
COPY requirements.txt .
RUN pip install -r requirements.txt

# Скопируйте исходный код
COPY . .

# Запустите приложение
CMD ["python", "app.py"]
