## Видеоплеер
[Видеоплеер](https://efekta.github.io/video-player-jslib/dist/index.html)


## Яндекс поиск
[Яндекс поиск](https://efekta.github.io/video-player-jslib/dist/yandex.html)

### Как установить
1. Python3 должен быть уже установлен. 
2. Активировать виртуальное окружение

```
python3 -m venv env && source ./env/bin/activate
```

3. Затем используйте pip (или pip3, есть есть конфликт с Python2) 
для установки зависимостей:

```
pip install -r requirements.txt
```

4. Запуск автообновления страницы

- Все статические файлы положить в папку dist
- Запустить сервер командой:
```
livereload dist
```