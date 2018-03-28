# django-starter
Make sure npm is installed in your computer.
It is recommended that you keep your charts in the directory below.
/django-starter/mysite/polls/static

Once you're sure, run this command:
npm install chart.js --save

A folder called 'node_modules' will appear.
Run the below command:
python manage.py collectstatic

This will extract the charts into an admin folder in the directory.
Run the following command to have the server up:
python manage.py runserver