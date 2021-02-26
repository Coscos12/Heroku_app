# Heroku_app

Heroku_app это простой проект, сделанный при помощи языка Python и нескольких библиотек, таких как 
Dash, Pandas и Plotly. Данный проект отображает графики по таблицам, взятых на Alphavantage.
## Installation

Для быстрого и простого использования для начала перейдите в командной строке
в папку, где планируете разместить проект, а затем клонруйте весь репозиторий:
```bash
git clone https://github.com/Coscos12/Heroku_app.git
```
После этого установите все необходимые библиотеки:
```bash
pip install -r requirements.txt
```
## Usage
Запуск проекта локально:
```bash
python app.py
```
Таблица с именами и сокращениями валют 
```bash
Heroku_app/names.py
```
Таблица с основными стилями и цветами
```bash
Heroku_app/styles.py
```
Для обновления данных таблиц необходимо в файл .env добавить свой api ключ в 
виде 
```bash
ALPHAVANTAGE_API_KEY=1111111111111111
```
и после этого запусить Get_data.py
```bash
python Get_data.py
```
##Contributing

Копируем/клонируем/пулим.... 

## License
[MIT](https://choosealicense.com/licenses/mit/)

## P.S.
Все держиться на огромной стопке костылей, поэтому сильно не пинаем, это мой первый проект