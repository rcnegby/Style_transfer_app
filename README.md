# Style transfer app

## Постановка решаемой задачи

Разработать приложение, которое позволит изменять стиль входного изображения.

## Описание предполагаемых инструментов решения

Библиотека 'pytorch' для работы с нейронными сетями

Библиотека 'gradio' для GUI

## Интерфейс

Пользователь взаимодействует с приложением через интерфейс.
Он может выбирать размер входного изображения, а также режим работы (быстрый, но с ограниченным набором стилей или медленный, но с возможностью подать на вход 2 изображения: контент и стиль)
Кроме этого, пользователь может видеть список задач с прогрессом их выполнения (особенно актуально при выборе 'медленного' способа)
Пример интерфейса предоставлен в файле Interface.jpg
