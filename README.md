# Обрезка ссылок с помощью Битли

- Программ имеет 2 режима работы:
  - Сократить ссылку
  - Узнать количество переходов по ссылке Битли

### Как установить

- Создать в корне проекта файл **.env**, указать в нем токен ,Битли, пример в файле **.env.example**
- Python3 должен быть установлен
- Затем используйте `pip` (или `pip3`, еслить есть конфликт с Python2) для установки зависимостей: 
    ```
    pip install -r requirements.txt
    ```

- Рекомндуется использовать [virtualenv/venv](https://docs.python.org/3/library/venv.html) для изоляции проекта.


### Как пользоваться

- Запустить проект через консоль и указать аргументом ссылку: 
    ```python3 main.py https://dvmn.org
       https://bit.ly/3yNcL9f
    ```
    ```python3 main.py https://bit.ly/3yNcL9f
       Количество переходов по ссылке битли: 5
    ```

### Цель проекта

Код написан в образовательный целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).

