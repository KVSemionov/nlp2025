# Homework: Audio Classification

## Задание

Заполнил пропущенные части в ноутбуке `audio_classification.ipynb` .

## Что реализовали

1. **Архитектура модели `AudioCNN`** (Cell 9):
   - Реализовал CNN модель для классификации mel-spectrogram
   - Модель принимает на вход mel-spectrogram размером `[batch, n_mels, time_frames]` (128, 32)
   - Выход: логиты для 35 классов

2. **Методы `training_step` и `validation_step`** в классе `AudioClassificationModule` (Cell 13):
   - Реализовали шаг обучения с вычислением loss и метрик

## Требования

- **Accuracy > 90%** на валидационной выборке. У нас 92%.
