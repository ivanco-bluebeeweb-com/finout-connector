# Finout Connector — Connector Discovery

**Vendor API Baseline:** https://finout.io

## Архитектура API
- **Базовый адрес:** `https://api.finout.io/v1`
- **Протокол:** REST / HTTPS (JSON)
- **Аутентификация:** API Key (Authorization: Bearer <token>)
- **Ключевые эндпоинты:**
  - виртуальные теги (/megabills)
  - статьи затрат (/costs)
  - аномалии (/anomalies)
  - KPI стоимости единицы юнита
- **Тестовая точка проверки подключения:** `GET /v1/reports`.
