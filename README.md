## ⚙  How to run your program on MAC
------------------

``` 
xcode-select --install
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install python3
pip3 install virtualenv

# If you have xcode, homebrew, python3, virtualenv you can start from here 

virtualenv create-env
pip install -r requirements.txt
source create-env/bin/activate
python manage.py makemigrations
python manage.py migrate --run-syncdb
python manage.py runserver

``` 

## ⚙ Demo
------------------ 

![Main Page](https://github.com/mayankkt9/Covid-Tracker/blob/master/1.png)
![Main Page](https://github.com/mayankkt9/Covid-Tracker/blob/master/2.png)