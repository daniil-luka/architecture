# Задание 1 - декомпозиция на микрофронтенды

## Выбор подхода

Для решения задачи был выбран подход Webpack Module Federation, так как он прост в реализации, позволяет деполить MF-модули независимо друг от друга, а также размещать их на разных доменах. 

## Выделение микрофронтендов

По стратегии вертикальной нарезки, была выделены следующие микрофронтенды:

- auth - выполняет авторизацию/регистрацию пользователя
- photos - отвечает за отображение и удаление фотографий
- upload - отвечает за загрузку фотографий
- users - управляет отображением профиля и его редактированием.

# Задание 2 - проектирование архитектуры
[Задание 2](https://drive.google.com/file/d/1kbrOtnSIY_o7s_JgY0rioUjph9McBXUD/view)
