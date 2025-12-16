# Homework: Audio Classification

## Задание

Необходимо заполнить пропущенные части в ноутбуке `audio_classification.ipynb` (места, где стоит `...`).

## Что нужно реализовать

1. **Архитектура модели `AudioCNN`** (Cell 9):
   - Реализовать CNN модель для классификации mel-spectrogram
   - Модель должна принимать на вход mel-spectrogram размером `[batch, n_mels, time_frames]` (128, 32)
   - Выход: логиты для 35 классов

2. **Методы `training_step` и `validation_step`** в классе `AudioClassificationModule` (Cell 13):
   - Реализовать шаг обучения с вычислением loss и метрик

## Требования

- **Accuracy > 90%** на валидационной выборке
