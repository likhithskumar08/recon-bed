# recon-bed

### System requirements
- Python 3.10
- Django 4.2.4
- Postgres 15.2
------------

### 1. Create of virtual environment 
Create the virtual environment using conda or local env

- Conda environment
Open the terminal and enter the following command:<br />`$ conda create -n <environment_name> python=3.10`<br />
Once the environment has been created, activate the environment:<br />`$ conda activate <environment_name>`

- local environment
Open the terminal and enter the following command:<br />`$ virtualenv env`<br />
Now, activate the virtual environment with the following command:<br />`$ . env/bin/activate`<br />

------------
### 2. Clone project to the local machine
In the terminal, navigate to the location where the project folder has to be created. Then enter the git command to clone the project:<br />`$ https://github.com/appinessgit/recon-bed.git` <br />
Once cloned, change the directory to **recon**<br /> `$ cd recon`

------------

### 3. Running the project

- Install the python packages listed in the **requirements.txt** file.
Enter the following command in the terminal:<br />`$ pip install -r requirements.txt`<br/>
- To start the development server, run the following command:<br /> `$ python manage.py runserver`
By default the server runs on port`8000`
Check whether the server is running by going to [localhost:8000/admin](localhost:8000/admin "localhost:8000/admin") <br />

------------
#### References
Anaconda : https://docs.anaconda.com/anaconda/ <br />Django : https://www.djangoproject.com/
