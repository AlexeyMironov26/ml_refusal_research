this is readme file for task of researching and controlling the phenomenon of refusal of models

# Refusal Direction Research (Qwen2.5-1.5B-Instruct)

Этот репозиторий содержит реализацию тестового задания по исследованию и контролю способности отказа на запросы llm: 
исследование refusal direction, аблитерация и activation steering.

## Структура репозитория

- `artifacts/` — все сохранённые данные, активации и результаты экспериментов
- `test_refusal_ml_v1` — ноутбук 


## Воспроизводимость

- Seed: 42
- Модель: Qwen/Qwen2.5-1.5B-Instruct
- Данные: AdvBench (harmful) + Alpaca (harmless) + Wikitext (нейтральный корпус)
- Сплиты: Train=300, Val=70, Held-out=150

## Как запустить

1. Открыть Kaggle Notebook с GPU T4.
2. Импортировать `test_refusal_ml_v1.ipynb` и запустить.


## Лицензия
Используется только в образовательных целях.