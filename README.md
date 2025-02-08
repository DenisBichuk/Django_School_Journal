# This is my pet project, a prototype of school journal app.
*This is its Django based version, you can find FastApi based one [here](https://github.com/DenisBichuk/FastAPI_School_Journal)*

---
## Installation and local deploy
Follow these simple steps to local deploy.
* Clone the repo:
```
git@github.com:DenisBichuk/Django_School_Journal.git
```
* Run Docker app and docker-compose:
```
docker-compose up -d
```
```
sudo docker-compose run web python manage.py migrate
```

* App is available. Follow the link to see docs
```
http://127.0.0.1:8000/swagger/
```
