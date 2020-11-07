# PP.Kurylo
КАЧАЄМО ЧЕРЕЗ КЛОН або напряму цілим файлом(скачуємо .zip) git clone "https://github.com/ValentynKurylo/PP.Kurylo.git"
СТВОРЮЄМО ВІРТУАЛЬНЕ СЕРЕДОВИЩЕ

git install virtualenv - якщо ще у вас немає virtualenv venv - (venv) це назва для нашого віртуального середовища

source venv/bin/active - щоб активувати наше середовище

pip install -r requirements.txt - для того щоб забрати всі мої залежності

Ну і для того щоб зберегти всі залежності, які ви самі собі поставили можна використати pip freeze > requirements.txt команду

Для запуску сервера ми напишемо gunicorn --reload "main:create_app()" де --reload перезапускає сервер автоматично і вам не прийдеться кожного разу робити це самому, а просто потрібно перезагружати сторінку "main:create_app()" (main) - наш файл (create_app()) - функція яку ми викликаємо

для того щоб вийти з venv потрібно прописавти - venv deactivate
