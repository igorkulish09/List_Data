List_Data

This project is created for a test task ("displaying a list of any elements from the database").

Installation
To deploy the project on your local machine, follow these steps:

1. Clone the repository:

git clone https://github.com/igorkulish09/List_Data.git
cd List_Data

2. Install dependencies:

pip install -r requirements.txt

3. Create a superuser:

python manage.py createsuperuser

4. Apply migrations:

python manage.py  makemigrations
python manage.py migrate

Running the Project
Run the Django development server:

python manage.py runserver localhost:8000

Administrative Panel:
The Item model is already registered in the administrative panel. 
You can manage it using the administrative interface by visiting http://127.0.0.1:8000/admin/.

