# AiAutoCover
Данный блокнот позволяет заменить голос в песне всего в несколько кликов. Вам понадобятся ссылка на YouTube и ссылка на модель вокала. Всё!  
Используются open-source модели и репозиторий [UVR](https://github.com/Anjok07/ultimatevocalremovergui) для отделения вокала от инструментала и [RVC](https://github.com/Mangio621/Mangio-RVC-Fork) для преобразования вокала.

## Как работает

### Установка и подготовка

Подготовка к работе включает в себя установку зависимостей (UVR + RVC), скачивание исходного аудио и модели вокала.

### Обработка аудио

Здесь происходит отделение вокала от инструментала. Далее происходит дополнительная обработка от реверберации и эха, а также, есть возможность поэкспериментировать с настройками преобразования голоса. Затем происходит преобразование вокала с использованием выбранной модели

### Пост-обработка и финальные штрихи

После преобразования вокала следует пост-обработка, которая включает в себя компрессию, нормализацию, лёгкую реверберацию и разведение по стерео-панораме. Затем вокал и инструментал смешиваются обратно, и вуаля, ваш кавер готов!

### Повторное использование

Система позволяет возвращаться к любому предыдущему шагу без необходимости запускать полный процесс заново. Например, вы можете загрузить другую модель вокала и преобразовать её, не возвращаясь к отделению вокала от инструмента.

# TODO

Вот некоторые вещи, которые я планирую добавить или улучшить в AiAutoCover:

## Прикрутить Google Drive
Сейчас каждый раз приходится скачивать репозитории и устанавливать зависимости, так что первым делом надо сделать Google Drive основным хранилищем. Это облегчит жизнь и сэкономит время.

## DeepFake в v2: клипы на новом уровне
На следующем этапе планирую прикрутить DeepFake, чтобы можно было не только делать аудио-каверы, но и менять лица в клипах. Во прикол будет!

## Интеграция с SoundCloud, Spotify, Apple Music и другими платформами
Думаю, будет удобно, если добавить возможность напрямую скачивать треки из музыкальных стриминговых сервисов, таких как SoundCloud, Spotify или Apple Music. Наверное, это упростит процесс и сделает его ещё быстрее.

Все предложения и замечания приветствуются! Если у тебя есть идеи или ты нашел баг, открывай PR или issue.
