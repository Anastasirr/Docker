# Запуск проекта 

"""
docker run -d -p 8000:8000 --name running-stockproducts stockproducts:tag
"""

# Сборка образа

"""
docker build . --tag=stockproducts:tag
"""

# Запустить миграции 

"""
RUN python manage.py migrate
"""