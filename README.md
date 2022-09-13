# Mapper

## Setup/Installation
Install Python requirements:
```shell
$ pip install -r requirements.txt
```


Then, run migrations and start the backend:
```shell
$ python server/manage.py migrate && python server/manage.py runserver
```


In another terminal, start Parcel running to compile the frontend assets
from `client` to the `server`'s static files:
```shell
$ cd client/
$ yarn install && yarn run start
```


Navigate to `http://localhost:8000` to view pages.

## About
 A customizable map generator app for use with tabletop roleplaying games or board games
