# **What To DO, on Developer side?**

## **STEP 1**

- Clone the git repo in your Terminal, **git@github.com:geekpnx/weather_webapp.git**.

	- With the command:

		`git clone git@github.com:geekpnx/weather_webapp.git`


## **STEP 2**

- Create virtual environment with **venv**.

	- With the command:

		`python3 -m venv .venv --prompt weather_webapp`


- Activate **venv**

	- With the command:

		`source .venv/bin/activate` 


## **STEP 3**

- Install requirements.

	- With the command:

		`make dev-install`

## **STEP 4**

**Note:** Before you create the database, please make sure your **PostgreSQL** are runnning and you able to access **postgres** database with the username **postgres**
- Create your project database (for this project name it `weather_webapp`), by running the python script inside **createDB.py** file.

	- With the command:

		`python3 -m createDB`

## **STEP 5**

- Create your apps.

	- With the command:

		`make dev-startapp apps=user` 

		and

		`make dev-startapp apps=weather` 