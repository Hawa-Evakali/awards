## Project name
* Awards

## Description
It's a web application that allows register and signin to the website. In addition, it allows one to be able to view all the post projects for other users to see and rate according to defined specifications.

## User Story
* A user can view their profile page.
* A user can view posted projects and their details.
* A user can post their projects.
* a user can search for projects.

## Snapshots
* Projects display
* Registration display
* Login display

## Setup Instalation
* Copy the github repository url
* Clone to your computer
* Open terminal and navigate to the directory of the project you just cloned to your computer
* Run the following command to start the server using virtual environment


```
python3.8 -m venv  virtual
```
- To activate the virtual environment

```
source virtual/bin/activate
```

```
pip install -r requirements.txt
```

```
pip install bootstrap5
```
- Edit the .env file and replace the values
with your own Cloudinary credentials and 
database credentials

- To run the server

```
python manage.py runserver

```