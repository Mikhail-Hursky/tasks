# Задание №8: HttpClient

## Требования:

1. Реализуйте бекэнд для вашего проекта, используя, например, [json-server](https://www.npmjs.com/package/json-server?activeTab=readme)
2. Создайте сервис для работы с `HttpClient`.
3. Реализуйте часть методов по схеме `Promise`, а часть по схеме `Observable`.
4. Реализуйте `TimingInterceptor`, который в консоль выводит длительность запросов. Добавьте фильтр, чтобы время подсчитывалось только для конкретных запросов.
5. Реализуйте сервис AppSettings, который должен загружать настройки приложения из `localStorage` используя сервис `LocalStorageService`, разработанный ранее. Если в `localStorage` ничего нет, то загружать из файла _assets/app-settings.json_ и при удачной загрузке записывать эти данные в `localStorage`, используя сервис `LocalStorageService`. При неудачной попытке делать две попытки. Если загрузить все-таки не удалось, то устанавливать значения настроек поумолчанию.

## Рекомендации:

В качестве настроек можно применять считать применение различных фильтров для книг по `category`, дате, направление сортировки и т.д.

## Оценка

Максимальная оценка - **50** баллов
