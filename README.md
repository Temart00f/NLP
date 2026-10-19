# Лабораторные работы по NLP

Курс «Обработка естественного языка», ПМиФИ ОмГТУ.

| Лабораторная | Папка | Тема |
|---|---|---|
| 1 | [`lab1_torch_w2v/`](lab1_torch_w2v/) | [Полносвязные нейросети в PyTorch, контекстные эмбеддинги, Word2Vec (CBoW, SkipGram)](https://wiki.pmifi.ru/ru/disciplines/nlp/laboratory-works/torch-w2v) |
| 2 | [`lab2_rnn/`](lab2_rnn/) | [Классификация текстов с применением RNN, LSTM, GRU](https://wiki.pmifi.ru/ru/disciplines/nlp/laboratory-works/rnn) |
| 3 | [`lab3_gpt/`](lab3_gpt/) | [Архитектура Transformer, обучение генеративного трансформера (GPT)](https://wiki.pmifi.ru/ru/disciplines/nlp/laboratory-works/gpt) |

## Структура

```
data/raw/          исходные датасеты (не в git, ссылки в data/README.md)
labN_*/            ноутбуки лабораторной; цифра в начале имени — порядок запуска
labN_*/data/       обработанные данные лабораторной
labN_*/outputs/    результаты: файлы для Projector, эмбеддинги, веса моделей
```

## Запуск

```bash
python3 -m venv .venv
.venv/bin/pip install -r requirements.txt
```

1. Скачать датасеты в `data/raw/` (см. [data/README.md](data/README.md)).
2. Открыть ноутбук, выбрать ядро `.venv` и запустить ноутбуки лабораторной по порядку номеров. Ноутбуки запускаются из своей папки: пути к данным в них относительные.
