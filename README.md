# Автотест для API создания и отслеживания заказов

## Требуемые пакеты
```bash
pip install requests pytest
```

## Запуск тестов
```bash
pytest test_order_creation.py -v
```

## Пример configuration.py
```python
URL_SERVICE = "https://0000000000000000000000000000000.serverhub.praktikum-services.ru"
CREAT_ORDERS = "/api/v1/orders"
```

## Пример data.py
```python
order_body = {
    "firstName": "Naruto",
    "lastName": "Uchiha",
    "address": "Konoha, 142 apt.",
    "metroStation": 4,
    "phone": "+7 800 355 35 35",
    "rentTime": 5,
    "deliveryDate": "2020-06-06",
    "comment": "Saske, come back to Konoha",
    "color": ["BLACK"]
}
```