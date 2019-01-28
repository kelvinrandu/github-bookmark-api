# github-bookmark-api
a Github open source bookmark project 

## DESCRIPTION
A github open source bookmark project built using JavaScript ( React )  and a REST API written in Python ( Flask ) which is going to persist, forming the backend of the application

## REQUIREMENTS
Minimum requirements needed to run this application include;
- [Python 3](https://www.python.org/download/releases/3.0/)
- [MongoDB](https://www.mongodb.com/)
- Free-forever[Okta](https://developer.okta.com/signup/) account

## TESTING THE APPLICATION
- clone [this](https://github.com/kelvinrandu/github-bookmark-api) repository
- replace  client_id and issuer_url in the file kudos_oss/app/http/web/app/src/Main/index.js to match your credentials as per your okta developer account
- export environment variable
``` $ export MONGO_URL=mongodb://mongo_user:mongo_secret@0.0.0.0:27017/ ```
- spin up the mongoDB container
``` $ docker-compose up ```
- to run the backend (flask application) type the code below in your terminal in the root folder
``` $ FLASK_APP=$PWD/app/http/api/endpoints.py FLASK_ENV=development pipenv run python -m flask run --port 4433 ```
- to run the frontend(React application) navigate to kudos_oss/app/http/web/app and type the code below in your terminal
``` $ npm start```

## ENQUIRIES
- for clarifications,enquiries or questions you can contact the developer through randukelvin@gmail.com