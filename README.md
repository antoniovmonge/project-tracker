# Flask Web Application // project-tracker
## Keep track of our projects and tasks associated with those pojects.
---
Description:
- **Homepage:** display all the projects and button to add a project; each project is linked to an individual project page
- **Individual project page:** displays tasks associated with that project and there is a button to add a task
---
### Tools and Technologies
- **Database:** Postgress
- **Database connection:** SQLAlchemy
- **Web framework:** Flask
- **Webpages:** CSS and HTML (To be implemented) 
---

### Goal of the project:
Using and manipulating Databases with Python.

# Startup the project

The initial setup.

Create virtualenv and install the project:
```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv ~/venv ; source ~/venv/bin/activate ;\
    pip install pip -U; pip install -r requirements.txt
```

Unittest test:
```bash
make clean install test
```

Check for project-tracker in gitlab.com/{group}.
If your project is not set please add it:

- Create a new project on `gitlab.com/{group}/project-tracker`
- Then populate it:

```bash
##   e.g. if group is "{group}" and project_name is "project-tracker"
git remote add origin git@github.com:{group}/project-tracker.git
git push -u origin master
git push -u origin --tags
```

Functionnal test with a script:

```bash
cd
mkdir tmp
cd tmp
project-tracker-run
```

# Install

Go to `https://github.com/{group}/project-tracker` to see the project, manage issues,
setup you ssh public key, ...

Create a python3 virtualenv and activate it:

```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv -ppython3 ~/venv ; source ~/venv/bin/activate
```

Clone the project and install it:

```bash
git clone git@github.com:{group}/project-tracker.git
cd project-tracker
pip install -r requirements.txt
make clean install test                # install and test
```
Functionnal test with a script:

```bash
cd
mkdir tmp
cd tmp
project-tracker-run
```
