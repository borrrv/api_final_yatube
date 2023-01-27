# API for yatube project
### Description
In this project realized API for yatube project which was done in time education on Yandex.Practicum
### Technology
Python 3.7

Django 2.2.19

DRF 3.14.0

JWT + Djoser
### Start app in dev-mode
- Clone this repositories on your PC
- Create and start venv
```
python -m venv env

source env/scripts/activate

python3 -m pip install --upgrade pip
```
- Install requiremets.txt
```
pip install -r requirements.txt
``` 
- Run migrations
```
python manage.py migarte
```
- In folder with file manage.py use command for start project:
```
python3 manage.py runserver
```
### Examples requests
For interaction with endpoint, use the following commands:
(POST) Send username and password, get a token
```
api/v1/api-token-auth/
```
(GET, POST) Get list all posts or create new post
```
api/v1/posts/
```
(GET, PUT, PATCH, DELETE) Get, put, patch or delete post on ```id```
```
api/v1/posts/{post_id}/
```
(GET) Get list all groups
```
api/v1/groups/
```
(GET) Get information a group on ```id```
```
api/v1/groups/{group_id}/
```
(GET, POST) Get list all comments post or create new comment with ```post_id``` which we want to comment.
```
api/v1/posts/{post_id}/comments/
```
(GET, PUT, PATCH, DELETE) Get, put, patch or delete post comment
```
api/v1/posts/{post_id}/comments/{comment_id}/
```
### Author
github.com/borrrv

