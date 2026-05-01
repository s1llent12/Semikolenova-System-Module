# Semicolenova System Module

## Назначение модуля
Модуль безопасности и управления доступом (Security & Governance). Обеспечивает авторизацию пользователей, контроль доступа на основе ролей (RBAC), аудит действий и защиту от атак на ИИ (Prompt Injection).

## Используемый стек
- Python 3.10+
- FastAPI
- PostgreSQL (RLS)
- AI Gateway
- JWT для аутентификации

## Компоненты модуля
1. Авторизация и управление ролями
2. Row-Level Security (RLS)
3. Аудит действий пользователей
4. Защита от Prompt Injection (LLM Firewall)
5. PII Masking (обезличивание данных)

## Интеграция со смежными модулями
- Передача UUID в 1С (Little-Endian)
- Приём векторизованных запросов от Semantic Layer
- Логирование в общей системе
