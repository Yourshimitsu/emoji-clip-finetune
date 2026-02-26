# emoji-clip-finetune
В работе использовалась предобученная модель CLIP (ViT-B-32, OpenAI), которая была дообучена на датасете с [Kaggle](https://www.kaggle.com/datasets/shuvokumarbasak4004/emojis-list-unicode-image-dataset).


- Есть 256x256 пикселей png картинка эмодзи
- В качестве текста используется его имя (например `:smiling_face:`)

После обучения модель протестирована на 5 рукописных изображениях эмодзи.
