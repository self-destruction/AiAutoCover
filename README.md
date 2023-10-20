# ✨ AiAutoCover
Данный блокнот позволяет заменить голос в песне всего в несколько кликов. Вам понадобятся ссылка на YouTube и ссылка на модель вокала. Всё, нейро-кавер готов! Не нужно ничего устанавливать. Все вычисления происходят на серверах гугл (около 2 часов в день - бесплатно).  
Используются open-source модели и репозиторий [UVR](https://github.com/Anjok07/ultimatevocalremovergui) для отделения вокала от инструментала, [RVC](https://github.com/Mangio621/Mangio-RVC-Fork) для преобразования вокала, [SadTalker](https://github.com/OpenTalker/SadTalker) для анимирования лица (если используете [блокнот с SadTalker](https://github.com/self-destruction/AiAutoCover/blob/main/AI_Auto_Cover_SadTalker_V1.ipynb)).  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/self-destruction/AiAutoCover/blob/main/AI_Auto_Cover_V1.ipynb) - AI Auto Cover  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/self-destruction/AiAutoCover/blob/main/AI_Auto_Cover_SadTalker_V1.ipynb) - AI Auto Cover + SadTalker

## 💪 Как работает

### Установка и подготовка

Подготовка к работе включает в себя установку зависимостей (UVR + RVC), скачивание исходного аудио и модели вокала.

### Обработка аудио

Здесь происходит отделение вокала от инструментала. Далее происходит дополнительная обработка от реверберации и эха, а также, есть возможность поэкспериментировать с настройками преобразования голоса. Затем происходит преобразование вокала с использованием выбранной модели

### Пост-обработка и финальные штрихи

После преобразования вокала следует пост-обработка, которая включает в себя компрессию, нормализацию, лёгкую реверберацию и разведение по стерео-панораме. Затем вокал и инструментал смешиваются обратно, и вуаля, ваш кавер готов!

### Анимирование фотографии

Используя [блокнот с SadTalker](https://github.com/self-destruction/AiAutoCover/blob/main/AI_Auto_Cover_SadTalker_V1.ipynb) можно заставить "петь" под готовый кавер любую фотографию.

### Повторное использование

Система позволяет возвращаться к любому предыдущему шагу без необходимости запускать полный процесс заново. Например, вы можете загрузить другую модель вокала и преобразовать её, не возвращаясь к отделению вокала от инструмента.

## 📌 TODO

Вот некоторые вещи, которые я планирую добавить или улучшить:

### Прикрутить Google Drive
Сейчас каждый раз приходится скачивать репозитории и устанавливать зависимости, так что первым делом надо сделать Google Drive основным хранилищем. Это облегчит жизнь и сэкономит время.

### DeepFake в v2: клипы на новом уровне
На следующем этапе планирую прикрутить DeepFake, чтобы можно было не только делать аудио-каверы, но и менять лица в клипах. Во прикол будет!

### Интеграция с SoundCloud, Spotify, Apple Music и другими платформами
Думаю, будет удобно, если добавить возможность напрямую скачивать треки из музыкальных стриминговых сервисов, таких как SoundCloud, Spotify или Apple Music. Наверное, это упростит процесс и сделает его ещё быстрее.

## 💬 Задать вопрос
Все предложения и замечания приветствуются! Пожалуйста, используйте специальные каналы для вопросов и обсуждений. Помощь гораздо ценнее, если она предоставляется публично, чтобы ею могли воспользоваться больше людей.

| Type                            | Platforms                               |
| ------------------------------- | --------------------------------------- |
| 🚨 **Баг-репорты**              | [GitHub Трекер]                  |
| 🎁 **Feature Requests & Идеи** | [GitHub Pull Requests]                  |

[gitHub трекер]: https://github.com/self-destruction/AiAutoCover/issues
[github pull requests]: https://github.com/self-destruction/AiAutoCover/pulls
## 👩‍💻 Контрибьютеры и поддержка 🐸
Спасибо [NeuroDonu](https://github.com/NeuroDonu) за помощь ❤
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=self-destruction/AiAutoCover&type=Date&theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=self-destruction/AiAutoCover&type=Date" />
  <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=self-destruction/AiAutoCover&type=Date" />
</picture>

[![](https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20Coffee%20for%20Morning&emoji=:☕&slug=intercross&button_colour=c69d8a&font_colour=000000&font_family=Arial&outline_colour=000000&coffee_colour=FFDD00)](https://ko-fi.com/intercross) &nbsp;
[![](https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20Beer%20for%20the%20Night&emoji=🍺&slug=intercross&button_colour=FFDD00&font_colour=000000&font_family=Arial&outline_colour=000000&coffee_colour=ffffff)](https://www.buymeacoffee.com/intercross)  
