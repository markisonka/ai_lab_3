# ai_lab_3
# Генеративные текстовые нейросети

## Задание

Необходимо натренировать и сравнить качество нескольких генеративных текстовых моделей на одном из заданных текстовых датасетов.

Необходимо исследовать следующие нейросетевые архитектуры:

1. Simple RNN с посимвольной и по-словной токенизацией
1. Однонаправленная однослойная и многослойная LSTM c посимвольной токенизацией и токенизацией по словам и [на основе BPE](https://keras.io/api/keras_nlp/tokenizers/byte_pair_tokenizer/)
1. Двунаправленная LSTM
1. (На хорошую оценку) трансформерная архитектура (GPT) "с нуля" [[пример](https://keras.io/examples/generative/text_generation_gpt/)] 
1. (На отличную оценку) до-обучение предобученной GPT-сети [[пример 1](https://github.com/ZotovaElena/RuGPT3_finetuning)]

## Датасеты

Рекомендуется использовать один из следующих датасетов, распределив их таким образом, чтобы все команды в группе использовали разные датасеты:

1. Текст книги [Гарри Поттер и методы рационального мышления](https://hpmor.ru/)
## Отчет

Отчет приведите в файле [Report.md](Report.md). Также приложите к репозиторию набор Jupyter-ноутбуков, демонстрирующих процесс обучения моделей и результаты текстовой генерации.
