This is the repository for Food Ordering Application
<img width="1437" alt="Screenshot 2024-03-17 at 16 47 16" src="https://github.com/RishabhManojAgrawal/scueats/assets/114192710/61c6fe6d-8975-4b89-9f80-149393ff2021">

Installation steps:
- create virtual environment and activate it: 
virtualenv env
source env/bin/activate

- Install the packages from requirements.txt file: 
pip install -r requirements.txt

- Install Postgres

- Run migrations: 
python manage.py migrate

- Run the server:
python manage.py runserver
