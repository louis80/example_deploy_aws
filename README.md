# flask-react-todo

To-do list application written with Python and Javascript using Client + API architechture
https://github.com/rHuggler/flask-react-todo
---

### Technologies
- React 16.4.1
- Python 3.6.4
- Flask 1.0.2
- Flask-SQLAlchemy 2.3.2
- SQLite 3.7.17

### How to run   
Clone repository via SSH or HTTP and `cd` into it.   

#### How to run the backend  
Open a console in the flask_api directory 
`pip install pipenv`  
`pipenv install`  
`pipenv shell`  
`pipenv run python flask_api/app.py --FLASK_CONFIG=dev`  


#### How to run the frontend   
Open a console in the react_client directory 
`npm install --prefix react_client`  
`npm start --prefix react_client`  


Access [http://127.0.0.1:3000](http://127.0.0.1:3000) (should open automatically).
