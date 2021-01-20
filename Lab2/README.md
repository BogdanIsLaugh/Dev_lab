# Загальне

Використовуваний дистрибутив Linux Ubuntu через це трохи змінені команди для встановлення та налаштування venv
# 2
Команди для створення віртуального середовища

sudo apt install pipenv;
sudo apt install python3-pip;
pipenv --three;
	

# 3
Команди для завантаження бібліотек

python3 -m pipenv install requests;
python3 -m pipenv install ntplib;

# 5
Перевірка роботи програми

python app.py
========================================
Результат без параметрів: 
No URL passed to function
========================================
Результат з правильною URL: 
Time is:  04:05:57 PM
Date is:  01-18-2021
Доброї ночі


# 6
Команда для завантаження бібліотеки для тестів

pipenv install pytest;

# 7
Перевірка та запуск тестів

pytest tests/tests.py
============================= test session starts ==============================
platform linux -- Python 3.8.5, pytest-6.2.1, py-1.10.0, pluggy-0.13.1
rootdir: /home/yyang/Dev_lab/Lab2
collected 4 items                                                              

tests/tests.py ....                                                      [100%]

============================== 4 passed in 0.92s ===============================


# 10
Перенаправлення stdout у файл

pytest tests/tests.py > results.txt; python app.py >> results.txt
