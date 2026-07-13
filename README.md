# alignment-olympiad

Colab-ноутбук для ML Olympiad Red Task: выравнивание Qwen3-4B-Instruct через SFT, DPO, Reward Model и SimPO.

## Запуск

1. Загрузите папку `ml-olympiad-red-task/` в Google Drive.
2. Откройте `alignment_notebook.ipynb` в Colab с GPU T4.
3. Запустите все ячейки по порядку.

## Задачи

| # | Метод | Данные | Метрика |
|---|-------|--------|---------|
| 1 | SFT | kid_adult | P_simple |
| 2 | DPO style | kid_adult | P_simple |
| 3 | Reward Model | good_bad | accuracy |
| 4 | DPO quality | good_bad | gold_rm score |
| 5 | SimPO | good_bad | gold_rm score |
