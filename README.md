# django-backend-notesapp
## Frontend and Backend integrated for the blogapp developed
- sudo apt-get update
- sudo apt upgrade
- sudo apt get git
- sudo apt-get install ngrok-client
- sudo apt-get python3-pip
- sudo apt-get nodejs
- sudo apt-get npm
- git clone "https://github.com/codebotx/react-frontend-blogapp"
- sudo iptables -t nat -A PREROUTING -p tcp --dport 80 -j REDIRECT --to-ports 3000
- cd blogapp/notes
- npm i
- npm run build
- npm install serve -g (if this doesn't work use supersu)
- serve -s build 

open another connection to the instance

- cd blogapp/notes
- pip install django
- pip install django-cors-headers
- pip install django-rest
- python manage.py runserver
