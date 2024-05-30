# Secret manager project

## step creation project (0-step)

Delete virtual enviroment

Create a new virtual enviroment

~~~
python -m venv venv
~~~

Activate virtual enviroment

~~~
source venv/Scripts/activate
~~~

install python dependencies

~~~
pip install -r requirements.txt
~~~

## Execute program

~~~
flask --app secret_manager.app run --debug
~~~

add /secret-manager to the dropped link