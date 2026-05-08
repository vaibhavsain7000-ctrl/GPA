# clone repo
git clone https://github.com/mohith7548/Graphical-Password-User-Authentincation

# Navigate to the folder
cd Graphical-Password-User-Authentincation

# Install dependencies; honestly this itself suffice to run this project, hence there's no requirements.txt file in here
pip install Django

# djanog stuff for database creation
python manage.py makemigrations
python manage.py migrate

# create admin account - Create a login to use on admin page
python manage.py createsuperuser

# Run Django server
python manage.py runserver
