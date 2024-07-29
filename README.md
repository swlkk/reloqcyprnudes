# reloqcyprnudes
Просто голый RASA, никаких пользовательских действий, никаких дополнительных конфигов

###
- Python 3.10

1. Создаем и активируем виртуальное окружение:
    ```sh
    python -m venv venv
    venv\Scripts\activate
    ```
3. Устанавливаем либы:
    ```sh
    pip install -r requirements.txt
    ```
4. Инициализируем RASA
    ```sh
    rasa init

    enter
    y
    n
    ```
5. Копируем в Data nlu.yml, rules.yml, stories.yml

6. Копируем в главную директорию domain.yml, config.yml

7. Указать свои данные для credentails.yml(закину в личку)

10. Тренеруем и запускаем RASA
    ```sh
    rasa train
    rasa run
    ```
