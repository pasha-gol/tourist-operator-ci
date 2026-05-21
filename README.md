# Electronic Tourist Operator System

## Варіант 18

CI/CD pipeline для електронної системи туристичного оператора.

## Мета роботи

Налаштування автоматизованої перевірки коду за допомогою GitHub Actions.

## Використані технології

- Python
- GitHub Actions
- flake8
- unittest
- GitHub Issues
- GitHub Projects

## Можливості pipeline

- автоматична перевірка стилю коду;
- запуск unit tests;
- використання GitHub Secrets;
- автоматичний запуск при Pull Request.

## Запуск тестів

```bash
python -m unittest test_tour_system.py
