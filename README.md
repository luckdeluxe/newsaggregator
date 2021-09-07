# News Aggregator

_This Web application scrapes news articles from websites like theonion.com and present it in a webpage. This webapp combines the concept of django with web crawling_

## Starting 🚀

_These instructions will allow you to get a copy of the project running on your local machine for development and testing purposes._

Look **Deployment** to know how to deploy the project.


### Pre requirements 

_A series of step-by-step examples that tells you what to run to get a development environment running_

_Clone the repository_

```
git clone https://github.com/luckdeluxe/newsaggregator.git && cd newsaggregator
```

_Create a virtual Python environment:_

```
python3 -m venv .venv
```

_Activate the virtual environment_

```
sorce .venv/bin/activate
```

### Installation 🔧

_What things do you need to install the software and how to install them_
_You can install the requirements.txt file recursively_
```
pip install requirements.txt
```
_If you have any errors in the above way you can install it manually_

```
pip install [dependency==version]
```

```
beautifulsoup4==4.9.3
bs4==0.0.1
certifi==2021.5.30
charset-normalizer==2.0.4
Django==2.2.6
idna==3.2
python-decouple==3.4
pytz==2021.1
requests==2.26.0
soupsieve==2.2.1
sqlparse==0.4.1
urllib3==1.26.6
```

## Running the tests ⚙️

_Create database from models_

```
python3 manage.py makemigrations
python3 manage.py migrate
```

```
python3 manage.py runserver
```
